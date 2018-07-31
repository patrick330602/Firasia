# Firasia
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fpatrick330602%2FFirasia.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fpatrick330602%2FFirasia?ref=badge_shield)

This is Firasia, a fork of SARASA GOTHIC based on Fira Code and Source Han Sans.

## To build

You need [Node.js](https://nodejs.org/en/) 8.5 (or newer), [otfcc](https://github.com/caryll/otfcc), [AFDKO](http://www.adobe.com/devnet/opentype/afdko.html) and [ttfautohint](https://www.freetype.org/ttfautohint) installed, then run:

```bash
npm install
```

after the NPM packages are installed, run

```bash
node build ttf
```

to build the TTF files, it would be in `build/out` directory.

To build TTC, type

```bash
node build ttc
```

instead, the files would be in `build/ttc` directory.

# License

See License.

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fpatrick330602%2FFirasia.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fpatrick330602%2FFirasia?ref=badge_large)