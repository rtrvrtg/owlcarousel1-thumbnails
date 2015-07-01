# Owl Carousel v1 Thumbnail Plugin

Thumbnail display plugin for [Owl Carousel v1](https://github.com/OwlFonk/OwlCarousel).

## Authorship

Written by [Geoffrey Roberts](mailto:g.roberts@blackicemedia.com)

## License

MIT

## Features

* Uses hidden area to contain thumbnail content
* Supports scrollable thumbnail paginator
* Responsive thumbnail area
* Supports vertical thumbnail areas

## Requirements

* jQuery
* Owl Carousel
* [Owl Carousel v1 Pseudo-Plugins](https://github.com/rtrvrtg/owlcarousel1-pseudoplugins)

## Installation

In the `<head>` of your page, after you set up your jQuery, Owl Carousel and jquery-throttle-debounce `<script>` items, add the following:

```html
<script type="text/javascript" src="owlcarousel-thumbnails.js"></script>
```

## Usage

Since this plugin uses the Owl Carousel v1 Pseudo-Plugin architecture, you can apply it to some Owl Carousel settings by using the following:

```javascript
var settings = {};
OwlThumbs.Plugin.applyTo(settings);
$(".owl-carousel").owlCarousel(settings);
```

@TODO more documentation on settings

## Changelog

### v0.1

Initial commit