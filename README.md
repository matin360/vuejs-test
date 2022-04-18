# VueJS project

- *This doc is in the progress...*
- This documentation is inspired by [Vue Mastery](https://www.vuemastery.com/)

## Useful resources
- [VueJs Docs](https://vuejs.org/guide/introduction.html)
- For beginners [Vue 3 Intro Course](https://www.vuemastery.com/courses/intro-to-vue-3/forms-and-v-model-vue3)
- git repo of [Vue 3 Intro Course](https://github.com/Code-Pop/Intro-to-Vue-3)
- VueJs in production ( highly recommended) [Real World Vue 3 Course](https://www.vuemastery.com/courses/real-world-vue3/vue-cli-creating-the-project)
- git repo of [VueJs in production](https://github.com/Code-Pop/real-world-vue)

## Pre-installation
- Please, install both.
- PS: yarn is more flexible, but we are going to use both of them.
- To install NODEJS and NPM/Yarn:

- [Instal nodejs](https://nodejs.org/en/download/)

- [Instal yarn](https://classic.yarnpkg.com/lang/en/docs/install/#windows-stable)

## Installation

```
    npm install -g @vue/cli
```
OR
```
    yarn global add @vue/cli
```

## Project setup

Run these commands

```
    git clone https://github.com/matin360/vuejs-test.git
```
```
    yarn install
```

## Create new vuejs porject (optional)

```
    vue create project_name
```
After running the command above

- Select `Vue 3`
- Select `Use Yarn`

### Compiles and hot-reloads for development

```
    npm run serve
```
OR

```
    yarn serve
```

### Compiles and minifies for production
```
    yarn build
```

### Lints and fixes files
```
yarn lint
```

You might use this command as well, but add this to your congif file first! (`package.json -> "scripts"`)

```
yarn lint --fix
```

## Manage project

There 2 options to manage the project (import/install dependencis, create new projects, etc)

- using terminal
- using Vue UI tool (good for begginers). To do so, just run this:

```
    vue ui

```

## Project Config

- Go check `package.json` file that contains project configuration. You can modify it according to your preferneces.

- In "scripts" you can see what commands you can run ( e.g run, build, lint)

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### Tools you can/have to use in your project

You will need this a lot :D

- info about Eslint [here](https://eslint.org/docs/user-guide/getting-started)
- info about Babel [here](https://babeljs.io/)
- info about Webpack [here](https://webpack.js.org/)
- info about Rollup [here](https://rollupjs.org/guide/en/)

## Project Testing

...

