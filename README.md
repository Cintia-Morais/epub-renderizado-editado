## 📘 Projeto EPUB “Três Anos de Silêncio”
## 1. Sobre o Projeto ⚙️

Este repositório contém a versão digital estruturada do livro “Três Anos de Silêncio”, desenvolvida para distribuição em formato EPUB 3, com foco em compatibilidade, organização interna e padronização técnica.

O objetivo principal do projeto é consolidar o material original em um EPUB limpo, funcional, validado e fiel ao design estabelecido no Adobe InDesign.

---


## 2. Autoria e Produção 🖇️
Autora da história:

Cibely
Responsável pelo texto original, narrativa e propriedade intelectual da obra.

Renderização e diagramação no Adobe InDesign

A composição gráfica, layout inicial e exportação primária do arquivo foram realizados no Adobe InDesign, garantindo fidelidade visual, tipografia consistente e organização editorial.

Edição, estruturação e preparação digital

Cintia
Responsável por:

- Revisão estrutural de todos os arquivos XHTML

- Otimização do CSS para leitura digital

- Correção de referências internas (links, capitulação, TOC, NCX)

- Reorganização do OPF e manifestos

- Implementação correta das fontes

- Padronização semântica para conformidade com EPUB 3

- Ajustes na capa, metadata e navegação

- Montagem das pastas e compactação final no padrão EPUB

---
## 3. Estrutura do EPUB 📂

O projeto segue a estrutura recomendada para EPUB 3:
```css
/
│── mimetype
│── META-INF/
│   └── container.xml
│── OEBPS/
│   ├── content.opf
│   ├── toc.xhtml
│   ├── toc.ncx
│   ├── css/
│   ├── font/
│   ├── image/
│   └── capítulos .xhtml

```
---

Pontos importantes da estrutura

- mimetype descompactado e no topo do arquivo

- Arquivos XHTML limpos, sem tags proprietárias

- Navegação moderna via toc.xhtml e compatibilidade com leitores antigos via toc.ncx

- Fontes declaradas corretamente no OPF e carregadas via @font-face

- CSS padronizado, eliminando classes automáticas do InDesign (_idGenObject*, CharOverride*, etc.)

- Sem scripts externos, garantindo compatibilidade universal

----

## 4. Metadados e Navegação 🧭

O EPUB foi configurado com:

- Título, autor, idioma e identificador único

- Data de modificação conforme padrão W3C/EPUB

- Capa oficialmente registrada no OPF via properties="cover-image"

- Navegação declarada com epub:type="toc"

- Landmarks (epub:type="landmarks") indicando pontos essenciais do livro

Essas configurações garantem que leitores como Kindle Previewer, Thorium, Adobe Digital Editions, Kobo e Apple Books reconheçam corretamente a estrutura.

---

## 5. Objetivo Final 🎯

Este repositório consolida:

- A versão digital oficial do livro

- A diagramação produzida no InDesign

- A edição técnica e reconstrução do EPUB feita por Cintia

O propósito é manter um arquivo confiável, bem organizado e pronto para uso em plataformas de leitura ou distribuição.

----

## 6. Manutenção 🔧

O projeto é mantido por:

Cintia
Responsável pela edição técnica, estruturação, validação e evolução contínua do EPUB.

Atualizações incluem ajustes estruturais, melhorias de compatibilidade e refinamento da organização interna.
