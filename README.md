# Etch Lite

Etch Lite is a stripped-down variant of Etch for [Hugo](https://gohugo.io) focused on minimizing page size. A live demo is available at https://lukasjoswiak.github.io/etch/.

<img src="https://raw.githubusercontent.com/LukasJoswiak/etch/master/images/screenshot_small.png" alt="screenshot" width="545px">

## Features:

* Homepage with list of posts.
* Support for pages.
* Responsive design for optimized mobile experience.
* Minimal CSS (single file, minified).
* No external dependencies, no JavaScript, no web fonts.
* Internationalization friendly: use default English translations or create your own

## Installation

To install `etch`, download the repository into the `themes` folder in the root of your site.

```
$ git submodule add https://github.com/LukasJoswiak/etch.git themes/etch
```

Then, use the theme to generate your site.

```
$ hugo server -t etch
```

Use the [sample configuration](https://github.com/LukasJoswiak/etch/wiki/Configuration#sample-configuration) as a starting point. See the [configuration](https://github.com/LukasJoswiak/etch/wiki/Configuration) page for more info.

Read the [wiki](https://github.com/LukasJoswiak/etch/wiki) to learn about more options.
