# JEO Newsroom

A news-forward child theme version of JEO, built for the [Earth Journalism Network](http://earthjournalism.net/).

[David Ramos](http://imaginaryterrain.com/)

## Development tooling

Build tools are based on [gulp-starter[(https://github.com/greypants/gulp-starter).

## Project layout

- gulp _build config_- gulpfile.js _build script_- htdocs _install on webserver_- node_modules _gulp build support, not under version control_- package.json _node.js packages for gulp_- README.md- src _static, frontend development_

## Notes

The gulp tools depend on node-sass, which doesn’t support:
- Compass
- Suffix selectors, i.e. for BEM notation


