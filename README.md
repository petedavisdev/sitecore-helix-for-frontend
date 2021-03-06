# Sitecore Helix For Frontend - A Sitecore User Group Tale

The repository is an extended example of a possible front-end solution to Sitecore helix projects that [David Moore](https://twitter.com/Moorag81) and I presented in the [Cardiff Sitecore user group](https://www.meetup.com/sug-uk/events/252868135/)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine.

### Prerequisites
* Visual Studio Code
* Latest version of [node.js](https://nodejs.org/en/)

### Installing
1. Clone this repository to your local machine, this can be any directory.
2. Create a folder in your inetpub directory C:\inetpub\wwwroot\SugukDemo
3. CD to the root directory and run ```npm install```
4. Run `npm run build` in command line and this install project dependencies, compile the frontend assets in the **dist** directory
5. Run `npm run publish` to copy the compiled files to the inetpub directory

## Folder structure
```text
dist
Feature
    Products
        Scripts
            products.js
        Views
            ProductComponent
                ProductComponent.cshtml
                productComponent.js
                __tests__
                    // tests here
Foundation
    // nothing in here yet
Project
    Commercial.Website
        Scripts
            commercial.js
            // helper/service modules here...
        Styles
            commercial.scss
            // base styles here such as _breakpoints, _variables, _placeholders etc...
        Views
            Products
                ProductComponent
                    product-component.js
                    _product-component.scss
                    __tests__
                        // mocks here
                        // tests here
            Widgets
                CommercialWidget
                    CommercialWidget.cshtml
                    commercial-widget.js
                    _commercial-widget.scss
                    __tests__
                        // mocks here
                        // tests here
    Residential.Website
        Scripts
            commercial.js
            // helper/service modules here...
        Styles
            commercial.scss
            // base styles here such as _breakpoints, _variables, _placeholders etc...
        Views
            Products
                ProductComponent
                    product-component.js
                    _product-component.scss
                    __tests__
                        // mocks here
                        // tests here

```

## Built With
* [NPM](https://www.npmjs.com/) - Dependency management and build scripts
* [Lerna](https://lerna.js.org/) - Multi-package dependency manager and script runner
* [Rollup](https://rollupjs.org/) - JS bundler
* [sass](http://sass-lang.com/) - CSS preprocessor

## Authors

* **Matthew Neil** - *Initial work* - [Pheon1x84](https://github.com/Phoen1x84)
* **Pete Davis** - [petedavisdev](https://github.com/petedavisdev) Twitter: [@petedavisdev](https://twitter.com/petedavisdev)
