<template>
    <div class="options">
        <div class="container">
            <div class="row">
                <div class="option" v-for="(item, i) in options" :key="i">
                    <img class="option-img" :src="item.src" alt="">
                    <span class="option-text">{{ item.text }}</span>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'BaseOptions',
    data() {
        return {
            options: [
                {
                    src: require('../assets/img/buy-comics-digital-comics.png'),
                    text: 'DIGITAL COMICS',
                },
                {
                    src: require('../assets/img/buy-comics-merchandise.png'),
                    text: 'DC MERCHANDISE',
                },
                {
                    src: require('../assets/img/buy-comics-subscriptions.png'),
                    text: 'SUBSCRIPTIONS',
                },
                {
                    src: require('../assets/img/buy-comics-shop-locator.png'),
                    text: 'COMIC SHOP LOCATOR',
                },
                {
                    src: require('../assets/img/buy-dc-power-visa.svg'),
                    text: 'DC POWER VISA',
                },
            ]
        }
    }
}
</script>

<style lang="scss">
.options {
    height: 160px;
    background-color: #0C7CEC;
    color: white;
    display: flex;
    align-items: center;
}

.container {
    width: 1100px;
    margin: 0 auto;
}

.option {
    display: flex;
    align-items: center;
}

.option-img {
    height: 60px;
}

.option-text {
    font-size: 12px;
    margin-left: 5px;
}
</style>