# JEO Newsroom

A news-forward child theme for [JEO](http://oeco.github.io/jeo/), built for the [Earth Journalism Network](http://earthjournalism.net/).

This project is under early, active development and is not ready for use.

## Project layout

- `gulp/` _Frontend build config_
- `gulpfile.js` _Frontend build script_
- `htdocs/` _Basic WordPress environment; deploy on web server_
	- _Install WordPress files here_
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

## License

JEO Newsroom is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

JEO Newsroom is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with JEO Newsroom.  If not, see <http://www.gnu.org/licenses/>.

## Contacts and contributors

[David Ramos](http://imaginaryterrain.com/)


