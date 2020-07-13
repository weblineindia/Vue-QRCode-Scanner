# Vue QR Scanner Component

A Vue.js based QR Code scanner component, allowing you to detect and decode QR codes without leaving the browser.

## Table of contents

- [Browser Support](#browser-support)
- [Getting started](#getting-started)
- [Usage](#usage)
- [Want to Contribute?](#want-to-contribute)
- [Need Help / Support?](#need-help)
- [Collection of Components](#collection-of-components)
- [Changelog](#changelog)
- [Credits](#credits)
- [License](#license)
- [Keywords](#Keywords)

## Browser Support

#### `QrcodeStream`

This component fundamentally depends on the [Stream API](https://caniuse.com/#feat=stream).

![Chrome](https://raw.github.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/src/safari/safari_48x48.png) | ![Edge](https://raw.github.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![IE](https://raw.github.com/alrra/browser-logos/master/src/archive/internet-explorer_9-11/internet-explorer_9-11_48x48.png) |
--- | --- | --- | --- | --- |
83.0 ✔ | 77.0  ✔ | 13.1.1 ✔ | 83.0 ✔ | Not verified |

1. Chrome requires [HTTPS or localhost](https://sites.google.com/a/chromium.org/dev/Home/chromium-security/deprecating-powerful-features-on-insecure-origins) (see _Troubleshooting_ for help)
2. Safari also requires HTTPS **even** on localhost. It also won't work in:
   - _Chrome for iOS_, _Firefox for iOS_,
   - WkWebView component of native iOS apps
   - web apps added to home screen (PWA mode) **prior to iOS 13.4**

#### `QrcodeDropZone` and `QrcodeCapture`

The newest API these components depend on is the [FileReader API](https://caniuse.com/#feat=filereader).

![Chrome](https://raw.github.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/src/safari/safari_48x48.png) | ![Edge](https://raw.github.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![IE](https://raw.github.com/alrra/browser-logos/master/src/archive/internet-explorer_9-11/internet-explorer_9-11_48x48.png) |
--- | --- | --- | --- | --- |
83.0 ✔ | 77.0  ✔ | 13.1.1 ✔ | 83.0 ✔ | 10+ |

## Getting started

Install the npm package:

``` bash
npm install vue-weblineindia-qrcode-scanner
#OR
yarn add vue-weblineindia-qrcode-scanner
```

## Usage

Use the `<vue-weblineindia-qrcode-scanner>` component:

Either import the components independantly for local registration:

```javascript
import { QrcodeStream, QrcodeDropZone, QrcodeCapture } from 'vue-weblineindia-qr-scanner'

const MyComponent = {

  components: {
    QrcodeStream,
    QrcodeDropZone,
    QrcodeCapture
  },

  // ...
))
```

Or register all of them globally:

```javascript
import Vue from "vue";
import VueQrcodeReader from "vue-weblineindia-qr-scanner";

Vue.use(VueQrcodeReader);
```
## Import Css
- `<link href="`[vue-weblineindia-qr-scanner.css](https://unpkg.com/vue-weblineindia-qr-scanner/lib/vue-qrcode-reader.css)`" rel="stylesheet">`
- `<script src="`[vue-weblineindia-qr-scanner.browser.js](https://unpkg.com/vue-weblineindia-qr-scanner/lib/vue-qrcode-reader.browser.js)`"></script>`


## Want to Contribute?

- Created something awesome, made this code better, added some functionality, or whatever (this is the hardest part).
- [Fork it](http://help.github.com/forking/).
- Create new branch to contribute your changes.
- Commit all your changes to your branch.
- Submit a [pull request](http://help.github.com/pull-requests/).

-----

## Need Help? 

We also provide a free, basic support for all users who want to use this VueJS QR code scanner in their software project. In case you want to customize this VueJS QR code scanner to suit your development needs, then feel free to contact our [VueJS developers](https://www.weblineindia.com/hire-vuejs-developer.html).

-----

## Collection of Components
We have built many other components and free resources for software development in various programming languages. Kindly click here to view our [Free Resources for Software Development](https://www.weblineindia.com/software-development-resources.html )

------

## Changelog

Detailed changes for each release are documented in [CHANGELOG.md](./CHANGELOG.md).

## Credits

vue-weblineindia-qr-scanner is inspired by [vue-qrcode-reader](https://www.npmjs.com/package/vue-qrcode-reader).

## License

[MIT](LICENSE)

[mit]: https://github.com/weblineindia/Vue-CK-Editor/blob/master/LICENSE

## Keywords

vue-weblineindia-qr-scanner, vue, vuejs, vue-component, qrcode, qrcode-reader, qrcode-scanner, webrtc
