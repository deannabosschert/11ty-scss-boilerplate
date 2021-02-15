# Project Title

[![Netlify Status](https://api.netlify.com/api/v1/badges/581f4463-abc5-4dcb-802f-dad50e683c44/deploy-status)](https://app.netlify.com/sites/11ty-scss-boilerplate/deploys)
 ... [link to live demo]()-->
![screenshot of website]()
# 11ty-scss-boilerplate

## Table of Contents

    -   [✅ To-do](#--to-do)
    -   [📋 Concept](#---concept)
    -   [⚙️ Installation](#---installation)
    -   [👯🏿‍ Features (+ wishlist)](#------features----wishlist-)
    -   [ℹ️ Resources](#---resources)
    -   [🗺️ License](#----license)

## ✅ To-do

See the [project board](https://github.com/deannabosschert/11ty-scss-boilerplate/projects/1) for my current to-do's

## 📋 Concept


## ⚙️ Installation

Clone this repo to your own device:

```bash
$ git https://github.com/deannabosschert/11ty-scss-boilerplate.git
```

Navigate to this folder and run:

```bash
npm install
```

Then:

```bash
npm run dev
```

#### Dependencies

```json
"devDependencies": {
    "@11ty/eleventy": "^0.11.0",
    "cross-env": "^7.0.2",
    "ejs": "^3.0.1",
    "express": "^4.17.1",
    "node-fetch": "^2.6.0",
    "npm-run-all": "^4.1.5",
    "rimraf": "^3.0.2",
    "csvtojson": "^2.0.10",
    "mkdirp": "^0.5.1"
  },
  "dependencies": {
    "nodemon": "^2.0.2"
  }
```

#### Scripts

```json
  "scripts": {
    "predev": "rimraf _site",
    "dev:eleventy": "npx @11ty/eleventy --formats=html,njk,ejs,gif,jpg,png,css --serve --port=3000",
    "dev:css": "sass --watch assets/scss:_site/assets/css/",
    "dev": "cross-env ELEVENTY_ENV=development run-p dev:*",
    "debug": "DEBUG=* eleventy",
    "prebuild": "rimraf _site",
    "build": "cross-env ELEVENTY_ENV=production run-s build:*",
    "build:eleventy": "eleventy",
    "build:css": "node-sass --importer node_modules/node-sass-glob-importer/dist/cli.js assets/scss/index.scss _site/assets/css/index.css"
  }
```

## 👯🏿‍ Features (+ wishlist)

_What would you like to add (feature wishlist / backlog)?_

-   [ ] 

## ℹ️ Resources

### Credits


### (Small) inspiration sources


## 🗺️ License

Author: [Deanna Bosschert](https://github.com/deannabosschert), , license by
[MIT](https://github.com/deannabosschert/11ty-scss-boilerplate/blob/master/LICENSE)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
