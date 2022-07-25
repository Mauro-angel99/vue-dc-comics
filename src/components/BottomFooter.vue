<template>
    <footer>
        <div class="bg-b-footer">
            <div class="container">
                <div class="footer-flex">
                    <button class="button-footer">SIGN-UP NOW!</button>
                    <div class="footer-social">
                        <h3>FOLLOW US</h3>
                        <img src="../assets/img/footer-facebook.png" alt="">
                        <img src="../assets/img/footer-twitter.png" alt="">
                        <img src="../assets/img/footer-youtube.png" alt="">
                        <img src="../assets/img/footer-pinterest.png" alt="">
                        <img src="../assets/img/footer-periscope.png" alt="">
                    </div>
                </div>
            </div>
        </div>

    </footer>
</template>

<script>
export default {
    name: 'BottomFooter',
}
</script>

<style lang="scss">
.bg-b-footer {
    height: 110px;
    background-color: #303030;
    display: flex;
    align-items: center;
}

.button-footer {
    color: white;
    font-size: 18px;
    background-color: transparent;
    border: 3px solid #0C7CEC;
    padding: 10px;
}

.footer-flex {
    display: flex;
    justify-content: space-between;
}

.footer-social {
    width: 35%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
</style>