<template>
  <div class="product">
    <img :src="image" :alt="title">
    <h3>{{title}}</h3>
  </div>
</template>

<script>
export default {
    name: 'CardProduct',
    props: {
        title: String,
        image: {
            type: String,
            default: 'https://www.fidoo.com/wp-content/uploads/2020/02/placeholder.png'
        },
    }
}
</script>

<style lang="scss" scoped>
.product {
    background: black;
    padding: 15px;
    color: white;
    margin-left: 50px;
}
</style>