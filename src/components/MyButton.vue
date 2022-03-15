<template>
    <div>
        <h2>111</h2>
        <button @click="count++">{{count}}</button>
    </div>
</template>

<script>
export default {
    name: '',
    data(){
        return {
            count:0
        }
    }
}
</script>

<style  scoped>
    h2{
        color: hotpink;
    }
</style>