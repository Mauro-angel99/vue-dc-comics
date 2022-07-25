<template>
    <header>
        <div class="container">
            <div class="row">
                <figure>
                    <img class="logo-small" src="../assets/img/dc-logo.png" alt="">
                </figure>
                <ul class="side-bar">
                    <li class="side-bar-item" v-for="(item, i) in sideBar" :key="i" :class="{ 'active': item.current }">
                        {{ item.text }}</li>
                </ul>
            </div>
        </div>
    </header>
</template>

<script>
export default {
    name: 'BaseHeader',
    data() {
        return {
            sideBar: [
                {
                    text: 'Characters',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Comics',
                    url: '#',
                    current: true,
                },
                {
                    text: 'Movies',
                    url: '#',
                    current: false,
                },
                {
                    text: 'TV',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Games',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Collectibles',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Videos',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Fans',
                    url: '#',
                    current: false,
                },
                {
                    text: 'News',
                    url: '#',
                    current: false,
                },
                {
                    text: 'Shop',
                    url: '#',
                    current: false,
                },
            ]
        }
    }
}
</script>

<style lang="scss">
header {
    height: 130px;
    font-size: 16px;
    font-weight: 600;

}

.container {
    width: 1100px;
    margin: 0 auto;
}

.row {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo-small {
    height: 90px;
}

.side-bar {
    height: 100%;
    width: 55%;
    display: flex;
    list-style: none;
    justify-content: space-between;
}

.side-bar-item {
    height: 130px;
    line-height: 130px;
    cursor: pointer;

    &.active {
        color: #0C7CEC;
        border-bottom: 3px solid #0C7CEC;
    }

    &:hover {
        color: #0C7CEC;
        border-bottom: 3px solid #0C7CEC;
    }
}
</style>