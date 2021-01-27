<template>
    <h1>Hello, {{ this.id }}</h1>
</template>

<script>
export default {
    async asyncData({ params }){
        const id = params.id
        return { id }
    }
}
</script>