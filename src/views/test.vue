<template>
    <div class="test">
        <div>template_element</div>
        <div>我是Element UI</div>
        <i class="el-icon-edit"></i>
        <el-button type="success">Element UI</el-button>
    </div>
</template>

<script>
    export default {
        name: 'test',
        data() {},
        created() {
            this.$api
                .login({
                    phone: '13402318457',
                    code: '123458'
                })
                .then(res => console.log(res))
        },
        methods: {}
    }
</script>

<style lang="scss" scoped>
    .test {
        color: red;
    }
</style>
