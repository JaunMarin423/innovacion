## Table of Contents

* [Versions](#versions)
* [Demo](#demo)
* [Quick Start](#quick-start)
* [Documentation](#documentation)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Licensing](#licensing)
* [Useful Links](#useful-links)


## Versions

[<img src="https://github.com/creativetimofficial/public-assets/blob/master/logos/html-logo.jpg?raw=true" width="60" height="60" />](https://www.creative-tim.com/product/material-kit?ref=mkr-readme)[<img src="https://github.com/creativetimofficial/public-assets/blob/master/logos/vue-logo.jpg?raw=true" width="60" height="60" />](https://www.creative-tim.com/product/vue-material-kit?ref=mkr-readme)[<img src="https://github.com/creativetimofficial/public-assets/blob/master/logos/react-logo.jpg?raw=true" width="60" height="60" />](https://www.creative-tim.com/product/material-kit-react?ref=mkr-readme)[<img src="https://github.com/creativetimofficial/public-assets/blob/master/logos/react-native-logo.jpg?raw=true" width="60" height="60" />](https://www.creative-tim.com/product/material-kit-react-native?ref=mkr-readme)[<img src="https://github.com/creativetimofficial/public-assets/blob/master/logos/figma-logo.jpg?raw=true" width="60" height="60" />](https://demos.creative-tim.com/material-kit-figma/presentation.html?ref=mkr-readme)[<img src="https://github.com/creativetimofficial/public-assets/blob/master/logos/wordpress-logo.jpg?raw=true" width="60" height="60" />](https://themeisle.com/themes/hestia/?ref=creativetim)[<img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/photoshop-logo.jpg" width="60" height="60" />](https://github.com/creativetimofficial/material-kit/tree/photoshop)[<img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/sketch-logo.jpg" width="60" height="60" />](https://github.com/creativetimofficial/material-kit/tree/sketch)


[View More](https://demos.creative-tim.com/material-kit/index.html)


## Quick start

- `npm i material-kit-react`
- [Download from Github](https://github.com/creativetimofficial/material-kit-react/archive/master.zip).
- [Download from Creative Tim](https://www.creative-tim.com/product/material-kit-react).
- Install with [Bower](https://bower.io/): ```bower install material-kit-react```.
- Clone the repo: `git clone https://github.com/creativetimofficial/material-kit-react.git`.


## Documentation
The documentation for the Material Kit React is hosted at our [website](https://demos.creative-tim.com/material-kit-react/#/documentation/tutorial).


## File Structure
Within the download you'll find the following directories and files:

```
material-kit-react
.
├── CHANGELOG.md
├── ISSUE_TEMPLATE.md
├── LICENSE.md
├── README.md
├── bower.json
├── gulpfile.js
├── jsconfig.json
├── package.json
├── Documentation
│   ├── assets
│   │   ├── css
│   │   ├── img
│   │   │   └── faces
│   │   └── js
│   └── tutorial-components.html
├── public
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
└── src
    ├── index.js
    ├── logo.svg
    ├── assets
    │   ├── css
    │   │   └── material-kit-react.css.map
    │   ├── img
    │   │   ├── examples
    │   │   └── faces
    │   ├── jss
    │   │   ├── material-kit-react
    │   │   │   ├── components
    │   │   │   └── views
    │   │   │       ├── componentsSections
    │   │   │       ├── landingPageSections
    │   │   └── material-kit-react.js
    │   └── scss
    │       ├── core
    │       │   ├── mixins
    │       │   └── variables
    │       ├── plugins
    │       └── material-kit-react.scss
    ├── components
    │   ├── Badge
    │   │   └── Badge.js
    │   ├── Card
    │   │   ├── Card.js
    │   │   ├── CardBody.js
    │   │   ├── CardFooter.js
    │   │   └── CardHeader.js
    │   ├── Clearfix
    │   │   └── Clearfix.js
    │   ├── CustomButtons
    │   │   └── Button.js
    │   ├── CustomDropdown
    │   │   └── CustomDropdown.js
    │   ├── CustomInput
    │   │   └── CustomInput.js
    │   ├── CustomLinearProgress
    │   │   └── CustomLinearProgress.js
    │   ├── CustomTabs
    │   │   └── CustomTabs.js
    │   ├── Footer
    │   │   └── Footer.js
    │   ├── Grid
    │   │   ├── GridContainer.js
    │   │   └── GridItem.js
    │   ├── Header
    │   │   ├── Header.js
    │   │   └── HeaderLinks.js
    │   ├── InfoArea
    │   │   └── InfoArea.js
    │   ├── NavPills
    │   │   └── NavPills.js
    │   ├── Pagination
    │   │   └── Pagination.js
    │   ├── Parallax
    │   │   └── Parallax.js
    │   ├── Snackbar
    │   │   └── SnackbarContent.js
    │   └── Typography
    │       ├── Danger.js
    │       ├── Info.js
    │       ├── Muted.js
    │       ├── Primary.js
    │       ├── Quote.js
    │       ├── Small.js
    │       ├── Success.js
    │       └── Warning.js
    └── views
        ├── Components
        │   ├── Components.js
        │   └── Sections
        │       ├── SectionBasics.js
        │       ├── SectionCarousel.js
        │       ├── SectionCompletedExamples.js
        │       ├── SectionDownload.js
        │       ├── SectionExamples.js
        │       ├── SectionJavascript.js
        │       ├── SectionLogin.js
        │       ├── SectionNavbars.js
        │       ├── SectionNotifications.js
        │       ├── SectionPills.js
        │       ├── SectionTabs.js
        │       └── SectionTypography.js
        ├── LandingPage
        │   ├── LandingPage.js
        │   └── Sections
        │       ├── ProductSection.js
        │       ├── TeamSection.js
        │       └── WorkSection.js
        ├── LoginPage
        │   └── LoginPage.js
        └── ProfilePage
            └── ProfilePage.js
```


## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://github.com/creativetimofficial/public-assets/blob/master/logos/chrome-logo.png?raw=true" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/firefox-logo.png" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/edge-logo.png" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/safari-logo.png" width="64" height="64"> <img src="https://raw.githubusercontent.com/creativetimofficial/public-assets/master/logos/opera-logo.png" width="64" height="64">



## Resources
- Demo: <https://demos.creative-tim.com/material-kit-react/#/>
- Download Page: <https://www.creative-tim.com/product/material-kit-react>
- Documentation: <https://demos.creative-tim.com/material-kit-react/#/documentation/tutorial>
- License Agreement: <https://www.creative-tim.com/license>
- Support: <https://www.creative-tim.com/contact-us>
- Issues: [Github Issues Page](https://github.com/creativetimofficial/material-kit-react/issues)
- **Dashboards:**

## Reporting Issues

We use GitHub Issues as the official bug tracker for the Material Kit. Here are some advices for our users that want to report an issue:

1. Make sure that you are using the latest version of the Material Kit. Check the CHANGELOG from your dashboard on our [website](https://www.creative-tim.com/).
2. Providing us reproducible steps for the issue will shorten the time it takes for it to be fixed.
3. Some issues may be browser specific, so specifying in what browser you encountered the issue might help.

## Licensing

- Copyright 2019 Creative Tim (https://www.creative-tim.com/)

- Licensed under MIT (https://github.com/creativetimofficial/material-kit/blob/master/LICENSE.md)

## Useful Links

- [Tutorials](https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w)
- [Affiliate Program](https://www.creative-tim.com/affiliates/new) (earn money)
- [Blog Creative Tim](http://blog.creative-tim.com/)
- [Free Products](https://www.creative-tim.com/bootstrap-themes/free) from Creative Tim
- [Premium Products](https://www.creative-tim.com/bootstrap-themes/premium) from Creative Tim
- [React Products](https://www.creative-tim.com/bootstrap-themes/react-themes) from Creative Tim
- [Angular Products](https://www.creative-tim.com/bootstrap-themes/angular-themes) from Creative Tim
- [VueJS Products](https://www.creative-tim.com/bootstrap-themes/vuejs-themes) from Creative Tim
- [More products](https://www.creative-tim.com/bootstrap-themes) from Creative Tim
- Check our Bundles [here](https://www.creative-tim.com/bundles?ref="mk-github-readme")

### Social Media

Twitter: <https://twitter.com/CreativeTim>

Facebook: <https://www.facebook.com/CreativeTim>

Dribbble: <https://dribbble.com/creativetim>

Instagram: <https://www.instagram.com/CreativeTimOfficial>
