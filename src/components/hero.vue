<template>
    <div>
        <img src="../assets/coverlg_home.jpeg" alt="">
        <span>Come ti senti dopo aver installato Vue-CLI <br> e inserito un solo componente title</span>
    </div>
</template>

<script>
export default{
    name: 'hero',
}
</script>

<style scoped lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');
div{
    position: relative;
}
img, div{
    max-width: 1000px;
    margin: auto;
}
span{
    width: 100%;
    color: white;
    position: absolute;
    bottom: .625rem;
    left: 50%;
    transform: translateX(-50%);
    font-size: 50px;
    font-family: 'Bebas Neue', sans-serif;
}
</style>