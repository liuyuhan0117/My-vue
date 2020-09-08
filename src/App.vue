<!--
 * @Descripttion: 
 * @version: 1.0
 * @Author: 刘宇涵
 * @Date: 2020-09-08 16:43:14
 * @LastEditors: 刘宇涵
 * @LastEditTime: 2020-09-08 17:29:43
-->
<template>
  <div id="app">
   这是我修改后得vue项目
   <Index :a="msg"/>
  </div>
</template>

<script>
  import Index from './components/Index'
export default {
  name: 'App',
  data(){
    return {
       msg:"这是我要传给子组件得字符串"
    }
     
  },
  components: {
    Index
  }
}
</script>

<style>

</style>
