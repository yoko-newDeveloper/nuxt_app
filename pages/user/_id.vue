<template>
    <div>{{ message }}</div>
</template>

<script>
export default {
    computed: {
        message: function() {
            let user_id = this.$route.params.id
            return "ユーザID["+ user_id +"]のページです"
        }
    }
}
</script>

<style>
</style>
