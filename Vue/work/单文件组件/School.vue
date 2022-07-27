<template>
  <div class="demo">
        <div>
            <h2>学生名称:{{name}}</h2>
            <h2>学生地址:{{address}}</h2>
            <button @click="showName">点我提示学生名</button>
        </div>
    </div>
</template>

<script>
export default {
    	name:'School',
        data(){
             return{
                name:'相信音乐',
                address:'北京',
            }
        },
        methods: {
            showName(){
                alert(this.name)
            }
        },
}
</script>

<style>
     .demo{
        background-color: rgb(69, 165, 230);
    }
</style>