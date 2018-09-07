<template>
    <div class="hello">
        <x-header>标题</x-header>

        <div class="test">同样不支持第三方ui库</div>
    </div>
</template>

<script>
    export default {
        name: 'HelloWorld',
        data() {
            return {
                msg: 'Welcome to Your Vue.js App'
            }
        }
    }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
    .test {
        border: 1px solid black;
        font-size: 6px;
        line-height: 100px;
        height: 100px;
        position: relative;
    }
</style>