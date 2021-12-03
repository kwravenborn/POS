<template>
    <div id="login-index">
        <div class="split-container ht--fullscreen">
            <div class="left-half d-flex al-hv-center">
                <div class="wrapper al-txt-center">
                    <h2>Login POS</h2>
                    <form action="" class="login-form">
                        <div class="form__group">
                            <input type="text" name="username" class="form__input" placeholder="username">
                        </div>
                        <div class="form__group">
                            <input type="password" name="password" class="form__input" placeholder="password">
                        </div>
                        <div class="form__group">
                            <input type="submit" class="form__input form__submit" value="Log in">
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'login-index'
}
</script>

<style scoped>
.ht--fullscreen {
  height: 100vh;
}
.al-hv-center {
   align-items: center;
    justify-content: center;
}
.d-flex {
  display: flex;
}
split-container {
  display: flex;
  flex-direction: row;
}
.left-half {
    height: 100%;
    flex-basis: 50%;
    background-color: #EBEEF2;
    text-align: center;
}
.content {
  width: 100%;
}
.al-txt-center {
  text-align: center;
}
input[type="submit"] {
    border-bottom-right-radius: 4px;
    border-bottom-left-radius: 4px;
    background-color: #0F4F99;
    color: #fff;
    font-weight: 700;
    cursor: pointer;
}
.form__group {
    margin-bottom: .5rem;
}
.form__input {
    border: 0;
    padding: 2rem;
    width: 30rem;
}
input:focus {
    outline: 0;
    transform: scale(1.01);
}
input {
    display: block;
    font-family: inherit;
    font-size: 1.6rem;
    transition: transform .2s ease-in;
}
input[type="text"] {
    border-top-right-radius: 4px;
    border-top-left-radius: 4px;
}
h2 {
    font-size: 3rem;
    text-transform: uppercase;
    margin-bottom: 3rem;
    font-weight: 900;
}

</style>
