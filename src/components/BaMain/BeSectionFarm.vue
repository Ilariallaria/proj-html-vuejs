<template>
  <section class="my_section">
    <!-- titolo section -->
    <div class="big_container flex">
      <div class="my_section-txt">
        <h2 class="section_title">farm to table</h2>
        <div class="section_subtitle"> lorem ipsum dolor quavit rende loreti subum carneit  rende loreti rende. <br> rende loreti subum carneit </div>
      </div>
      <div>
        <a href="#" class="btn my_btn">read our blog</a>
      </div>
    </div>
    <!-- corpo section -->
    <div class="big_container flex">
      <!-- colonna sx -->
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
        <div class="btn more_post">
          <a href="#">LOAD MORE POST</a>
        </div>
      </div>
      <!-- colonna dx -->
      <div class="dx_col">

        <div class="leatest_recipes">
          <img src="../../assets/ad-bg.jpg" alt="">
          <h2>VIEW OUR <br> LEATES <br> RECIPES</h2>
        </div>

        <div class="city_guide">
          <img src="../../assets/singapore-featured-image-400x263.jpg" alt="">
          <div class="btn view_all">
            <a href="#"><span><i class="fa-solid fa-earth-americas"></i></span> VIEW ALL CITY GUIDES</a>
          </div>
          <h2>City Guide: Singapore</h2>
          <hr>
        </div>
                
        <div class="input_cont flex">
          <div><i class="fa-solid fa-magnifying-glass"></i></div>
          <input class="my_input" type="text" placeholder ="Search...">
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
    height: 1800px;
    background-color: $grey_05_lightBack;
}
.flex{
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}
// colonna sx
.sx_col{
  padding-top: 40px;
  width: 65%;
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
.more_post{
  width: 100%;
  background-color: $grey_04_darkBack;
  margin-top: 30px;
  font-size: 11px;
  padding: 10px 15px;
  font-weight: bold;
  text-align: center;
  a{
    color: $grey_01;
  }
}

// colonna dx
.dx_col{
  padding-top: 40px;
  width: 30%;
}
.leatest_recipes{
  height: 320px;
  position: relative;
  img{
    height: inherit;
  }
  h2{
  text-align: center;
  line-height: 25px;
  font-size: 16px;
  position: absolute;
  top: 38%;
  right: 35%;
}
}

.city_guide{
  margin-top: 40px;
  position: relative;

  .view_all{
    width: 100%;
    background-color: $orange_element;
    font-size: 10px;
    padding: 7px;
    font-weight: bold;
    text-align: center;
    border-radius: 0;
    a{
      color: white;
      span{
        padding-right: 3px;
      }
    }
  }

  h2{
    font-size: 15px;
    background-color: black;
    opacity: (0.75);;
    color: white;
    width: 70%;
    padding: 10px;
    position: absolute;
    top: 100px;
    left: 0;
  }

  hr{
    margin: 30px 0;
    color:$grey_03;
  }
}
.input_cont{
  padding: 5px;
  height: 40px;
  color:$grey_03;
  border: 2px solid $grey_04_darkBack;
  background-color: white;
  border-radius: 5px;

    
  div{
    padding: 10px 5px 5px 10px;
    background-color: white;
    font-size: 10px;
    height: 100%;
    width: 10%;
  }
  .my_input{
  width: 90%;
  height: 100%;
  padding: 0 10px;
  border: none;
  font-size: 11px;
  font-weight: bold;
  color:$grey_03;
  
  }
}



</style>