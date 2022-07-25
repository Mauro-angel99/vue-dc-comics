<template>
    <main>
        <div class="content">
            <div class="container">
                <div class="row">
                    <h2>Content goes here</h2>
                </div>
            </div>
        </div>
        <BaseOptions />
    </main>
</template>

<script>
import BaseOptions from './BaseOptions.vue'
export default {
    name: 'BaseMain',
    components: {
        BaseOptions,

    }
}
</script>

<style lang="scss">
.content {
    height: 150px;
    color: white;
    background-color: black;
}

.container {
    width: 1100px;
    margin: 0 auto;
}

h2 {
    line-height: 150px;
}

.options {
    height: 160px;
    background-color: #0C7CEC;
}
</style>