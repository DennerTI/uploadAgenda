<template>
    <div>
        <h3>quantas cervejas o carlos vai beber sabado?</h3>
        <input type="text" v-model="quantidade">
        <h2>O carlos vai beber {{ quantidade }}</h2>
    </div>
</template>

<script>
export default {
    data() {
        return {
            quantidade: ''
        }
    },
}
</script>

<style lang="less" scoped>

</style>