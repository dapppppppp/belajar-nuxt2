<template>
    <h1>Profil {{ $route.params.id }}</h1>
</template>

<script>
    export default{
        validate({ params }) {
            // Validate that the id is a number
            return /^\d+$/.test(params.id);
        }
        
    }
</script>