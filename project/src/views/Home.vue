<template>
  <div class="home">
      <h1>这个是首页内容。</h1>
  </div>
</template>

<script lang="ts">
// import { Options, Vue } from 'vue-class-component';
// @Options({
//   components: {
    
//   },
// })
// export default class Home extends Vue {
//     // setup(props) {
      
//     // }
// }
import { defineComponent } from 'vue';

export default defineComponent({
    setup(props){
      console.log(props);
    }
})
</script>
