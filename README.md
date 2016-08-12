# About this Project

The [Draft U.S. Web Design Standards](https://standards.usa.gov) include a library of open source UI components and a visual style guide for U.S. federal government websites.

This project is takes the [web-design-standards/staging provides](https://github.com/18F/web-design-standards/tree/18f-pages-staging) branch of the Draft U.S. Web Design Standards and alters it so that healthcare professionals can easily use it on their Patient Portal powered by Surescripts LLC's [Secure Messaging and Patient Portal](http://surescripts.com/products-and-services/patient-portal-with-secure-messaging) product.

It is a very barebones version of the Draft U.S. Web Design Standards. We are limited by the CSS selectors that SMPP (my acronym, not SureScripts) supports. For most (almost all) healthcare agencies, their portal is hosted by off-site so they are limited to what they can alter.

This is more-or-less a guide to help healthcare professionals theme their installation of SMPP in an accessible and screen reader-friendly manner.

## Why Use This Project

The Draft U.S. Web Design Standards provides an amazing color palette and allows healthcare professionals to roll out accessible web elements to their Secure Messaging and Patient Portal installation.

This project was created for use on the [PDR Clinics] Patient Portal. Like the Draft U.S. Web Design Standards, this project is licensed under the Public Domain.

## Getting started

`Coming Soon`

## Download

The project can be downloaded as a `.zip` file and then you'll just need to follow the instructions included. The Getting Started snippet above outlines most of the steps as well.

```
smpp-us-design-standards/
├── contents/
│   ├── css/
│   ├── fonts/
│   ├── img/
└── guides/
```

## Making Changes/ Contributing

We tend to update this as changes are made to the `staging` branch of the Draft U.S. Web Design Standards. The `staging` branch is the bleeding edge of development.

For complete instructions on how to contribute code, please read [CONTRIBUTING.md](CONTRIBUTING.md).

## Contact/ Support

This project is tailored specifically for a HIPAA-compliant project. I will not provide support for this project. I will reply to all Issues posted to this project and work to resolve them.

## Reuse of open-source style guides

Much of the guidance in the Draft U.S. Web Design Standards leans on open source designs, code, and patterns from other civic and government organizations, including:

* Consumer Financial Protection Bureau’s [Design Manual](https://cfpb.github.io/design-manual/)
* U.S. Patent and Trademark Office’s [Design Patterns](http://uspto.github.io/designpatterns/)
* Healthcare.gov [Style Guide](http://styleguide.healthcare.gov/)
* UK’s Government Digital Service’s [UI Elements](http://govuk-elements.herokuapp.com/)
* Code for America’s Chime [Styleguide](https://github.com/chimecms/chime-starter)
* Pivotal Labs [Component Library](http://styleguide.cfapps.io/)

## Licenses and attribution

### A few parts of this project are not in the public domain

The Source Sans Pro font files in `src/fonts` are a customized subset of [Source Sans Pro](https://github.com/adobe-fonts/source-sans-pro), licensed under the [SIL Open Font License](http://scripts.sil.org/cms/scripts/page.php?item_id=OFL), and copyright [Adobe Systems Incorporated](http://www.adobe.com/), with Reserved Font Name 'Source'. All Rights Reserved. Source is a trademark of Adobe Systems Incorporated in the United States and/or other countries.

The Merriweather font files in `src/fonts` are from [Google Web Fonts](https://www.google.com/fonts#UsePlace:use/Collection:Merriweather:400,300,400italic,700,700italic), licensed under the [SIL Open Font License](http://scripts.sil.org/cms/scripts/page.php?item_id=OFL), and copyright [Sorkin Type Co](www.sorkintype.com) with Reserved Font Name 'Merriweather'.

The files in `src/img` are from [Font Awesome](http://fontawesome.io/) by Dave Gandy under the [SIL Open Font License 1.1](http://scripts.sil.org/OFL).

The files in `src/stylesheets/_scss/lib/bourbon` are from [Bourbon](http://bourbon.io/), copyright [thoughtbot](https://thoughtbot.com/), inc., under the [MIT license](https://github.com/thoughtbot/neat/blob/master/LICENSE.md).

The files in `src/stylesheets/_scss/lib/neat` are from [Neat](http://neat.bourbon.io/), copyright [thoughtbot](https://thoughtbot.com/), inc., also under the [MIT license](https://github.com/thoughtbot/neat/blob/master/LICENSE.md).

The file `src/stylesheets/css/normalize.min.css` is from [Normalize.css](https://github.com/necolas/normalize.css), copyright Nicolas Gallagher and Jonathan Neal, under the [MIT license](https://github.com/necolas/normalize.css/blob/master/LICENSE.md).

The file `src/js/component.js` includes `politespace.js` from [Politespace](https://github.com/filamentgroup/politespace), copyright Zach Leatherman, under the [MIT license](https://github.com/filamentgroup/politespace/blob/master/LICENSE).

The file `src/js/vendor/html5shiv.js` is from [HTML5 Shiv](https://github.com/afarkas/html5shiv), copyright Alexander Farkas (aFarkas), under the [MIT license](https://github.com/aFarkas/html5shiv/blob/master/MIT%20and%20GPL2%20licenses.md).

The file `src/js/vendor/jquery-1.11.3.min.js` is from [jQuery](https://jquery.com/), copyright The jQuery Foundation, under the [MIT license](https://jquery.org/license/).

The file `src/js/vendor/rem.min.js` is from [REM unit polyfill](https://github.com/chuckcarpenter/REM-unit-polyfill), copyright Chuck Carpenter, under the [MIT license](https://github.com/chuckcarpenter/REM-unit-polyfill/blob/master/LICENSE.md).

The file `src/js/vendor/respond.js` is from [Respond.js](https://github.com/scottjehl/Respond), copyright Scott Jehl, under the [MIT license](https://github.com/scottjehl/Respond/blob/master/LICENSE-MIT).

The file `src/js/vendor/selectivizr-min.js` is from [Selectivizr](http://selectivizr.com/), copyright Keith Clark, under the [MIT license](http://opensource.org/licenses/mit-license.php).

The files `docs/assets/js/vendor/prism.js` and `assets-styleguide/css/prism.css` are from [Prism](http://prismjs.com/), copyright Lea Verou, under the [MIT license](https://github.com/PrismJS/prism/blob/gh-pages/LICENSE).

### The rest of this project is in the public domain

The rest of this project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.
