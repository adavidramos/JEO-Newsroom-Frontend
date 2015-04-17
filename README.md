# JEO Newsroom

A news-forward child theme of JEO, built for the [Earth Journalism Network](http://earthjournalism.net/).

[David Ramos](http://imaginaryterrain.com/)

## Project layout

- `gulp/` _Frontend build config_
- `gulpfile.js` _Frontend build script_
- `htdocs/` _Basic WordPress installation; deploy on web server_
	- `static/` _Static files (CSS, JavaScript, images, and fonts), output from 	Gulp_
	- `wp-content/`
		- `themes/`
			- `jeo-newsroom/` _WordPress theme files_
- `node_modules/` _Gulp build support, not under version control_
- `package.json` _Node.js packages for gulp_
- `README.md`
- `src/` _HTML, SASS, JavaScript, and images (processed through Gulp)_

Compiled CSS and JavaScript files are at `htdocs/static/`, *not* in the WordPress theme folder.

## Frontend development tooling

This project uses Gulp for frontend development automation. Build scripts are based on [gulp-starter](https://github.com/greypants/gulp-starter).

Theme styles are written in SASS, compiled to CSS, and minified for production. Similarly, JavaScript files are concatenated and minified.

The Gulp tools use node-sass, which doesn’t support:
- Compass
- Suffix selectors, i.e. for BEM notation


