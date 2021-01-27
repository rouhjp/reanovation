<template>
    <div class="container">
        <div>
            <Logo />
            <h1 class="title">{{ this.id }}</h1>
        </div>
    </div>
</template>
 
<script>
export default {
    async asyncData({ params }) {
      const id = params.id
      return { id }
    }
}
</script>