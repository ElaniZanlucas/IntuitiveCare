<template>
  <div id="global">
    <Header/>
    <Body/>
  </div>
</template>

<script>
import Header from "../components/header.vue"
import Body from "../components/body.vue"
  export default {
    components: {Header, Body} 
  }
</script>

<style>
#global {
  height: 100%;
  width: auto;
  /* background-color: #e0e0e0; -> body .body*/ 
}
</style>