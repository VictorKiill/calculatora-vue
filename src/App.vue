<template>
    <h1>Calculadora</h1>
    <MyCalculator />
</template>

<script>
import MyCalculator from './main/MyCalculator.vue'

export default {
    components: { MyCalculator }
}
</script>

<style>
    @font-face {
        font-family: "RobotoMono";
        src: url('./fonts/RobotoMono-Thin.ttf');
    }

    * {
        font-family: 'RobotoMono', monospace;
    }

    body {
        margin: 0;
    }

    #app {
        display: flex;
        flex-direction: column;
        height: 100vh;
        justify-content: center;
        align-items: center;
        text-align: center;

        color: #fff;
        background: linear-gradient(90deg, rgba(31,31,31,1) 0%, rgba(177,177,177,1) 100%);
    }
</style>