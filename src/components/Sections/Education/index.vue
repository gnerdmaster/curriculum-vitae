<template>
    <div class="title">
        <img class="image" alt="Vue logo" src="@/assets/logo.png">
        <h2>{{ title.toUpperCase() }}</h2>
    </div>
    <div class="body">
        <ul>
            <li>
                <div>
                    <p> <b>Ingeniería en Sistemas Computacionales</b><br>
                        JUN 2012 - JUN 2017<br>
                        Tecnológico Superior de Escárcega
                    </p>
                </div>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'EducationComponent',
    components: {

    },
    data() {
        return {
            title: 'EDUCACIÓN'
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