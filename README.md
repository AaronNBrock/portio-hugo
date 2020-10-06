<h1>Portio Hugo</h1>
<img src="./docs/images/screenshot-cropped.jpg" alt="screenshot" width="100%">

Portio is a simple, minimal and responsive Portfolio Hugo Theme. Portio is well organized, well-formatted and named accordingly so it’s easy to change any and all of the design. Portio is built with Bootstrap 4. You can customize it very easy to fit your needs.

## Table of Contents

- [Live Demo](https://portio-hugo.staticmania.com/)
- [Installation](#installation)
- [Main Features](#features)
- [Support](#support)
- [Licensing](#licensing)
- [Hire](#hire)

## Installation

Before installing this theme, please read the [Hugo Quick Start](https://gohugo.io/getting-started/quick-start/)

1. Add the repository into your Hugo Project repository as a submodule, 

   ```bash
   git submodule add git@github.com:StaticMania/portio-hugo.git themes/portio
   ```

2. Copy the `.forestry`, `data`, `content`, `static`, `resources` & `config.toml` files from the `exampleSite` directory and paste it on you Hugo Project repository/directory. From the site home directory:
   ```bash
   cp -a themes/portio/exampleSite/* .
   ```

3. Build your site with `hugo serve` and see the result at `http://localhost:1313/`.

## Features

- Responsive Ready.
- Powered by Bootstrap 4.
- Blog Support.
- Well formatted code.
- Easy Customization.
- Formspree Contact form.
- Google Analytics.
- Forestry Integrated.
- Crafted for Personal Portfolio

## Customize

This theme leverages SCSS.  So, in order to customize this theme you must have hugo "extended" installed.

1. Copy the [`_variables.scss`](./assets/scss/_variables.scss) file from `themes/portio/assets/scss/_variables.scss` to `assets/scss/_variables.scss`:

   ```bash
   mkdirs -p ./assets/scss/
   cp ./themes/portio/assets/scss/_variables.scss ./assets/scss/
   ```

2. Update the `_variables.scss` with your desired customization!
3. **Tip:** For more options, take a look at [Theming Bootstrap](https://getbootstrap.com/docs/4.0/getting-started/theming/)

## Support

Have some question or facing any technical trouble feel free to [Contact Us](https://staticmania.com/contact/)

## Licensing

This Repository is licensed under the [MIT](https://github.com/StaticMania/portio-hugo/blob/master/LICENSE) License

## Hire

Need help to build HUGO websites with your custom requirements. Feel free to [contact](https://staticmania.com/contact/) with us. We provide custom development service for HUGO.
