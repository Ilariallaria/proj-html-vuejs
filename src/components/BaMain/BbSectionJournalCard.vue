<template>
    <div class="my_card">
        <div class="my_cont-img">
            <img src="../../assets/single-post-img3-400x263.jpg" alt="Card image">
        </div>
        <div class="my_cont-body">
            <div class="my_card-title">Food Corner: Top Japanese Resturant for Sushi</div>
            <div class="my_card-subtitle">Card subtitle</div>
            <hr>
            <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
            <a href="#" class="btn">Go somewhere</a>
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
@import '../../style/variables';

.my_card{
    height: inherit;
    width: inherit;
    border: 1px solid black;
}
.my_cont-img{
    height: 60%;
}

.my_cont-body{
    height: 40%;
    text-align: center;

    .my_card-title{
        color: $grey_01;
        font-size: 14px;
        padding: 0 20px;
    }
    .my_card-subtitle{
        color: $grey_02;
        font-size: 12px;
    }

}


</style>