# BRiCSS

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/ita-design-system/bricss?style=for-the-badge)](https://github.com/ita-design-system/briccs/releases)

A simple and customizable low-level CSS library generator with automatic documentation generation.

[Website](https://ita-design-system.github.io/bricss/) | [Example in use](https://itautomotive-dev.github.io/marques-blanches-ui/) | [BRiCSS Website UI](https://ita-design-system.github.io/bricss-website-ui/)

They are using BRiCSS:

| Skoda | Hyundai | OpenHive |
|-|-|-|
| [![Skoda Rent](https://cdn.jsdelivr.net/gh/ita-design-system/ita-medias@main/logo-skoda-rent.svg)](https://rent.skoda.fr/) | <a href="https://mocean-rent.hyundai.fr"><img src="https://github.com/user-attachments/assets/bf07dce5-ea7a-40b3-9b4a-f5bca2c607f1" alt="Hyundai Mocean Rent" height="26"></a> | <a href="https://openhive.eu"><img src="https://github.com/user-attachments/assets/95a7b956-abc4-4ac0-8ee7-86eb5d2e6a0c" width="128" alt="openhive"></a> |


## General principles

* **Simple responsive naming convention**: BRiCSS is a simple low-level CSS abstraction and a naming convention based on abbreviations of CSS class names and attributes.
* **CSS you really use**: Just set CSS properties you really use into your designs and code.
* **Responsive on-demand**: Optimized CSS output file size thanks to selective responsive CSS properties you really use.
* **Automatic documentation**: An interactive documentation of CSS output is automatically generated. [.](https://ita-design-system.github.io/bricss-website-ui/).
* **Low-engineered**: Only a browser is required.
* **JSON based**: BRiCSS is a JSON file base solution to generate a tailored CSS file library.
* **Offline**: Works even with no Internet connection.
* **Design Systems friendly**: Integrates seamlessly into a Design System.
* **Instant file size**: Instantly observe the file size impact of your settings.
* **Copy or download**: Just refresh your browser to get the latest version of your custom CSS library.

## Requirements

A text editor, a web server and a browser.

## Getting started

1. [Download](https://github.com/ita-design-system/bricss/archive/refs/heads/main.zip) or clone this repository the starter project and unpack to any web server.
2. **Edit** `build.json` file to fit your needs.
3. **Run through your browser!**: Interactive documentation is generated automatically. 
4. **Customize**: Replace all "Project Name" string into the `index.html` file to your own project name. Customize or remove Github link 

At first start, an onboarding menu with JSON examples is available to help populating your own `build.json`. At least one single CSS property is required to display documentation. When `build.json` is not empty, just click to download or copy your new CSS library.

All JSON examples are placed nto the folder `json_examples` or the repository.

