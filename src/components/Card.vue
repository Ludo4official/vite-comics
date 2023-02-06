<script>

export default {
    name: 'Card',
    props: {
        title: String,
        src: String
    }

}

</script>

<template>
     <div class="cards">
            <div class="card">
                <img :src="src" :alt="title">
                <h3> {{ title }}</h3>
            </div>
        </div>
</template>

<style lang="scss" scoped>

</style>