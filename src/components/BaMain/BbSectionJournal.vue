<template>
  <section class="big_container">
    <div class="container my_container">
      <div class="row">
        <div class="col">
          <div class="flex">
            <div class="title-hr"></div>
            <h2 class="section_title">foodie journal</h2>
            <div class="title-hr"></div>
          </div>
        </div>
      </div>
      <div class="row pad_top">
        <div class="col">
          <!-- <BbSectionJournalCard/> -->
          <div class="my_card">
            <div class="my_cont-img">
              <img src="../../assets/single-post-img3-400x263.jpg" alt="Card image">
            </div>
            <div class="my_cont-body">
              <div class="my_card-title">Food Corner: Top Japanese Resturant for Sushi</div>
              <div class="my_card-subtitle">By Admin | March 25, 2019</div>
            </div>
          </div>
        </div>
        <div class="col">
          <!-- <BbSectionJournalCard/> -->
          <div class="my_card">
            <div class="my_cont-img">
              <img src="../../assets/fi-roundup-400x263.jpg" alt="Card image">
            </div>
            <div class="my_cont-body">
              <div class="my_card-title">Food Corner: Top Japanese Resturant for Sushi</div>
              <div class="my_card-subtitle">By Admin | March 25, 2019</div>
            </div>
          </div>
        </div>
        <div class="col">
          <!-- <BbSectionJournalCard/> -->
          <div class="my_card">
            <div class="my_cont-img">
              <img src="../../assets/fi-toasts-400x263.jpg" alt="Card image">
            </div>
            <div class="my_cont-body">
              <div class="my_card-title">Food Corner: Top Japanese Resturant for Sushi</div>
              <div class="my_card-subtitle">By Admin | March 25, 2019</div>
            </div>
          </div>
        </div>
      </div>
    </div>

  </section>
</template>

<script>
// import BbSectionJournalCard from '../BaMain/BbSectionJournalCard.vue'
export default {
 components: {
  // BbSectionJournalCard,
 }
}
</script>

<style scoped lang="scss">
@import '../../style/variables';

section{
  background-color: white;
  height: 300px;
  position: absolute;
  top: 610px;
  left: 237px

}

.my_container{
width: 93%;
margin: 0 auto;
padding: 20px 0;
}

.flex{
  display: flex;
  justify-content: space-between;
  .title-hr{
    width: 35%;
    background-color: $grey_04_darkBack;
    height: 1.5px;
    align-self: center;
  }
  h2{
    margin: 0 15px;
  
  .section_title{
    width: 175px;
    align-self: center;
    }
  }
   
}

.pad_top{
  padding-top:10px;
}

.my_card{
  height: inherit;
  width: inherit;
  position: relative;
}
.my_cont-img{
  height: 60%;
  &:hover{
    opacity: (0.7);
  }
  
}

.my_cont-body{
  height: 40%;
  text-align: center;

  .my_card-title{
    color: $grey_01;
    font-size: 14px;
    font-weight: 700;
    padding: 0 20px;
  }
  .my_card-subtitle{
    color: $grey_02;
    font-size: 12px;
  }

}

</style>