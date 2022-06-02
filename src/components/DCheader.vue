<template>
<header class="header">
    <div class="container">
        <div class="header-logo">
            <img src="../assets/img/dc-logo.png" alt="">
        </div>
        <nav class="header-nav">
            <ul>
                <li><a href="">CHARACTERS</a></li>
                <li><a href="">COMICS</a></li>
                <li><a href="">MOVIES</a></li>
                <li><a href="">TV</a></li>
                <li><a href="">GAMES</a></li>
                <li><a href="">COLLECTIBLES</a></li>
                <li><a href="">VIDEOS</a></li>
                <li><a href="">FANS</a></li>
                <li><a href="">NEWS</a></li>
                <li><a href="">SHOP</a></li>
            </ul>
        </nav>
    </div>

</header>
</template>

<script>
export default {
 name: 'DCheader'
}
</script>

<style lang="scss" scoped>
@import '../assets/style/mixins.scss';
.header{
    &-logo{
        img{
        display: block;
        margin-top: 50px;
        width: 80px;
        height: 80px;
        }
    }
    &-nav{
        ul {
        display: flex;
        justify-content: flex-end;
        @include listInline;
        column-gap: 15px;
        }
    }

}

</style>