<template>
    <!-- 组件的结构 -->
    <div class="demo">
        <h1>{{name}}</h1>
        <button @click="show">点我提示学校名称</button>
    </div>
</template>

<script>
export default {
    name:'School',
    data() {
        return {
            name:"尚硅谷"
        }
    },
    methods: {
        show(){
            alert(this.name); 
        }
    },
}
</script>
<style scoped>
.demo{
  background-color: orange;  
}
</style>