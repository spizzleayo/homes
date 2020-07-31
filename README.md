<p align="center">
  <a href="" rel="noopener">
 <img width=50px height=50px src="img/favicon.png" alt="Project logo"></a>
</p>

<h3 align="center">Nexter Homes</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> Own your home, own your freedom
    <br> 
</p>

## 🧐 About <a name = "about"></a>

The purpose of this project is to create the landing page for a company that sells premium houses.

### Prerequisites

You will need to have [Nodejs](https://nodejs.org/en/) in your system.

### Installing

Once you have Node Js on your system. You can see in the package.json all the scripts.

```
 "scripts": {
    "watch:sass": "node-sass sass/main.scss css/style.css -w",
    "devserver": "live-server",
    "start": "npm-run-all --parallel devserver watch:sass",
    "compile:sass": "node-sass sass/main.scss css/style.comp.css",
    "prefix:css": "postcss --use autoprefixer -b \"last 10 versions\" css/style.comp.css -o css/style.prefix.css",
    "compress:css": "node-sass css/style.prefix.css css/style.css --output-style compressed",
    "build:css": "npm-run-all compile:sass prefix:css compress:css"
  },

package.json

```

## ⛏️ Built Using <a name = "built_using"></a>

- HTML
- CSS Grids
- CSS Animation Effects
- SASS