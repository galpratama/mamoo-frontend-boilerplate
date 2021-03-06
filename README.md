# Navillera Frontend

Simple and easy to use front-end boilerplate with hot reloading for kickstart your project

## What's included?
- Clean and organized folder structure. (From sass-guidelin.es)
- sass-boilerplate (by HugoGiraudel)
- Bourbon Mixin
- Bootstrap Responsive Mixins (respondto)
- Bootstrap
- jQuery
- Font Awesome
- BrowserSync (autoreload html,css,php)
- SASS compile (using node-sass)
- CSS Minify
- Autoprefixr
- Source maps (css)
- Image minify
- Icon font generator from svg placed in `icons` folder

## How to use?
1. Clone this repo
2. Run `npm install -g gulp` to install gulp to your system. (you must have node.js and npm installed first). If it doesn't working, try adding `sudo` in front of the command.
3. Run `npm install` 
4. Run `gulp` to start.
5. Done!

## Folder structure

```
styles/
|
|– base/
|   |– _reset.scss       # Reset/normalize
|   |– _typography.scss  # Typography rules
|   …                    # Etc.
|
|– components/
|   |– _buttons.scss     # Buttons
|   |– _carousel.scss    # Carousel
|   |– _cover.scss       # Cover
|   |– _dropdown.scss    # Dropdown
|   …                    # Etc.
|
|– layout/
|   |– _navigation.scss  # Navigation
|   |– _grid.scss        # Grid system
|   |– _header.scss      # Header
|   |– _footer.scss      # Footer
|   |– _sidebar.scss     # Sidebar
|   |– _forms.scss       # Forms
|   …                    # Etc.
|
|– pages/
|   |– _home.scss        # Home specific styles
|   |– _contact.scss     # Contact specific styles
|   …                    # Etc.
|
|– themes/
|   |– _theme.scss       # Default theme
|   |– _admin.scss       # Admin theme
|   …                    # Etc.
|
|– utils/
|   |– _variables.scss   # Sass Variables
|   |– _functions.scss   # Sass Functions
|   |– _mixins.scss      # Sass Mixins
|   |– _helpers.scss     # Class & placeholders helpers
|
|– vendors/
|   |– _bootstrap.scss   # Bootstrap
|   |– _jquery-ui.scss   # jQuery UI
|   …                    # Etc.
|
|
-– main.scss             # Main Sass file
```

## Modification License

```
Copyright (c) 2017 Galih Pratama

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
