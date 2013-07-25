# Backbone.Paginator (0.9.0-dev) browserify wrapper

This is a simple wrapper to enable using [Backbone.Paginator](http://addyosmani.github.com/backbone.paginator)
 with [browserify](https://github.com/substack/node-browserify).

## Usage

Backbone.Paginator does not return anything, it only attaches itself to the Backbone
instance.

    var Backbone = require('backbone');

    require('backbone.paginator-browserify');