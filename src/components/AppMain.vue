<template>
    <div id="app_main">
        <div class="container">

            <div class="position-relative">

                <button id="current" class="btn btn-primary mb-3 position-absolute">CURRENT SERIES</button>
            </div>

            <div
                class="row row-cols-1 row-cols-sm-2 row-cols-md-4 row-cols-lg-6 justify-content-between justify-content-md-center py-3 g-4 ">

                <AppCard v-for="comic in comics" :thumb="comic.thumb" :series="comic.series"></AppCard>

            </div>

            <div class="d-flex justify-content-center">

                <button id="load" class="btn btn-primary mb-3 px-4">Load More</button>
            </div>

        </div>

    </div>
    <!-- /#app_main -->
</template>

<script>
import comics from '../comics.js';
import AppCard from './AppCard.vue';

export default {
    name: 'AppMain',
    data() {
        return {
            comics
        };
    },
    components: {
        AppCard
    }
}
</script>
