# vue-cli

> A Vue.js project to practice communicating between components
* Props - pass data from parent to child. When a value is passed to a prop attribute, it becomes a property on that component instance.
* $emit - pass data from child to parent 
* eventBus - pass data from sibling to sibling. eventBus.$emit() for sibling that is sending and created() { eventBus.$on() } for receiver sibling. 


## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

For detailed explanation on how things work, consult the [docs for vue-loader](http://vuejs.github.io/vue-loader).
"# VueComponentCommunication" 
