<template>
    <div class="card">
        <img :src="thumb" alt="">
        <div class="py-3">
            <h5 class="card-text">{{ series }}</h5>
        </div>
    </div>
</template>

<script>


export default {
    name: 'AppCard',

    props: {
        thumb: String,
        price: String,
        series: String,
        type: String
    }

}
</script>

<style lang="scss" scoped></style>