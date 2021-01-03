<template>
    <div class='container-children1'>
        {{ testData }}
    </div>
</template>

<script>
export default {
    data() {
        return {
            testData: '这是子应用1'
        };
    }
};
</script>

<style lang="less" scoped>
.container-children1 {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 100px;
    color: blue;
    font-size: 50px;
}
</style>
