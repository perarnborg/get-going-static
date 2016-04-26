GET GOING STATIC
================

Get Going is a series of boilerplate/starting point setups for web devevelopment. This is the Vanilla flavour, wich is a setup for building a static HTML project.

Features included:

- Gulp setup
- Templates with nunjucks
- LiveReload
- local dev server with express


SETUP
-----

Setup application with

```
npm install
```

Compile assets with

```
gulp build
```
NOTE: this is done after npm install.

Build and watch assets with

```
gulp dev
```

Build, watch assets and start local server with
```
gulp
```
which is an alias of
```
gulp dev && gulp serve
```
