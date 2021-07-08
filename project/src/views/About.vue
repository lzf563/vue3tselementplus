<template>
  <div class="about">
    <h1>This is an about page</h1>
    <h2>{{ flag }}</h2>
    <h3>{{ a }}</h3>
    <h3>{{  arr }}</h3>

    <el-button @click="toHome">点击按钮</el-button>
  </div>
</template>
<script lang='ts'>
    import { Options, Vue, } from 'vue-class-component';
    @Options({
      components: {},
      data(){
        return{
          flag:'这个是about的组件内容。'
        }
      },
      methods:{
        toHome(){
          this.$router.push("/")
        }
      }
    })
    export default class Home extends Vue {
        const a = "这个是个字符串内容。";
        const arr = [1,2,3,4,5,6,7]
    }
</script>
<style lang="sass">
  
</style>
