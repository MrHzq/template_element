<template>
    <div class="test">
        我是Element UI
        <i class="el-icon-edit"></i>
        <el-button type="success">Element UI</el-button>
    </div>
</template>

<script>
    export default {
        name: 'test',
        data() {},
        created() {
            this.$api.logout({
                password: 'qwer1234',
                userNo: '13402318457'
            });
        },
        methods: {}
    };
</script>

<style lang='scss' scoped>
    .test {
        color: red;
    }
</style>
