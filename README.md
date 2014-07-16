# Eliteprospects Tooltips [![Dependency Status](https://gemnasium.com/menmo/eliteprospects-tooltips.svg)](https://gemnasium.com/menmo/eliteprospects-tooltips)

Show detailed information about hockey players directly on your site.

## Usage

Place a script tag at the end of your page, right before the closing BODY-tag.
The script automatically finds all links to player profiles on Eliteprospects.com and improves them with an informative tooltip.

See demo here: [http://menmo.github.io/eliteprospects-tooltips](http://menmo.github.io/eliteprospects-tooltips)

*Use your own hosted version of the script in production environments!*

The data is fetched from the [Eliteprospects API](https://github.com/menmo/eliteprospects-api-documentation).

This can be used in conjunction with our [Wordpress plugin](https://github.com/menmo/eliteprospects-wordpress-player-link) that generate links.

### Options

The tooltips can be customized with the following options.

TODO: options.

## Develop

### Requirements (install globally)

* node
* bower
* gulp

### Install

    npm install
    bower install

### Build release version

    gulp bundle

### Deploy

Bump version, type can be `major`, `minor` or default `patch`

    gulp bump --type=minor

Deploy to `gh-pages`

    gulp deploy

Tag version before pushing to Git

    gulp tag
