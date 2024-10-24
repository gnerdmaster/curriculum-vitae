<template>
    <div class="title">
        <img class="image" alt="Vue logo" src="@/assets/logo.png">
        <h2>{{ title.toUpperCase() }}</h2>
    </div>
    <div class="body">
        <ul>
            <li>Inglés</li>
            <li>Español</li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'LanguagesComponent',
    components: {

    },
    data() {
        return {
            title: 'IDIOMAS'
        }
    }
}
</script>

<style scoped>
.title {
    display: flex;
    align-items: center;
    margin-left: 10px;
}

.title img {
    margin-right: 10px;
}

.image {
    height: 30px;
    width: 30px;
}

.body {
    align-items: left;
    margin-left: 50px;
}
</style>