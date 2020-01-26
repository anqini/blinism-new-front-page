<template>
  <div id="nav">
    <img alt="logo" src="../assets/logo.png" style="float: left;" height=60>
    <ul style="float: right;">
        <li>留学咨询</li>
        <li>在线工具箱</li>
        <li>背景提升</li>
        <li>选择比邻</li>
        <li class="active">首页</li>
    </ul>
  </div>
</template>

<script>
export default {
  props: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#nav {
    height: 80px;
    position: fixed;
    width: 94%;
    /* margin: 0 5%; */
    left: 50%;
    margin-left: -47%;
    padding: 10px 2%;
    -webkit-box-shadow: 4px 4px 11px -4px #96B9C2;
    box-shadow: 4px 4px 11px -4px #96B9C2;
    box-sizing: border-box;
    background-color: white;
    z-index: 1000;
        border-radius: 0 0 5px 5px;
}
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  padding-top: 20px;
}
li {
    float:right; 
    margin-right: 30px;
}
li.active {
    color: #13B7CA;
}
</style>
