<template>
    <div>
        <main v-if="$route.params.slug">
            <h1 v-text="'Blog Post ' + $route.params.slug"></h1>
        </main>
        <main v-else>
            <h1>List Blog</h1>
        </main>
    </div>
</template>