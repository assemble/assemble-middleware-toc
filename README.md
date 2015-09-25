# grunt-assemble-toc [![NPM version](https://badge.fury.io/js/grunt-assemble-toc.svg)](http://badge.fury.io/js/grunt-assemble-toc)

> Assemble middleware for adding a Table of Contents (TOC) to any HTML page.

## Quickstart

In the command line, run:

```sh
npm install grunt-assemble-toc --save-dev
```

Next, to register the plugin with Assemble in your project's Gruntfile you can either specify the direct path to the plugin(s) (e.g. `./path/to/plugins/*.js`), or if installed via npm, make sure the plugin is in the `devDependencies` of your project.js package.json, and simply add the module's name to the `plugins` option:

```js
assemble: {
  options: {
    plugins: ['grunt-assemble-toc', 'other/plugins/*.js']
  }
}
```

Visit the [plugins docs](http://assemble.io/plugins/) for more info or for help getting started.

## Options

## toc

Type: `String`
Default: `'toc'`

Tag to determine where the table of contents is located

## modifier

Type: `String`
Default: `''`

CSS class used in the wrapper `ul` for the table of contents.

## Usage Examples

```js
assemble: {
  options: {
    plugins: ['grunt-assemble-toc'],
    toc: {
      id: 'toc',
      modifier: ''
    }
  }
}
```

## Assemble plugins

* [grunt-assemble](https://www.npmjs.com/package/grunt-assemble): Static site generator for Grunt.js, Yeoman and Node.js. Used by Zurb Foundation, Zurb Ink, H5BP/Effeckt,… [more](https://www.npmjs.com/package/grunt-assemble) | [homepage](http://assemble.io)
* [grunt-assemble-anchors](https://www.npmjs.com/package/grunt-assemble-anchors): Assemble plugin for creating anchor tags from headings in generated html using Cheerio.js. | [homepage](https://github.com/assemble/grunt-assemble-anchors)
* [grunt-assemble-contextual](https://www.npmjs.com/package/grunt-assemble-contextual): Generates a JSON file with the context of each page. Basic plugin to help see… [more](https://www.npmjs.com/package/grunt-assemble-contextual) | [homepage](https://github.com/assemble/grunt-assemble-contextual)
* [grunt-assemble-decompress](https://www.npmjs.com/package/grunt-assemble-decompress): Assemble plugin for extracting zip, tar and tar.gz archives. | [homepage](https://github.com/assemble/grunt-assemble-decompress)
* [grunt-assemble-download](https://www.npmjs.com/package/grunt-assemble-download): Assemble plugin for downloading files from GitHub. | [homepage](https://github.com/assemble/grunt-assemble-download)
* [grunt-assemble-lunr](https://www.npmjs.com/package/grunt-assemble-lunr): Assemble plugin for adding search capabilities to your static site, with lunr.js. | [homepage](http://assemble.io)
* [grunt-assemble-permalinks](https://www.npmjs.com/package/grunt-assemble-permalinks): Permalinks plugin for Assemble, the static site generator for Grunt.js, Yeoman and Node.js. This plugin… [more](https://www.npmjs.com/package/grunt-assemble-permalinks) | [homepage](https://github.com/assemble/grunt-assemble-permalinks)

## Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](https://github.com/assemble/grunt-assemble-toc/issues/new).

## Author

**Brian Woodward**

+ [github/assemble](https://github.com/assemble)
+ [twitter/assemble](http://twitter.com/assemble)

## License

Copyright © 2015 Brian Woodward
Released under the MIT license.

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on September 24, 2015._