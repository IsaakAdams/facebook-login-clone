<template>
    <div class="content-root">
        <div class="text-content">
            <p id="header">facebook</p>
            <p>Connect with friends and the world<br>around you on Facebook.</p>
        </div>
        <Form />
    </div>
</template>

<script>
import Form from './Form.vue';
    export default {
        name: 
            'MainContent',
        components: {
            Form
        }
    }
</script>

<style scoped>
    * {
        box-sizing: border-box;
    }
    .content-root {
        display: flex;
        flex-direction: row;
        font-family: inherit;
        padding: 170px 0;
        justify-content: space-evenly;
    }

    .text-content {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        width: 35%;

    }

    #header {
        font-size: 4rem;
        color: #1877f2; 
        font-weight: bold;
    }

    p {
        font-size: 1.5rem;
        color: #1c1e21;
    }
</style>