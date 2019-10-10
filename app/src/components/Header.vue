<template>
    <header>
        <div class="header">
            <img alt="Vue logo" src="../assets/logo.png">
        </div>
    </header>
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
    header {
        top: 0;
        width: 100vw;
        background-color: white;
        display: flex;
        justify-content: center;
        -webkit-box-shadow: 0px 0px 5px 0px rgba(0,0,0,0.1);
        -moz-box-shadow: 0px 0px 5px 0px rgba(0,0,0,0.1);
        box-shadow: 0px 0px 5px 0px rgba(0,0,0,0.1);

        img {
            height: 32px;
            margin: 20px 0;
        }
    }
</style>