<snippet>
  <content>
  
##  [vue2-3-button-up-down](https://github.com/AlexeyZelenko/vue3_typescript/tree/master/src/vue-button-up) with Vue3 and Vue2.

<p align="center">
    <a href="https://www.npmjs.com/package/vue-button-up">
      <img alt="codebeat badge" src="https://img.shields.io/badge/version-1.0.3%20-44cc11.svg" />
    </a>
    <a href="https://www.npmjs.com/package/tiptap-vuetify">
      <img alt="codebeat badge" src="https://img.shields.io/badge/license-ISC%20-44cc11.svg" />
    </a>
    <a href="https://standardjs.com/">
      <img alt="codebeat badge" src="https://badgen.net/badge/code%20style/standard/f2a" />
    </a>
    <a href="https://www.npmjs.com/package/tiptap-vuetify">
      <img alt="codebeat badge" src="https://img.shields.io/badge/size-15%20kB-44cc11.svg" />
    </a>
  </p>
  
  Button with the functionality of scrolling the page up for Vue.
  [DEMO on codesanbox](https://codesandbox.io/s/vuejs3-up-down-button-s7j80?file=/src/App.vue)
  
  ## Navigation  
  <!-- TOC -->
  
  - [Features](#features)
  - [Installation](#installation)
  - [Usage](#Usage)
  <!-- /TOC -->
  
  ## Features
  
  - used vue2, vue3
  - easy to install
  - Easy application
  - Using slot
  - Use with icons, images, by default
  - Possibility to work on the button design
 
  
  ## Installation
  
    ```
     npm install --save vuejs3-up-down-button
    ```

## Usage
 #default
```
<Vue3DownUpButton >
    <template #top>
      &uarr;
    </template>
    <template #down>
      &darr;
    </template>
  </Vue3DownUpButton>

<script>
    import Vue3DownUpButton from 'vuejs3-up-down-button'
    
export default {
  components: {
    Vue3DownUpButton
  }
}
</script>
``` 
 #images
```
<Vue3DownUpButton >
    <template #top>
        <img
            :src="require(`@/assets/img/buttonUp.png`)"
        >
    </template>
    <template #down>
        <img
            :src="require(`@/assets/img/buttonDown.png`)"
         >
    </template>
  </Vue3DownUpButton>

<script>
    import Vue3DownUpButton from 'vuejs3-up-down-button'
    
export default {
  components: {
    Vue3DownUpButton
  }
}
</script>
```
#up
```
<Vue3DownUpButton >
    <template #top>
        <img
            :src="require(`@/assets/img/buttonUp.png`)"
        >
    </template>
  </Vue3DownUpButton>

<script>
    import Vue3DownUpButton from 'vuejs3-up-down-button'
    
export default {
  components: {
    Vue3DownUpButton
  }
}
</script>
```

></content>
><tabTrigger>readme</tabTrigger>
</snippet>