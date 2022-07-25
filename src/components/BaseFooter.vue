<template>
    <footer>
        <div class="bg-footer">
            <div class="container-list">
                <div class="row-list">
                    <div class="col-list">
                        <h3>DC COMICS</h3>
                        <ul class="list">
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>TV</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>
                        <h3>SHOP</h3>
                        <ul class="list">
                            <li>Shop DC</li>
                            <li>Shop DC Collectibles</li>
                        </ul>
                    </div>
                    <div class="col-list">
                        <h3>DC</h3>
                        <ul class="list">
                            <li>Terms Of Use</li>
                            <li>Privacy policy (New)</li>
                            <li>Ad Choices</li>
                            <li>Advertising</li>
                            <li>Jobs</li>
                            <li>Subscriptions</li>
                            <li>Talent Whorkshops</li>
                            <li>CPSC Cerificates</li>
                            <li>Ratings</li>
                            <li>Shop Help</li>
                            <li>Contact Us</li>
                        </ul>
                    </div>
                    <div class="col-list">
                        <h3>SITES</h3>
                        <ul class="list">
                            <li>DC</li>
                            <li>MAD Magazine</li>
                            <li>DC Kids</li>
                            <li>DC Universe</li>
                            <li>DC PowerVisa</li>
                        </ul>
                    </div>
                </div>
                <div class="logo-footer"></div>
            </div>
        </div>
    </footer>
</template>

<script>
export default {
    name: 'BaseFooter',
}
</script>

<style lang="scss">
.bg-footer {
    height: 350px;
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
}

.container-list {
    width: 1100px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
}

h3 {
    color: white;
    font-size: 18px;
}

.row-list {
    width: 50%;
    display: flex;
    margin-top: 70px;
}

.col-list {
    margin-right: 30px;
}

.list {
    color: grey;
    list-style: none;
    font-size: 14px;
}

.logo-footer {
    height: 350px;
    width: 40%;
    background-image: url(../assets/img/dc-logo-bg.png);
    background-position: center;
    background-size: cover;
}
</style>