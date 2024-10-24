<template>
    <ul class="ul__menu">
        <li><button class="button__menu">USUARIOS</button></li>
        <li><button class="button__menu">HABILIDADES</button></li>
    </ul>
</template>

<script>
export default {
    name: 'MenuLateralComponent'
}
</script>

<style scoped>
.ul__menu {
    display: block;
    list-style-type: none;
    width: 120px;
    padding-left: 20px;
}

.button__menu {
    border: none;
    width: 100%;
    height: 50px;
    text-align: left;
}
</style>