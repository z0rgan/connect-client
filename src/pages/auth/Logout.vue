<template>
    
</template>

<script>
    export default {
        name: "Logout",
        created() {
            localStorage.removeItem('token');
            this.$router.push('/');
        }
    }
</script>
<style scoped>

</style>