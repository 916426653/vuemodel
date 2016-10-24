<template>
  <div id="app">
    <h1>姓名：{{name}}</h1>
    <h2>{{age}}</h2>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      'name': 'wqq',
      'age': '21'
    }
  }
}
</script>

<style >
  /*一定要加lang不然无法编译*/
  /*测试一下对sass的编译*/



  h1{
    background-color: #eee;
    color: red;
    transform: translate(10%, 10%);/*测试自动添加前缀*/
  }
  h1:hover{
    height:100px;
  }
  h2{
    background-color: #999;
  }

</style>




