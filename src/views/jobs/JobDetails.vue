<template>
    <div>
        <h1>Job Details Page</h1>
        <p>the job id is: {{ id }}</p>
        <!-- <p>the job details are: {{ details }}</p> -->
    </div>
</template>

<script>
export default {
    props: [
        'id',   
    ]
}
</script>

<style>

</style>