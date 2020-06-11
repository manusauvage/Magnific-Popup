# Magnific Popup Repository

Fast, light and responsive lightbox plugin, for jQuery and Zepto.js.

This is a fork of [Dmitry Semenov's original Magnific-Popup](https://github.com/dimsemenov/Magnific-Popup/releases), with minor fixes for my own usage. I find it useful, but you YMMV. 

## Location of relevant files

- Generated popup JS and CSS files are in folder [dist/](https://github.com/manusauvage/Magnific-Popup/tree/master/dist). 
- Source files are in folder [src/](https://github.com/manusauvage/Magnific-Popup/tree/master/src). They include [Sass CSS file](https://github.com/manusauvage/Magnific-Popup/blob/master/src/css/main.scss) and js parts (edit them if you wish to submit commit). 
- Website (examples & documentation) is in folder [website/](https://github.com/dimsemenov/Magnific-Popup/tree/master/website).
- Documentation page itself is in [website/documentation.md](https://github.com/dimsemenov/Magnific-Popup/blob/master/website/documentation.md) (contributions to it are very welcome).


## Build 

To compile Magnific Popup by yourself, first of make sure that you have [Node.js](http://nodejs.org/), [Grunt.js](https://github.com/cowboy/grunt), [Ruby](http://www.ruby-lang.org/) and [Jekyll](https://github.com/mojombo/jekyll/) installed, then:

1) Copy repository

	git clone https://github.com/manusauvage/Magnific-Popup.git

2) Go inside Magnific Popup folder that you fetched and install Node dependencies

	cd Magnific-Popup && npm install

3) Now simply run `grunt` to generate JS and CSS in folder `dist` and site in folder `_site/`.

	grunt

Optionally:

- Run `grunt watch` to automatically rebuild script when you change files in `src/` or in `website/`.
- If you don't have and don't want to install Jekyll, run `grunt nosite` to just build JS and CSS files related to popup in `dist/`.



## [Changelog](https://github.com/manusauvage/Magnific-Popup/releases)

## License

Script is MIT licensed and free and will always be kept this way. But has a small restriction from the original author - please do not create public WordPress plugin based on it (or at least contact him before creating it), because he intends to make it and it'll be open source too ([want to get notified?](http://dimsemenov.com/subscribe.html)).

Created by [@dimsemenov](http://twitter.com/dimsemenov) & [contributors](https://github.com/dimsemenov/Magnific-Popup/contributors).
Forked by [@manusauvage](https://github.com/manusauvage)
