# Carbon Design System  
A Gatsby‑powered static site showcasing the Carbon Design System documentation.

![Deployment status](https://github.com/carbon-design-system/carbon-website/workflows/Deployment%20status/badge.svg)

This is the [Carbon Design System website](https://www.carbondesignsystem.com/).  
It's built using the [gatsby-theme-carbon](https://gatsby.carbondesignsystem.com/) with [GatsbyJS](https://www.gatsbyjs.org/).

---

## 📑 Table of Contents
- [About](#about)
- [Structure](#structure)
- [Prerequisites](#prerequisites)
- [Develop](#develop)
- [Build](#build)
- [Usage](#usage)
- [Support](#support)
- [License](#license)

---

## About
A clean and comprehensive documentation website for the Carbon Design System, powered by Gatsby.

---

## 📂 Structure

```text
src
├── components
├── data
├── gatsby-theme-carbon
├── images
├── pages
├── styles
└── util

## 🍽️ Prerequisites

Node.js v16+
Yarn v1 or v2+

## 👩‍💻 Develop

- 🤝 [Contribution guidelines](.github/CONTRIBUTING.md)
- 📚 [Content and Markdown guidelines](https://gatsby-theme-carbon.now.sh/components/markdown)
- 🗺 [Navigation guidelines](https://gatsby-theme-carbon.now.sh/guides/navigation/sidebar)

- `yarn install` – installs all project dependencies
- `yarn dev` – start the development server
- `yarn dev:clean` – use this if you have cache issues
- `lint:js` – lint your JavaScript files
- `format` - run Prettier

If you need more detailed information on how to set up your machine to develop locally, please take a look at our [wiki](https://github.com/carbon-design-system/carbon-website/wiki).

## 🚀 Build

Running the build command generates all the files and places them in the `public` folder.

```bash
yarn build

