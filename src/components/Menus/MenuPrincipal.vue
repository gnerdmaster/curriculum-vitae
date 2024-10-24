<template>
    <ul class="ul__menu">
        <li><button class="button__menu">USUARIOS</button></li>
        <li><button class="button__menu">HABILIDADES</button></li>
    </ul>
</template>

<script>
export default {
    name: 'MenuPrincipalComponent'
}
</script>

<style scoped>
.ul__menu {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
}

.ul__menu li {
    margin: 0 10px;
}

.button__menu {
    border: none;
    width: 100%;
    height: 50px;
    text-align: center;
}
</style>