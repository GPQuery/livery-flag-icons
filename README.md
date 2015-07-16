# GPQuery/livery-flags

A collection of flag icons and images for GPQuery-Livery.

## Overview


## Production


### Gulp

 - [`gulp-svg-sprite`](https://github.com/jkphl/gulp-svg-sprite) which wraps [`svg-sprite`](https://github.com/jkphl/svg-sprite)
 - [`gulp-svg-symbols`](https://github.com/Hiswe/gulp-svg-symbols) creates single SVG and CSS files
 - [`gulp-iconfont`](https://github.com/nfroidure/gulp-iconfont) produces:
   - Fonts in `svg`, `ttf`, `eot`, and `woff` formats (see [gulp-svgicons2svgfont](https://github.com/nfroidure/gulp-svgicons2svgfont))
   - CSS font template (see [`gulp-iconfont-css`](https://github.com/backflip/gulp-iconfont-css))
 - [`gulp-svgmin`](https://github.com/ben-eb/gulp-svgmin)
 - [`gulp-svg2png`](https://github.com/akoenig/gulp-svg2png)

### Build

```
dist/

├── 
├── 
├── 
├── png/
│  ├── country-1x1/
│  ├── country-4x3/
│  ├── maritime/
│  ├── overlays/
│  └── racing/
├── 
├── 
│  ├── 
│  ├── 
│  ├── 
│  └──
├── 
├── 
└──
```

Amongst the variety of flags types and sizes:

* National `png` - 16px by 11px
* National `svg` - 4:3 ratio
* National `svg` - 1:1 ratio
* State and Provincial Flags:
  * United States
  * Australia
  * Brazil
  * Canada
  * Germany
  * Spain
  * Russia
* Miscellaenous Flags:
  * Motor Racing Flags
  * Maritime & Signal Flags

The standards upon which flag names and codes are based include:

* [ISO 3166-1 alpha-2](http://en.wikipedia.org/wiki/ISO_3166-1_alpha-2) two-letter country codes
* [ISO 3166-1 alpha-2](http://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) three-letter country codes
* [ISO 3166-1 numeric](http://en.wikipedia.org/wiki/ISO_3166-1_numeric) three-digit country codes
* Nation Name, Colloquial
* Nation Name, Official
* Endonym, English
* Endonym, Native
* Denonym, Singular
* Denonym, Plural
* Grand Prix Race Name


## Credits

This repository was forked from [stevenrskelton/flag-icon](https://github.com/stevenrskelton/flag-icon), which in turn was based on [lipis/flag-icon-css](https://github.com/lipis/flag-icon/css):

* [Demonstration](http://lipis.github.io/flag-icon-css) of the original CSS vector-based compilation by [lipis]
* [Demonstration](https://github.com/stevenrskelton/flag-icon/blob/master/README.md) of additional flags, features, and Polymer Web Components library being written by [stevenrskelton](https://github.com/stevenrskelton).

* Flag image files from the [famfamfam](http://www.famfamfam.com/lab/icons/flags/) icon library
* Flag `svg` files from [Wikimedia Commons](http://commons.wikimedia.org/wiki/Category:SVG_sovereign_state_flags)
* Flag `png` files compressed with [pngcrush](http://en.wikipedia.org/wiki/Pngcrush)


## License

[MIT License](http://opensource.org/licenses/MIT) © 2013-2015
