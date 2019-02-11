<template>
    <div id="app">
        <h1>Calculator</h1>
        <Calculator/>
    </div>
</template>

<script>

import Calculator from "./main/Calculator"
export default {
    components: { Calculator }
}
</script>

<style>
    @font-face {
        font-family: "RobotoMono";
        src: url("./fonts/RobotoMono-Thin.ttf");
    }

    * {
        font-family: "RobotoMono", "monospace";
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
        text-align: #fff;
        background: linear-gradient(to right, rgb(178, 178, 253), purple);
    }

</style>
