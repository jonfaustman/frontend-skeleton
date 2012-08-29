# Front-end Skeleton

A collection of resources to have the perfect (for me) starting point for front-end development projects.

## Starring
* [HTML5 Boilerplate](https://github.com/h5bp/html5-boilerplate)
    * [Modernizr](https://github.com/Modernizr/Modernizr)
* [Twitter Bootstrap](https://github.com/twitter/bootstrap)
    * [sass-twitter-bootstrap](https://github.com/jlong/sass-twitter-bootstrap)
* [Compass](https://github.com/chriseppstein/compass)
* [jQuery](https://github.com/jquery/jquery)
* [iOS-Orientationchange-Fix](https://github.com/scottjehl/iOS-Orientationchange-Fix)

## Getting Started

Clone the repo `get clone git@github.com:jonfaustman/front-end-skeleton.git` or [download the latest release](https://github.com/jonfaustman/front-end-skeleton/zipball/0.1.0).

Replace UA-XXXXX-X with your Google Analytics site id, or delete the Google Analytics snippet from SKELETON.js.

Search the project for SKELETON and change it to your project/app's name. You can of course skip this step if you prefer.

### Quick Start

If you're not using Sass (what's wrong with you?), you can remove the src directory (or not) and edit SKELETON.css directly. You can add `<link rel="stylesheet" href="static/css/bootstrap/responsive.css">' after SKELETON.css if you want to use Twitter Bootstrap's responsive styles.

If you want to use Sass, but happen to not have Sass or Compass installed, you'll want to do that.

#### Sass

```ruby
gem instal sass
```
#### Compass

```ruby
gem install compass
```

After Sass and Compass are up and running, feel free to edit the Sass files as you see fit. I prefer to keep all the project/application styles in a single file (SKELETON.sass) but also include imports/variables/mixins, etc. in _base.sass in case there is a need to create additional Sass files throughout.

Customize the Twitter Bootstrap Sass files to meet your project's needs. Be aware that this can complicate upgrading Twitter Bootstrap.

#### Markup and included files

Edit the markup to fit your needs, it's only meant to help get you started.

The Twitter Bootstrap JavaScript files are included in `static/js/bootstrap/`; add them below the scripts before the end of the body as you need them.

## License

### Major Components:
* HTML5 Boilerplate: The Unlicense
* Modernizr: BSD/MIT License
* Twitter Bootstrap: Apache License, Version 2.0
* Compass: modified MIT License
* jQuery: MIT/GPL License
* iOS-Orientationchange-Fix: MIT/GPL v2.0 License

### Personal Components:
The Unlicense