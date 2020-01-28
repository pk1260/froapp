<template>
    <div v-bind:key="gunpla.id" v-for="gunpla in gunplas">
        <h3>{{gunpla.title}}</h3>
    </div>
</template>

<script>
    export default {
        name: "Gunplas",
        props: ["gunplas"]
    }
</script>

<style scoped>

</style>