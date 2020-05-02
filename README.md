# real-world-vue

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

The node_modules directory is where all of the libraries we need to build Vue are stored.

In the public directory, you place any static assets you don’t want to be run through Webpack when we build our project.

You’ll want to put the majority of your assets, such as images and fonts, in the assets directory so they can be optimized by Webpack.

The components directory is where we store the components, or building blocks, of our Vue app.

The views directory is where we store files for the different views, or pages, of our app.

The App.vue file is the root component that all other components are nested within.

The main.js file is what renders our App.vue component (and everything nested within it) and mounts it to the DOM.

Below that we have a router.js file, which we’ll cover more in the lesson on Vue Router, and the store.js file is for Vuex, which we’ll also cover in future lessons.

Finally, we have a .gitignore file where we can specify what we want git to ignore, along with a babel.config.js file and our package.json, which helps npm identify the project and handle its dependencies.
