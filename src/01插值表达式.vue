<template>
    <div class="first">
        <h1>这个文件用来说明插值表达式的使用</h1>
        <h2>作用就是用来展示数据的,这个数据变量一定要先定义好</h2>
        <p>{{msg}}</p>
        <p>我想对你说：{{msg}}</p>
        <p>{{'我想对你说：' + msg}}</p>
        <p>{{age + 1}}</p>
        <p>{{msg.toUpperCase()}}</p>
        <p>{{age>=18?"成年":"未成年"}}</p>
        <!-- <p>{{if(age>=19){console.log(123)}}}</p> -->
    </div>
</template>

<script>
export default {
  data () {
    return {
      msg: 'hello world',
      age: 20
    }
  }
}
</script>