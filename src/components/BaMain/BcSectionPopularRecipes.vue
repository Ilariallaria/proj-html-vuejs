<template>
    <section class="my_section">
        <div class="big_container">
            <div class="my_section-txt">
                <h2 class="section_title">popular recipes</h2>
                <div class="section_subtitle"> lorem ipsum dolor quavit rende loreti subum carneit  rende loreti rende. <br> rende loreti subum carneit </div>
            </div>
        
            <div class="container">
                <div class="row">
                    <div class="col-6 gx-4 my_padding-sx">
                        <div class="my_card">
                            <div class="my_cont-img">
                                <img src="../../assets/Yogurt-Nan-600x395.jpg" alt="Card image">
                            </div>
                            <div class="my_cont-body">
                                <div class="my_card-title">Lunch Favourite with Salad, naan And Beans</div>
                                <div class="my_card-subtitle">Bakery, Featured Healthy, Latest Recipes, Staff Picks</div>
                                <hr>
                                <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque corporis voluptas deserunt, nostrum accusamus sint impedit, nesciunt laudantium et atque eaque ratione odit vitae eum magni minus. Voluptatibus, dicta nihil. Lorem ipsum dolor, sit amet consectetur adipisicing elit, sit amet consectetur adipisicing elit, sit amet.</p>
                                <a href="#" class="btn my_btn">learn more</a>
                            </div>
                        </div>
                    </div>
                    <div class="col gx-5 my_padding-dx">
                        <div class="row gy-3 row_padding row-cols-2 ">
                            <div class="col">
                                <img class="little_img" src="../../assets/Mixed-fruits-200x132.jpg" alt="Card image">
                            </div>
                            <div class="col">
                                <img class="little_img" src="../../assets/r-rachel-park-366508-unsplash-min-200x132.jpg" alt="Card image">
                            </div>
                            <div class="col">
                                <img class="little_img" src="../../assets/r-michelle-tsang-500721-unsplash-min-200x132.jpg" alt="Card image">
                            </div>
                            <div class="col">
                                <img class="little_img" src="../../assets/quick-summer-drink-460x295.jpg" alt="Card image">
                            </div>
                            <div class="col">
                                <img class="little_img" src="../../assets/r-maarten-van-den-heuvel-400626-unsplash-min-460x295.jpg" alt="Card image">
                            </div>
                            <div class="col">
                                <img class="little_img" src="../../assets/perfect-cosmopolitan-460x295.jpg" alt="Card image">
                            </div><div class="col">
                                <img class="little_img" src="../../assets/fi2x-6-460x295.jpg" alt="Card image">
                            </div>
                            <div class="col">
                                <img class="little_img" src="../../assets/r-brooke-lark-96398-unsplash-min-460x295.jpg" alt="Card image">
                            </div>


                        </div>

                        
                    </div>
                </div>
            </div>

        </div>
    </section>
  
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
@import '../../style/variables';
.my_section{
    height: 1000px;
    background-color: $grey_05_lightBack;
}
.my_section-txt{
    padding-top: 320px;
    padding-bottom: 50px;
    text-align: center;
}
.my_card{
    background-color: white;
}

.my_cont-body{
    padding: 25px 20px;

    .my_card-title{
        color: $grey_01;
        font-size: 14px;
        font-weight: 700;
    }
    .my_card-subtitle{
        color: $grey_02;
        font-size: 11px;
    }
    hr{
        color: $grey_03;
    }
    p{
        color: $grey_02;
        font-size: 11px;
    }
}

.my_padding-sx{
    padding-left: 0;
}
.my_padding-dx{
    padding-right: 0;
}
.row_padding{
    padding-left: 8px;
}
.little_img{
    width: 190px;
    height: 120px;
}
</style>