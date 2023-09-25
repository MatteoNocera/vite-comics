<template>
    <div class="card">
        <img :src="thumb" alt="">
        <div class="card-body">
            <h4 class="card-text">{{ series }}</h4>
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