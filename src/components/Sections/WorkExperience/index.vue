<template>
    <div class="title">
        <img class="image" alt="Vue logo" src="@/assets/logo.png">
        <h2>{{ title.toUpperCase() }}</h2>
    </div>
    <div class="body">
        <ul>
            <li>
                <div>
                    <p> <b>Dev Team</b><br>
                        MAR 2024 - Actualmente<br>
                        <i>WorgCorp</i><br>
                        555-555-5555 | hello@gmail.com | <a
                            href="https://www.bsdenterprise.com/mx/">bsdenterprise.com</a><br>
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
                        been
                        the industry's standard dummy text ever since the 1500s, when an unknown printer took a
                        galley
                        of type and scrambled it to make a type specimen book.
                    </p>
                </div>
            </li>
            <li>
                <div>
                    <p> <b>Dev Team (Mérida, Yuc.)</b><br>
                        MAY 2021 - FEB 2024<br>
                        <i>COTEMAR S.A. de C.V.</i><br>
                        555-555-5555 | hello@gmail.com | <a href="https://www.cotemar.com.mx">cotemar.com.mx</a><br>
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
                        been
                        the industry's standard dummy text ever since the 1500s, when an unknown printer took a
                        galley
                        of type and scrambled it to make a type specimen book.
                    </p>
                </div>
            </li>
            <li>
                <div>
                    <p> <b>Becario</b><br>
                        ENE 2017 - SEPT 2017<br>
                        <i>WORGCORP</i><br>
                        555-555-5555 | hello@gmail.com | <a href="https://www.worgcorp.com">worgcorp.com</a><br>
                        Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has
                        been
                        the industry's standard dummy text ever since the 1500s, when an unknown printer took a
                        galley
                        of type and scrambled it to make a type specimen book.
                    </p>
                </div>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    name: 'WorkExperienceComponent',
    components: {

    },
    data() {
        return {
            title: 'EXPERIENCIA LABORAL'
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