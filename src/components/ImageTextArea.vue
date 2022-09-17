<template>
    <div>
      <ul>
        <li v-for="item in items" :key="item">{{ item }}</li>
      </ul>
    </div>
</template>
<script>
import { createApp} from 'vue'
import App from './App.vue'
import imageTextArea from './imageTextArea.vue'

const app = Vue.createApp({})
// const app = createApp(App)
// app.components('image-text-area', imageTextArea)
// app.mount('#app')
app.components('a',{
  data() {
    return {
      items: ["a","b"]
    }
  }
})
</script>