# Google Web Starter Kit

> A starting point for multi-device web development


## Overview

[Web Starter Kit](http://developers.google/com/web/starter-kit) is a starting point for multi-screen web development, encompassing opinionated recommendations on boilerplate and tooling for building an experience that works great across multiple devices.

The project aims to align with the mobile web recommendations made by Google's [Web Fundamentals](http://developers.google.com/web/fundamentals) and includes boilerplate, tooling and best practices that fall in line with how we think multi-screen webapps should be built.

## Features

* Mobile-optimized HTML Boilerplate
* Sexy minimalist layout
* Visual component style guide
* Gulp build tooling *(Optional)*
  * LiveReload
  * Cross-device synchronization of clicks, scrolls, navigation, form filling.
  * Image optimization
  * JavaScript minification and optimization
  * CSS optimization
  * HTML minification
  * PageSpeed performance reporting
  * CSS autoprefixing

## Quickstart

[Download](http://github.com/google/web-starter-kit/archive/master.zip) the kit or clone this repository and build on what we include in the `app` directory. 

You will want to checkout `index.html` (the default starting point, slide-out menu), 'alt-layout.html' (if you prefer a horizontal nav) or `basic.html` (no layout).

If you would like to use the optional tooling we provide:

```sh
# Install the gulp globally so you can run it in the terminal. Only need to to this once.
$ npm install --global gulp

# Install the local dependencies from package.json (requires Node)
$ npm install 

# Build the current project
$ gulp

# Watch files / LiveReload / Cross-device sync
$ gulp watch

# Run the deployed version of your app against PageSpeed
$ gulp pagespeed
```

## Requirements

In addition to requiring [Node](http://nodejs.org), [Ruby](https://www.ruby-lang.org/) and the [Sass gem](http://sass-lang.com/install) are also required.

## Web Performance

Web Starter Kit strives to give you a high performance starting point out of the box and we actively work on delivering the best [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/) score and frame-rate possible.

## Browser support

At present, we officially aim to support the following browsers:

* IE10, IE11, IE Mobile 10 
* FF 30, 31
* Chrome 34, 35
* Safari 7, 8
* Opera 23, 24
* iOS Safari 7, 8
* Opera Coast
* Android / Chrome 4.4, 4.4.3
* Blackberry 1.0

This is not to say that Web Starter Kit cannot be used in browsers older than those reflected, but merely that our focus will be on ensuring our layouts work great in the
above. 

## Inspiration

Web Starter Kit is inspired by [Mobile HTML5 Boilerplate](http://html5boilerplate.com/mobile/) and Yeoman's [generator-gulp-webapp](https://github.com/yeoman/generator-gulp-webapp), having taken input from contributors to both projects during development. 

## Contributing

Contributions, questions and comments are all welcomed and encouraged. For code contributions please see our [Contribution guide](https://github.com/google/web-starter-kit/wiki/Contributing) before submitting a patch.

## License

Apache 2.0  
Copyright 2014 Google Inc
