# :zap: Terracota App

* Single page optimised HTML-CSS-JS website to market a holiday home and aim for perfect SEO
* **Note:** to open web links in a new window use: _ctrl+click on link_

![GitHub repo size](https://img.shields.io/github/repo-size/AndrewJBateman/terracota-app?style=plastic)
![GitHub pull requests](https://img.shields.io/github/issues-pr/AndrewJBateman/terracota-app?style=plastic)
![GitHub Repo stars](https://img.shields.io/github/stars/AndrewJBateman/terracota-app?style=plastic)
![GitHub last commit](https://img.shields.io/github/last-commit/AndrewJBateman/terracota-app?style=plastic)

## :page_facing_up: Table of contents

* [:zap: Terracota App](#zap-terracota-app)
  * [:page\_facing\_up: Table of contents](#page_facing_up-table-of-contents)
  * [:books: General info](#books-general-info)
  * [:camera: Screenshots](#camera-screenshots)
  * [:signal\_strength: Technologies](#signal_strength-technologies)
  * [:floppy\_disk: Setup](#floppy_disk-setup)
  * [:computer: Code Examples](#computer-code-examples)
  * [:cool: Features](#cool-features)
  * [:clipboard: Status \& To-Do List](#clipboard-status--to-do-list)
  * [:clap: Inspiration](#clap-inspiration)
  * [:file\_folder: License](#file_folder-license)
  * [:envelope: Contact](#envelope-contact)

## :books: General info

* Built with HTML, CSS and JavaScript with Bootstrap 5 CSS and Javascript
* Progressive Web App (PWA)
* CSS and Javascript are minimised to reduce initial render/First Contentful Paint time.
* SEO optimised

## :camera: Screenshots

![Example screenshot](./imgs/home.png).

## :signal_strength: Technologies

* [HyperText Markup Language HTML](https://developer.mozilla.org/en-US/docs/Glossary/HTML)
* [Cascading Style Sheets CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) styling

## :floppy_disk: Setup

* Open index.html using [Visual Studio Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer). Changes are updated automatically on server.

## :computer: Code Examples

* index.html extract showing how new format webp images are marked up in HTML

```html
          <div class="carousel-item active">
            <picture>
              <source
                type="image/webp"
                class="d-block w-100"
                srcset="./images/bg/house-front.webp"
                alt="house front view"
              />
              <source
                type="image/jpeg"
                class="d-block w-100"
                srcset="/images/bg/house-front.jpg"
                alt="house front view"
              />
              <img
                src="/images/bg/house-front.jpg"
                class="d-block w-100"
                alt="house front view"
              />
            </picture>
            <div class="carousel-caption col-md-6 col-10 col-offset-md-6">
              <h1>Terracota</h1>
              <p class="carousel-image-text">
                Una vivienda moderna, muy bien equipada y muy confortable. En
                este alojamiento se respira tranquilidad: ¡relájate con toda la
                familia!
              </p>
            </div>
          </div>
```

## :cool: Features

* Deployed to web
* SEO optimised

## :clipboard: Status & To-Do List

* Status: Working.
* To-Do: SEO

## :clap: Inspiration

* [Anna Monus: 9 tricks to eliminate render blocking resources](https://blog.logrocket.com/9-tricks-eliminate-render-blocking-resources/)

## :file_folder: License

* This project is licensed under the MIT License - see the LICENSE file for details.

## :envelope: Contact

* Repo created by [ABateman](https://github.com/AndrewJBateman), email: `gomezbateman@yahoo.com`
