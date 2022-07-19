<template>
  <section class="my_section">
    <div class="big_container flex">
      <div class="my_section-txt">
        <h2 class="section_title">farm to table</h2>
        <div class="section_subtitle"> lorem ipsum dolor quavit rende loreti subum carneit  rende loreti rende. <br> rende loreti subum carneit </div>
      </div>
      <div>
        <a href="#" class="btn my_btn">read our blog</a>
      </div>
    </div>
    <div class="big_container flex">
      <div class="sx_col">
        <div class="my_card">
          <div class="my_cont-img">
            <img src="../../assets/Yogurt-Nan-600x395.jpg" alt="Card image">
          </div>
          <div class="my_cont-body">
            <div class="my_card-title">Lunch Favourite with Salad, naan And Beans</div>
            <div class="my_card-subtitle">Bakery, Featured Healthy, Latest Recipes, Staff Picks</div>
            <hr>
            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Itaque corporis voluptas deserunt, nostrum accusamus sint impedit, nesciunt laudantium et atque eaque ratione odit vitae eum magni minus. Voluptatibus, dicta nihil. Lorem ipsum dolor, sit amet consectetur adipisicing elit, sit amet consectetur adipisicing elit, sit amet.</p>
            <a href="#" >Read More <span><i class="fa-solid fa-chevron-right"></i></span></a>
            <span id="think"><i class="fa-regular fa-comments"></i>O</span>
          </div>
        </div>
        <div class="all_cards flex">
          <div class="single_card">
            <div class="my_cont-img">
              <img src="../../assets/fi-roundup-400x263.jpg" alt="Card image">
            </div>
            <div class="my_cont-body">
              <div class="my_card-title">Lunch Favourite with Salad, naan And Beans</div>
              <div class="my_card-subtitle">By Admin | 25 March 2019</div>
            </div>
          </div>
          <div class="single_card">
            <div class="my_cont-img">
              <img src="../../assets/fi-korean-food-400x263.jpg" alt="Card image">
            </div>
            <div class="my_cont-body">
              <div class="my_card-title">Lunch Favourite with Salad, naan And Beans</div>
              <div class="my_card-subtitle">By Admin | 25 March 2019</div>
            </div>
          </div>
          <div class="single_card">
            <div class="my_cont-img">
              <img src="../../assets/fi-toasts-400x263.jpg" alt="Card image">
            </div>
            <div class="my_cont-body">
              <div class="my_card-title">Lunch Favourite with Salad, naan And Beans</div>
              <div class="my_card-subtitle">By Admin | 25 March 2019</div>
            </div>
          </div>
          <div class="single_card">
            <div class="my_cont-img">
              <img src="../../assets/fi-street-food-400x263.jpg" alt="Card image">
            </div>
            <div class="my_cont-body">
              <div class="my_card-title">Lunch Favourite with Salad, naan And Beans</div>
              <div class="my_card-subtitle">By Admin | 25 March 2019</div>
            </div>
          </div>
          <div class="single_card">
            <div class="my_cont-img">
              <img src="../../assets/fi-organic-breakfast-1200x790.jpg" alt="Card image">
            </div>
            <div class="my_cont-body">
              <div class="my_card-title">Lunch Favourite with Salad, naan And Beans</div>
              <div class="my_card-subtitle">By Admin | 25 March 2019</div>
            </div>
          </div>
          <div class="single_card">
            <div class="my_cont-img">
              <img src="../../assets/fi-water-side-rest-400x263.jpg" alt="Card image">
            </div>
            <div class="my_cont-body">
              <div class="my_card-title">Lunch Favourite with Salad, naan And Beans</div>
              <div class="my_card-subtitle">By Admin | 25 March 2019</div>
            </div>
          </div>

        </div>

      </div>
      <div class="dx_col">Lorem ipsum dolor, sit amet consectetur adipisicing elit. Dolorum accusantium sit, recusandae error inventore iusto natus? Eum similique dignissimos commodi vitae laudantium nihil pariatur debitis accusamus, numquam nam dolore expedita!</div>
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
    height: 2000px;
    background-color: $grey_05_lightBack;
}
.flex{
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}
.sx_col{
  padding-top: 40px;
  width: 60%;
}
.my_card{
  background-color: white;
}
.my_cont-body{
  padding: 25px;

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
  a{
    color: $grey_02;
    font-size: 9px;
  }
  #think{
    font-size: 9px;
    padding-left: 430px;
    i{
      padding-right: 3px;

    }
  }
}

.single_card{
  margin-top: 30px;
  background-color: white;
  width: 47%;
  text-align: center;
}


.dx_col{
  padding-top: 40px;
  width: 36%;
}
</style>