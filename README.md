<p align="center">
  <a href="https://vuetifyjs.com" target="_blank"><img width="100"src="https://vuetifyjs.com/static/doc-images/logo.svg"></a>
</p>

<p align="center">
  <a href="https://travis-ci.org/vuetifyjs/vuetify">
    <img src="https://img.shields.io/travis/vuetifyjs/vuetify.svg" alt="travis ci badge">
  </a>
  <a href="https://codeclimate.com/github/vuetifyjs/vuetify/test_coverage">
    <img src="https://img.shields.io/codeclimate/coverage/github/vuetifyjs/vuetify.svg" alt="Coverage">
  </a>
  <a href="https://codebeat.co/projects/github-com-vuetifyjs-vuetify-dev">
    <img src="https://codebeat.co/badges/b2d1ce87-848b-440e-9d7e-df9883c0cd93" alt="codebeat badge">
  </a>
  <a href="https://www.npmjs.com/package/vuetify">
    <img src="https://img.shields.io/npm/dm/vuetify.svg" alt="Downloads">
  </a>
  <a href="https://www.npmjs.com/package/vuetify">
    <img src="https://img.shields.io/npm/v/vuetify.svg" alt="Version">
  </a>
  <a href="https://cdnjs.com/libraries/vuetify">
    <img src="https://img.shields.io/cdnjs/v/vuetify.svg" alt="CDN">
  </a>
  <a href="https://www.npmjs.com/package/vuetify">
    <img src="https://img.shields.io/npm/l/vuetify.svg" alt="License">
  </a>
  <a href="https://chat.vuetifyjs.com">
    <img src="https://img.shields.io/badge/chat-on%20discord-7289da.svg" alt="Chat">
  </a>
</p>
<br><br>
<h2 align="center">Supporting Vuetify</h2>
<p>Vuetify is an open source MIT project that has been made possible due to the generous contributions by <a href="https://github.com/vuetifyjs/vuetify/blob/dev/BACKERS.md">community backers</a>. If you are interested in supporting this project, please consider:</p>

- [Becoming a Patreon backer](https://www.patreon.com/vuetify)
<br><br>
<h3 align="center">Patrons</h3>

<h4 align="center">Diamond</h4>

<p align="center">
  <a href="https://careers.lmax.com/?utm_source=vuetify&utm_medium=github-link&utm_campaign=lmax-careers">
    <img height="70px" src="https://vuetifyjs.com/static/doc-images/backers/lmax-exchange.png">
  </a>
</p>

<h4 align="center">Palladium</h4>

<p align="center">
  <a href="http://intygrate.com/?ref=vuetify-github">
    <img height="40px" src="https://vuetifyjs.com/static/doc-images/backers/intygrate.png">
  </a>
  <br><br>
  <a href="http://www.eikospartners.com/?ref=vuetify-github">
    <img height="40px" src="https://vuetifyjs.com/static/doc-images/backers/eikos-partners.webp">
  </a>
  <br><br>
  <a href="https://application.rategenius.com/?ref=vuetify-github">
    <img height="40px" src="https://vuetifyjs.com/static/doc-images/backers/rate-genius.png">
  </a>
</p>

<h2>Introduction</h2>

<p>Vuetify is a semantic component framework for Vue. It aims to provide clean, semantic and reusable components that make building your application a breeze.</p>

<p>Build <i>amazing</i> applications with the power of Vue and Material Design and a massive library of beautifully crafted components. Created according to Google's <strong><a href="https://material.io/" target="_blank">Material Design Spec</a></strong>, Vuetify components feature an easy-to-remember semantic design that shifts remembering complex classes and markup, to type-as-you speak properties that have simple and clear names.</p>

<p>Harness the power of the <a href="https://chat.vuetifyjs.com">Vuetify community</a> and get help 24/7 from talented developers across the world, the dev team and the creator, John Leider. Become a <a href="https://www.patreon.com/vuetify">patreon backer</a> and get access to special Patreon only channels.</p>
  
<p>Vuetify supports all <strong>modern browsers</strong>, including IE11 and Safari 9+. From mobile to laptop to desktop, you can rest assured that your application will work as expected. Interested in the bleeding edge? Try the vue-cli Webpack SSR (Server side rendered) template and build websites optimized for SEO.</p>

<h2>Demo and Documentation</h2>

<a href="https://vuetifyjs.com" target="_blank">Documentation</a>

<h2>One minute Quick-start</h2>

```html
<!DOCTYPE html>
<html>
<head>
  <link href='https://fonts.googleapis.com/css?family=Roboto:300,400,500,700|Material+Icons' rel="stylesheet">
  <link href="https://unpkg.com/vuetify/dist/vuetify.min.css" rel="stylesheet">
  <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no, minimal-ui">
</head>
<body>
  <div id="app">
    <v-app>
      <main>
        <v-container>Hello world</v-container>
      </main>
    </v-app>
  </div>

  <script src="https://unpkg.com/vue/dist/vue.js"></script>
  <script src="https://unpkg.com/vuetify/dist/vuetify.js"></script>
  <script>
    new Vue({
      el: '#app'
    })
  </script>
</body>
</html>
```

<h2>Project Install</h2>

``` bash
# npm
npm install vuetify
```

``` bash
# yarn
yarn add vuetify
```

## Use

```javascript
import Vue from 'vue'
import Vuetify from 'vuetify'

Vue.use(Vuetify)
```

For including styles, you can either place the below styles in your ```index.html```
```html
<link href='https://fonts.googleapis.com/css?family=Roboto:300,400,500,700|Material+Icons' rel="stylesheet">
<link href="https://unpkg.com/vuetify/dist/vuetify.min.css" rel="stylesheet">
```
Or you can import it to your webpack entry point
```javascript
require('/path/to/node_modules/vuetify/dist/vuetify.min.css')
```
Keep in mind, you will need to ensure your webpack config contains a css-loader.

<h2>Frequently asked questions and Gotchas</h2>
<a href="https://vuetifyjs.com/vuetify/frequently-asked-questions" target="_blank">Frequently asked questions</a>

<h2>Community Support</h2>
Ask your support questions on the vuetifyjs [discord](https://chat.vuetifyjs.com).

<h2>Additional Resources</h2>
Codepen starter [Vuetify Template](http://codepen.io/johnjleider/pen/bgJOrX)
