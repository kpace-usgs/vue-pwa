# pwa-project

> A Vue.js project

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run all tests
npm test
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

What's Included

Service Worker precaching of application shell + static assets (prod)
Script (async chunk) preloading using <link rel="preload">
Web Application Manifest + favicons
Mobile-friendly meta-viewport
Lighthouse score of 90+/100
npm run dev: first-in-class development experience.

Webpack + vue-loader for single file Vue components.
State preserving hot-reload
State preserving compilation error overlay
Lint-on-save with ESLint
Source maps
npm run build: Production ready build.

JavaScript minified with UglifyJS.
HTML minified with html-minifier.
CSS across all components extracted into a single file and minified with cssnano.
All static assets compiled with version hashes for efficient long-term caching, and a production index.html is auto-generated with proper URLs to these generated assets.
Use npm run build --reportto build with bundle size analytics.
Generates a Service Worker for offline caching your static assets using sw-precache-webpack-plugin
npm run unit: Unit tests run in PhantomJS with Karma + Mocha + karma-webpack.

Supports ES2015+ in test files.
Supports all webpack loaders.
Easy mock injection.