## What is min-doc 

min-doc is an **hackable simple documentation generation template** that support **.md=>html** and **.plantuml=>img** tool.

## Advantage

* **Easy install** - All you need is having **node and npm installed**
* **Easy editing** - All you need is text editor like(nodepad++) to **draw different graph and styling**.
* **Good verision control** - Because **plantuml** allow Easily create UML Diagrams(Flow chart,Sequence diagram,Class diagram) from **simple textual description**.
* **Github-like html style** - Because when **html generated from markdown** using the **github markdown css**
* **hackable** - Want to integrate with [mindmap](https://github.com/fex-team/kityminder-editor)?Want to have .mp3 file?Simply Modify the `generate.js` file and **create your own documentation generation tool**.

## Target User
1. User that are familar with markdown.[Best markdown tutorial with online WYSIWYG Editior online](https://www.markdowntutorial.com/)
2. User that need to draw **massive** uml and diagram **efficiently**.[Plantuml](!http://plantuml.com/)


## Usage

```
git clone git@github.com:chungchi300/min-doc.git yourProject
npm install
npm run build
/*
if you want to automatically generate file after editing.
npm run build-watch
*/
```

## Example


[![在优酷上观看](https://t4.ftcdn.net/jpg/01/12/56/73/240_F_112567399_fVHoy5kIkNXdDnwCSpaSkDC3wmH9NVCs.jpg)](https://vimeo.com/266230854)


* [Self](./docs/self/gen.doc.html)
* [Demo](https://github.com/chungchi300/min-doc-demo)


## Optional Tool

Despite you can edit using any text editor,there is some **plugins and editor** suggested to use for **real time preview & wysiwyg**
on **single file**

### Editor

VS Code Studio

### Plugins

VS Code Studio

* [plantuml](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml#review-details)

* [markdown](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
