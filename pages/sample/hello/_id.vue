<template>
    <h1>{{ this.greeting }}, {{ this.id }} {{ this.ps }}</h1>
</template>

<script>
export default {
    async asyncData({ params }){
        const greeting = "Hello"
        const id = params.id
        let message = ""
        if(id==="legoyoshi"){
            message = "I LOVE YOU"
        }
        return { 
            greeting: greeting,
            id,
            ps: message
         }
    }
}
</script>