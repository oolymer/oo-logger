# oo-logger

[![Travis Build](https://img.shields.io/travis/oolymer/oo-logger/master.svg)](https://travis-ci.org/oolymer/oo-logger)
[![MIT License](https://img.shields.io/badge/license-MIT%20License-blue.svg?style=flat)](https://opensource.org/licenses/MIT)
[![Polymer 2](https://img.shields.io/badge/webcomponents-Polymer%202-orange.svg?style=flat)](https://www.polymer-project.org/2.0/start/)

> Polymer mixin for browser console logging. Supports different log levels.

**Table of Contents:**

<!-- TOC depthFrom:2 -->

- [Usage](#usage)
- [Contributing](#contributing)
- [Semantic Versions](#semantic-versions)

<!-- /TOC -->

## Usage

Add `oo-logger` as dependency to your `bower.json`.

~~~
$ bower install --save oolymer/oo-logger
~~~

Add `oo-logger.html` as HTML import to your `*.html`.

~~~html
<link rel="import" href="../oo-logger/oo-logger.html">
~~~

Use `<oo-logger>` element.

~~~html
<body>
  <oo-logger></oo-logger>
</body>
~~~

## Contributing

Install `npm` and `bower` dependencies.

~~~
$ npm install
$ npm run install:bower
~~~

Start the development server and open the default browser.

~~~
$ npm start
~~~

Run test suites in headless browsers.

~~~
$ npm test
~~~

Update the change log.

~~~
$ github_changelog_generator oolymer/oo-debug-helpers --simple-list --no-issues --usernames-as-github-logins --output CHANGES.md --future-release v0.1.0
~~~

## Semantic Versions

- Version number format `MAJOR.MINOR.PATCH`, e.g. "1.5.3".
- Increase MAJOR for breaking changes.
- Increase MINOR for new features.
- Increase PATCH for bug fixes.
