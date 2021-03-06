# Heisenberg.js

## A project base for building modern JavaScript applications

Please note that current Heisenberg is under _very_ active development. Large changes may happen often until we hit V1.0.0.

### Features

* Not a framework, but a base project to help you structure your JavaScript code and files.
* Templating built in - Handlebars is included but feel free to change engines.
* Included: jQuery, Underscore.js and Handlebars.
* A fully commented source to show you why it's doing what it's doing and how to build upon it's foundation.
* The JavaScript version of the HTML5 Boilerplate

### Getting Started
The best place to start is on the [wiki](https://github.com/Heisenbergjs/heisenberg/wiki).

* [Download the ZIP](https://github.com/Heisenbergjs/heisenberg/archive/master.zip)
* Extract the ZIP, and get started.

### Changelog

All releases our [tagged and listed here on Github](https://github.com/Heisenbergjs/heisenberg/tags).

##### V0.9.1
- remove cruft from gitignore

##### V0.9.0
- tidied up the code
- swapped `App.Utilities.Helpers` out for just `App.Helpers`

##### V0.8.0
- went back to basics, in preparation for creating two versions of Heisenberg, Basic (this), and Pro (to come).
- removed RequireJS, Package.json, Grunt, Node modules, Bower, and so on

##### V0.7.0
- moved back to using Bower for our package management
- use Bower grunt plugin to better control which files we pull down (avoid the issue of Bower bringing down the entire repo of a package).
- move components folder into `/app` so RequireJS' optimiser can do it exactly as we want

##### V0.6.0
- added `grunt server` task which is a good way to quickly run a local preview server

##### V0.5.0
- add mediator pattern

##### V0.4.0
- use [pulldown](http://github.com/jackfranklin/pulldown) for dependencies
- add JSHint grunt task

##### V0.2.0
- updated folder structure - thanks to @phuu and others for feedback on this

##### V0.1.2
- added Grunt.js and requirejs optimiser task

##### V0.1.1
- Added a `package.json` file for Node modules (Thanks @OliverJAsh)
- Added a RequireJS build file. (Thanks @OliverJash)
- Added doctype to HTML file.

##### V0.1.0
- Initial release

### Contributors
- [Ben Howdle](http://github.com/benhowdle89)
- [Boye Oomens](http://github.com/boye)
- [Jack Franklin](http://github.com/jackfranklin)
- [Oliver J Ash](https://github.com/OliverJAsh)

### License

The MIT License (MIT)
Copyright (c) 2013 Ben Howdle

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
