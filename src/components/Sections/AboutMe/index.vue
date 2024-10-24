<template>
    <div class="title">
        <img class="image" alt="Vue logo" src="@/assets/logo.png">
        <h2>{{ title.toUpperCase() }}</h2>
    </div>
    <div class="body">
        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's
        standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make
        a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting,
        remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing
        Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions
        of Lorem Ipsum.
    </div>
</template>

<script>
export default {
    name: 'AboutMeComponent',
    components: {

    },
    data() {
        return {
            title: 'ACERCA DE MÍ'
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