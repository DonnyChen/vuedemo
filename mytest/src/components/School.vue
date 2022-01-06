<template>
    <div class="demo">
        <h2>学校名称：{{schoolName}}</h2>
        <h2>学校地址：{{address}}</h2>
        <button @click="showMe"> 提示学校名称</button>
    </div>
</template>

<script>
export default {
    name:'School',
    data(){
        return {
            schoolName:'WUHNADAX',
            address:'ShangHai'
        }
    },
    methods: {
        showMe(){
            alert(this.schoolName)
        }
    },
}
</script>

<style>
    .demo {
        background-color: bisque;
    }
</style>