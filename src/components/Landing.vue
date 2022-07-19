<template>
    <h1>Landing</h1>
    <img :src="Landing.images.me" alt="">

</template>
<script>
export default{
    computed:{
        Landing(){
            return this.$store.state.Landing
        }
    }
}
</script>