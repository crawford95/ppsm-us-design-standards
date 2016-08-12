# About this Project

The [Draft U.S. Web Design Standards](https://standards.usa.gov) include a library of open source UI components and a visual style guide for U.S. federal government websites.

This project is takes the [web-design-standards/staging provides](https://github.com/18F/web-design-standards/tree/18f-pages-staging) branch of the Draft U.S. Web Design Standards and alters it so that healthcare professionals can easily use it on their Patient Portal powered by Surescripts LLC's [Patient Portal with Secure Messaging](http://surescripts.com/products-and-services/patient-portal-with-secure-messaging) product.

It is a very barebones version of the Draft U.S. Web Design Standards. We are limited by the CSS selectors that PPSM (my acronym, not SureScripts) supports. For most (almost all) healthcare agencies, their portal is hosted by off-site so they are limited to what they can alter.

This is more-or-less a guide to help healthcare professionals theme their installation of SMPP in an accessible and screen reader-friendly manner.

## Why Use This Project

The Draft U.S. Web Design Standards provides an amazing color palette and allows healthcare professionals to roll out accessible web elements to their Secure Messaging and Patient Portal installation.

This project was created for use on the [PDR Clinics](http://portal.pdrclinics.com) Patient Portal. Like the Draft U.S. Web Design Standards, this project is licensed under the Public Domain.

## Getting started

The application of this project to your installation of PPSM includes uploading images, applying CSS in the Appearance area, and hosting fonts off-site someplace. Follow the instructions located in `guides` to begin.

## Download

The project can be downloaded as a `.zip` file and then you'll just need to follow the instructions included in the `guides` folder.

```
ppsm-us-design-standards/
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

This project is tailored specifically for a HIPAA-compliant project. No support will be provided for this project. We will reply to all Issues posted to this project and work to resolve them.

The project maintainers, contributors, and sponsors are not responsible for any issues that arise from trying to apply and/ or maintain this project on your website.

## Licenses and attribution

Like the Draft U.S. Web Design Standards project, this project is licensed under the [public domain](LICENSE.md).

As stated in [CONTRIBUTING](CONTRIBUTING.md):
> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.

### A few parts of this project are not in the public domain

The Source Sans Pro font files in `contents/fonts` are a customized subset of [Source Sans Pro](https://github.com/adobe-fonts/source-sans-pro), licensed under the [SIL Open Font License](http://scripts.sil.org/cms/scripts/page.php?item_id=OFL), and copyright [Adobe Systems Incorporated](http://www.adobe.com/), with Reserved Font Name 'Source'. All Rights Reserved. Source is a trademark of Adobe Systems Incorporated in the United States and/or other countries.

The Merriweather font files in `contents/fonts` are from [Google Web Fonts](https://www.google.com/fonts#UsePlace:use/Collection:Merriweather:400,300,400italic,700,700italic), licensed under the [SIL Open Font License](http://scripts.sil.org/cms/scripts/page.php?item_id=OFL), and copyright [Sorkin Type Co](www.sorkintype.com) with Reserved Font Name 'Merriweather'.

The files in `contents/img` are from [Font Awesome](http://fontawesome.io/) by Dave Gandy under the [SIL Open Font License 1.1](http://scripts.sil.org/OFL).
