# vue-workshop

## vue-workshop

Requirements:
- editor, i.e. [Visual studio code](https://code.visualstudio.com/) with "Vetur" plugin
- [NodeJs](https://code.visualstudio.com/) (https://nodejs.org/en/download/)
- [Vue CLI] (https://cli.vuejs.org)

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

## Session 1 steps

- Setup project:
  - vue create vue-workshop
  - npm install
  - npm run serve
  - open app in browser
- HelloWorld.vue: remove content and change link to ipscape website
- App.vue: change msg to "Welcome to vue workshop"
- Add input and button
- Add data "greetingName" and v-model to input
- Add method greet, with alert greetingName
- Add image
- Add computed value "showSecretImage" which returns true greetingName is secret
- Change CSS styles