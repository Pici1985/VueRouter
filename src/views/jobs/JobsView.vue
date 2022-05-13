<template>
    <div>
        <h1>Jobs</h1>
        <div v-for="job in jobs" :key='job.id'>
            <h2>{{ job.title }}</h2>
            <!-- <p>{{ job.details }}</p> -->
        </div>
    </div>
</template>

<script>
export default {
    data(){
        return{
            jobs: [
                { title: 'UX designer', id: 1, details: 'lorem'},
                { title: 'Web Dev', id: 2, details: 'lorem'},
                { title: 'Vue Dev', id: 3, details: 'lorem'},
            ],    
        }
    }
}
</script>

<style>

</style>