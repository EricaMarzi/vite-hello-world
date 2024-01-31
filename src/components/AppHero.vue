<script>
export default {
    name: 'AppHero',
    data: () => ({
        image: 'hello-banner.jpeg'
    }),
};
</script>

<template>
    <img :src="`../../img${image}`" alt="">
</template>

<style>
h1 {
    text-align: center;
}
</style>