# Using This Project

We encourage you to read this project's [LICENSE](../LICENSE.md), its [CONTRIBUTING policy](../CONTRIBUTING.md), and [README](../README.md).

This project takes the [Draft U.S. Web Design Standards](https://github.com/18F/web-design-standards/) project and modifies it for use on SureScripts LLC's [Patient Portal with Secure Messaging](http://surescripts.com/products-and-services/patient-portal-with-secure-messaging) product. It is essentially a front-end theme for a healthcare facility's PPSM installation. It changes how patients (users) interact with your Patient Portal and makes everything more accessible.

## Included Files

This project contains everything that is needed to theme your PPSM installation. All of the files necessary for theming are present in the `contents` folder. This guide is available in a few different formats within the `guides` folder.

```
ppsm-us-design-standards/
├── contents/
│   ├── css/
│   ├── fonts/
│   ├── img/
│   ├── js/
└── guides/
```

## Regarding Fonts and JavaScript

Most healthcare agencies do not host their installation of Patient Portal with Secure Message. For these facilities (which is almost everyone), the files included in the `fonts` and `js` folders will need to be hosted by a webhost. Unfortunately, the files in these folders cannot be uploaded to PPSM and then called upon by our stylesheet from there.

Our suggestion is to go through a [CDN](https://en.wikipedia.org/wiki/Content_delivery_network), or host the files on a web host or [VPS](https://en.wikipedia.org/wiki/Virtual_private_server) like [DigitalOcean](https://www.digitalocean.com/). Remember: only use these for media hosting.

## Theming the Portal Using CSS

The first step to theming the portal is bringing up the Appearances menu within the PPSM admin area. We'll go through each tab under Appearances to ensure that your portal is themed correctly.

Under "General", you want to ensure that you're using a logo that has a transparent background (usually ending in `.png`). Delete any Header Background or Page Background that you may be using. You can add them back later but they should be removed so you can see the changes we are making.

The "Theme" tab is where we begin theming the Patient Portal. This project uses the colors set forth by the Draft U.S. Web Design Standards. They can be viewed [here](https://standards.usa.gov/colors/). The color palette is more-or-less modelled after [Healthcare.gov](http://www.healthcare.gov).

Replace the color codes so they reflect the following:
```
Basic Colors
├── Background
│   └── #ffffff
├── Logo Background
│   └── #ffffff
├── Left Column
│   └── #ffffff
├── Center Column
│   └── #ffffff
├── Right Column
│   └── #ffffff
├── Login Links
│   └── #0071bc
├── Footer Links
│   └── #ffffff
├── Content Links
│   └── ##0071bc
└── guides/
```

```
Basic Colors
├── contents/
│   ├── css/
│   ├── fonts/
│   ├── img/
│   ├── js/
└── guides/
```

```
Basic Colors
├── contents/
│   ├── css/
│   ├── fonts/
│   ├── img/
│   ├── js/
└── guides/
```

```
Basic Colors
├── contents/
│   ├── css/
│   ├── fonts/
│   ├── img/
│   ├── js/
└── guides/
```

Within the `Advanced` tab in Appearances, you will have the option of adding Custom CSS to your Patient Portal.
Transfer the contents of `smpp-us-design-standards/contents/css/stylesheet.css` into the CSS textbox and click "Publish". `Stylesheet.css` is tailor-made for PPSM, so you shouldn't get any errors. If you do, you may have existing CSS which needs to be deleted in order for this to work.
