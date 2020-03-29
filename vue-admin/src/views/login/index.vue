<template>
    <div id="login">
        外层必须有一层来包裹  不一定是div   别的也可以
    </div>
</template>
<script></script>
<style lang="scss" scoped>  //如果不加scoped  则下面的饿样式会对全局有效  加了scoped则下面的饿样式只对该页面有效
    #login {
        height: 100vh;   //100vh:表示占可视区的100%； 50vh表示占可视区的一半
        background-color: #cccccc;
    }
</style>