<template>
    <div class="form-root">
    <input type="text" placeholder="Email or phone number">
    <input type="password" placeholder="Password">
    <button id="b_login">Log In</button>
    <a id="a_password" href="#">Forgot password?</a>
    <hr>
    <button id="b_create">Create new account</button>
    <div id="ad">
        <p><a href="#">Create a Page</a> for a celebrity, brand or business.</p>
    </div>
    </div>
</template>

<script>
    export default {
        name: 'Form'
    }
</script>

<style scoped>
    * {
        box-sizing: border-box;
    }

    .form-root {
        display: flex;
        flex-direction: column;
        background-color: white;
        width: 25%;
        padding: 20px;
        box-shadow:
            0 2px 4px rgba(0, 0, 0, .1), 
            0 8px 16px rgba(0, 0, 0, .1);
    }

    .form-root input {
        margin: 10px 0;
        padding-top: 10px;
        padding-bottom: 10px;
        padding-left: 7px;
        border-radius: 4px;
        border: 1px solid;
    }

    .form-root input:focus {
        outline: none !important;
        border: 1px solid #1877f2;
        box-shadow: 0 0 5px, #1877f2;
    }

    #b_login {
        background-color: #1877f2;
        border: none;
        border-radius: 6px;
        color: white;
        font-weight: bold;
        font-size: 1.5rem;
        padding: 5px 0;
    }

    #b_login:hover {
        cursor: pointer;
    }

    #a_password {
        text-align: center;
        margin-top: 10px;
        margin-bottom: -7px;
    }

    #b_create {
        background-color: #42b72a;
        border: none;
        border-radius: 6px;
        color: white;
        font-weight: bold;
        font-size: 1.4rem;
        padding: 5px 0;
        width: 70%;
        margin: 0 auto;
    }

    #b_create:hover {
        cursor: pointer;
    }

    #ad {
        margin-top: 20px;
        margin-left: auto;
        margin-right: auto;
        color: #1c1e21;
    }

    #ad a {
        color: #1c1e21;
        font-weight: bold;
    }

    #ad a:hover {
        text-decoration: underline;
    }


</style>