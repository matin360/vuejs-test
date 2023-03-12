# VueJS project

- It is mostly about project management using package managers like `yarn` or `npm` which can be applied even to projects with another tech stack ( e.g React)
- Inspired by [Vue Mastery](https://www.vuemastery.com/)

## Useful resources
- [VueJs Docs](https://vuejs.org/guide/introduction.html)
- For beginners [Vue 3 Intro Course](https://www.vuemastery.com/courses/intro-to-vue-3/forms-and-v-model-vue3)
- git repo of [Vue 3 Intro Course](https://github.com/Code-Pop/Intro-to-Vue-3)
- VueJs in production ( highly recommended, but only 2 first lessons are avavailable for free, which is enough to know the project's structure) [Real World Vue 3 Course](https://www.vuemastery.com/courses/real-world-vue3/vue-cli-creating-the-project)
- git repo of [VueJs in production](https://github.com/Code-Pop/real-world-vue)
- Vue Router [here](https://vueschool.io/articles/vuejs-tutorials/how-to-use-vue-router-a-complete-tutorial/)
- [VueJs project deployment in heroku](https://betterprogramming.pub/deploying-a-vue-js-app-to-heroku-d16f95c07a04)

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

## Create new vuejs project

```
    vue create *project_name*
```
After running the command above

- Select `Vue 3`
- Select either `Use Yarn` (recommended) or `Use NPM`

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

You might use this command as well, but add this to your config file first! (`package.json -> "scripts"`)

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

- Go check `package.json` file that contains project configuration. You can modify it according to your preferences.

- In "scripts" you can see what commands you can run ( e.g run, build, lint)

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### Tools you can/have to use in your project

You will need this a lot :D

- info about Eslint [here](https://eslint.org/docs/user-guide/getting-started)
- info about Babel [here](https://babeljs.io/)
- info about Webpack [here](https://webpack.js.org/)
- info about Rollup [here](https://rollupjs.org/guide/en/)

## Install extensions if you use VScode

- *Vetur* - to work with `vue` files

- *es6-string-html* - to use use *HTML* in `js` files

## Resolve dependency issues

Sometimes you might have issues with dependencies which are located in `node_modules`. Terminal usually specifies which dependency is a problem ( e.g old version, absence, etc )

- In case your project does not have a particular dependency, just add it to your config file `package.json` running this command:
```
    yarn add *depency_name*
```
then:
```
    yarn install
```

- In case you are required to update dependencies, visit this [link](https://classic.yarnpkg.com/lang/en/docs/cli/upgrade/)
## Project Debugging

For debugging you can install dev tools on your browser.
- For `Vue 3` you should install *Vue.js devtools* `beta` version
- For `Vue 2` you can install *Vue.js devtools* `legacy` version
