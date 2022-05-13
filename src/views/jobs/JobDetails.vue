<template>
    <div>
        <h1>job deatils Page</h1>
        <p>the job id is: {{ id }}</p>
    </div>
</template>

<script>
export default {
    data() {
        return{
            id: this.$route.params.id 
        }
    }
}
</script>

<style>

</style>