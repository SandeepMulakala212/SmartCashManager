### Introduction

Vuetify is a Material Design Component Framework for the Vue framework. We believe that you shouldn't need design skills to build beautiful Vue applications. Vuetify takes the pain out of development by providing everything you need:

- Over 80 beautiful hand crafted Material Components
- Powerful and unique directives for customizing user experiences
- WCAG accessibility (a11y) and Section 508 compliant
- Full RTL support
- Support for IE11 / Safari 9 with [polyfill](https://vuetifyjs.com/getting-started/browser-support)
- Easily customizable with SASS variables and [vue-cli-plugin-vuetify](https://github.com/vuetifyjs/vue-cli-plugins/tree/master/packages/vue-cli-plugin-vuetify)
- Built with the [Material Design 2 Specification](https://material.io/guidelines/)
- Designed for mobile to desktop

Vuetify is expansive, powerful and provides tools required for large, robust applications.

###### Browser Support

Vuetify supports all **modern browsers**, including IE11 and Safari 9+ (using [polyfills](https://vuetifyjs.com/getting-started/quick-start#ie-11-amp-safari-9-support)). Components are designed for a minimum width of _320px_.

### Vuetify Ecosystem

<table>
  <thead>
    <tr>
      <th>Project</th>
      <th>Version</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <a href="https://github.com/vuetifyjs/vue-cli-plugins/tree/master/packages/cli-plugin-utils">@vuetify/cli-plugin-utils</a>
      </td>
      <td>
        <a href="https://www.npmjs.com/package/@vuetify/cli-plugin-utils">
          <img src="https://img.shields.io/npm/v/@vuetify/cli-plugin-utils.svg" alt="Version">
        </a>
      </td>
      <td>
        A collection of helper utilities for creating Vue CLI plugins
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/vuetifyjs/eslint-config-vuetify">eslint-config-vuetify</a>
      </td>
      <td>
        <a href="https://www.npmjs.com/package/eslint-config-vuetify">
          <img src="https://img.shields.io/npm/v/eslint-config-vuetify.svg" alt="Version">
        </a>
      </td>
      <td>
       An opinionated eslint-config for Vuetify
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/vuetifyjs/eslint-plugin-vuetify">eslint-plugin-vuetify</a>
      </td>
      <td>
        <a href="https://www.npmjs.com/package/eslint-plugin-vuetify">
          <img src="https://img.shields.io/npm/v/eslint-plugin-vuetify.svg" alt="Version">
        </a>
      </td>
      <td>
       An opinionated eslint-plugin for Vuetify
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/vuetifyjs/vue-cli-plugins/tree/master/packages/vue-cli-plugin-vuetify">vue-cli-plugin-vuetify</a>
      </td>
      <td>
        <a href="https://www.npmjs.com/package/vue-cli-plugin-vuetify">
          <img src="https://img.shields.io/npm/v/vue-cli-plugin-vuetify.svg" alt="Version">
        </a>
      </td>
      <td>
        A Vue CLI plugin for installing and configuring Vuetify
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/vuetifyjs/vue-cli-plugins/tree/master/packages/vue-cli-plugin-vuetify-cli">vue-cli-plugin-vuetify-cli</a>
      </td>
      <td>
        <a href="https://www.npmjs.com/package/vue-cli-plugin-vuetify-cli">
          <img src="https://img.shields.io/npm/v/vue-cli-plugin-vuetify-cli.svg" alt="Version">
        </a>
      </td>
      <td>
        A Vue CLI plugin for scaffolding Vue applications
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/vuetifyjs/vue-cli-plugins/tree/master/packages/vue-cli-plugin-vuetify-essentials">vue-cli-plugin-vuetify-essentials</a>
      </td>
      <td>
        <a href="https://www.npmjs.com/package/vue-cli-plugin-vuetify-essentials">
          <img src="https://img.shields.io/npm/v/vue-cli-plugin-vuetify-essentials.svg" alt="Version">
        </a>
      </td>
      <td>
        A supplementary Vue CLI plugin used by <a href="https:/github.com/vuetifyjs.com/vue-cli-preset-vuetify">vue-cli-preset-vuetify</a>
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/vuetifyjs/vue-cli-plugin-vuetify/tree/master/packages/vue-cli-plugin-vuetify-preset-basil">vue-cli-plugin-vuetify-preset-basil</a>
      </td>
      <td>
        <a href="https://www.npmjs.com/package/vue-cli-plugin-vuetify-preset-basil">
          <img src="https://img.shields.io/npm/v/vue-cli-plugin-vuetify-preset-basil.svg" alt="Version">
        </a>
      </td>
      <td>
        A Vuetify Preset for the <a href="https://material.io/design/material-studies/basil.html">Basil Material Study</a>
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/vuetifyjs/vue-cli-plugin-vuetify/tree/master/packages/vue-cli-plugin-vuetify-preset-crane">vue-cli-plugin-vuetify-preset-crane</a>
      </td>
      <td>
        <a href="https://www.npmjs.com/package/vue-cli-plugin-vuetify-preset-crane">
          <img src="https://img.shields.io/npm/v/vue-cli-plugin-vuetify-preset-crane.svg" alt="Version">
        </a>
      </td>
      <td>
        A Vuetify Preset for the <a href="https://material.io/design/material-studies/crane.html">Crane Material Study</a>
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/vuetifyjs/vue-cli-plugin-vuetify/tree/master/packages/vue-cli-plugin-vuetify-preset-fortnightly">vue-cli-plugin-vuetify-preset-fortnightly</a>
      </td>
      <td>
        <a href="https://www.npmjs.com/package/vue-cli-plugin-vuetify-preset-fortnightly">
          <img src="https://img.shields.io/npm/v/vue-cli-plugin-vuetify-preset-fortnightly.svg" alt="Version">
        </a>
      </td>
      <td>
        A Vuetify Preset for the <a href="https://material.io/design/material-studies/fortnightly.html">Fortnightly Material Study</a>
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/vuetifyjs/vue-cli-plugin-vuetify/tree/master/packages/vue-cli-plugin-vuetify-preset-owl">vue-cli-plugin-vuetify-preset-owl</a>
      </td>
      <td>
        <a href="https://www.npmjs.com/package/vue-cli-plugin-vuetify-preset-owl">
          <img src="https://img.shields.io/npm/v/vue-cli-plugin-vuetify-preset-owl.svg" alt="Version">
        </a>
      </td>
      <td>
        A Vuetify Preset for the <a href="https://material.io/design/material-studies/owl.html">Owl Material Study</a>
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/vuetifyjs/vue-cli-plugin-vuetify/tree/master/packages/vue-cli-plugin-vuetify-preset-rally">vue-cli-plugin-vuetify-preset-rally</a>
      </td>
      <td>
        <a href="https://www.npmjs.com/package/vue-cli-plugin-vuetify-preset-rally">
          <img src="https://img.shields.io/npm/v/vue-cli-plugin-vuetify-preset-rally.svg" alt="Version">
        </a>
      </td>
      <td>
        A Vuetify Preset for the <a href="https://material.io/design/material-studies/rally.html">Rally Material Study</a>
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/vuetifyjs/vue-cli-plugin-vuetify/tree/master/packages/vue-cli-plugin-vuetify-preset-reply">vue-cli-plugin-vuetify-preset-reply</a>
      </td>
      <td>
        <a href="https://www.npmjs.com/package/vue-cli-plugin-vuetify-preset-reply">
          <img src="https://img.shields.io/npm/v/vue-cli-plugin-vuetify-preset-reply.svg" alt="Version">
        </a>
      </td>
      <td>
        A Vuetify Preset for the <a href="https://material.io/design/material-studies/reply.html">Reply Material Study</a>
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/vuetifyjs/vue-cli-plugin-vuetify/tree/master/packages/vue-cli-plugin-vuetify-preset-shrine">vue-cli-plugin-vuetify-preset-shrine</a>
      </td>
      <td>
        <a href="https://www.npmjs.com/package/vue-cli-plugin-vuetify-preset-shrine">
          <img src="https://img.shields.io/npm/v/vue-cli-plugin-vuetify-preset-shrine.svg" alt="Version">
        </a>
      </td>
      <td>
        A Vuetify Preset for the <a href="https://material.io/design/material-studies/shrine.html">Shrine Material Study</a>
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/vuetifyjs/vue-cli-plugins/tree/master/packages/vue-cli-plugin-vuetify-storybook">vue-cli-plugin-vuetify-storybook</a>
      </td>
      <td>
        <a href="https://www.npmjs.com/package/vue-cli-plugin-vuetify-storybook">
          <img src="https://img.shields.io/npm/v/vue-cli-plugin-vuetify-storybook.svg" alt="Version">
        </a>
      </td>
      <td>
        A Vue CLI plugin for using Storybook w/ Vuetify
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/vuetifyjs/vue-cli-preset-vuetify">vue-cli-preset-vuetify</a>
      </td>
      <td>
        n/a
      </td>
      <td>
       A Vue CLI preset for Vuetify
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/vuetifyjs/vuetify-loader">vuetify-loader</a>
      </td>
      <td>
        <a href="https://www.npmjs.com/package/vuetify-loader">
          <img src="https://img.shields.io/npm/v/vuetify-loader.svg" alt="Version">
        </a>
      </td>
      <td>
       A webpack plugin for treeshaking and progressive image support
      </td>
    </tr>
    <tr>
      <td>
        <a href="https://github.com/vuetifyjs/vuex/tree/master/packages/cognito-module/">vuex-cognito-module</a>
      </td>
      <td>
        <a href="https://www.npmjs.com/package/@vuetify/vuex-cognito-module">
          <img src="https://img.shields.io/npm/v/@vuetify/vuex-cognito-module.svg" alt="Version">
        </a>
      </td>
      <td>
       A <a href="https://vuex.vuejs.org/">Vuex</a> module for <a href="https://aws.amazon.com/cognito/">AWS Cognito</a>
      </td>
    </tr>
  </tbody>
</table>

### Documentation

To check out the [component api explorer](https://vuetifyjs.com/components/api-explorer) and docs, visit [vuetifyjs.com](https://vuetifyjs.com).

## Getting Started
- Install Nodejs from [Nodejs Official Page](https://nodejs.org/en/)
- Open your terminal
- Clone project from Git and Navigate to the project
- Run `npm install` or `yarn install` if you use [Yarn](https://yarnpkg.com/en/)
- Run `npm run dev` or `yarn serve` to start a local development server
- A new tab will be opened in your browser

You can also run additional npm tasks such as
- `npm run build` to build your app for production
- `npm run lint` to run linting.
