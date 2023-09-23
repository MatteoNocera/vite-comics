<script>
export default {
    name: 'AppHeader',
    data() {
        return {
            active: '',
            voices: [
                {
                    name: 'CHARACTERS'
                },
                {
                    name: 'COMICS'
                },
                {
                    name: 'MOVIES'
                },
                {
                    name: 'TV'
                },
                {
                    name: 'GAMES'
                },
                {
                    name: 'COLLECTIBLES'
                },
                {
                    name: 'VIDEOS'
                },
                {
                    name: 'FANS'
                },
                {
                    name: 'NEWS'
                },
                {
                    name: 'SHOP'
                }
            ]
        }
    }

}
</script>

<template>
    <header id="app_header">

        <nav class="navbar navbar-expand py-0">

            <div class="container">

                <a class="navbar-brand py-0" href="#">
                    <img src="../assets/img/dc-logo.png" alt="Logo DC" class="">
                </a>

                <ul class="navbar-nav d-flex">

                    <li v-for="(voice, index) in voices" @click="active = index" :class="active === index ? 'selected' : ''"
                        class="nav-item">
                        <a class="nav-link" href="#">{{ voice.name }}</a>
                    </li>

                </ul>

            </div>

        </nav>

    </header>
    <!-- /#app_header -->
</template>


