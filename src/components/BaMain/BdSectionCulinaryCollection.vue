<template>
    <section class="my_section">
      <div class="big_container">
          <div class="my_section-txt">
            <h2 class="section_title">culinary collection</h2>
            <div class="section_subtitle"> lorem ipsum dolor quavit rende loreti subum carneit  rende loreti rende. <br> rende loreti subum carneit </div>
           </div>
        </div>
        <div class="big_container">
            <div class="container">
            <div class="row gy-2 row-cols-4">
                <div class="col">
                    <div class="my_card flex">
                        <img src="../../assets/drinks-recipes.png" alt="">
                        <div>ciao</div>
                    </div>
                </div>
                <div class="col">
                    <div class="my_card flex">
                        <img src="../../assets/soups-recipes.png" alt="">
                        <div>ciao</div>
                    </div>
                </div>
                <div class="col">
                    <div class="my_card flex">
                        <img src="../../assets/baking-recipes.png" alt="">
                        <div>ciao</div>
                    </div>
                </div>
                <div class="col">
                    <div class="my_card flex">
                        <img src="../../assets/dinner-recipes.png" alt="">
                        <div>ciao</div>
                    </div>
                </div>
                <div class="col">
                    <div class="my_card flex">
                        <img src="../../assets/healthy-recipes.png" alt="">
                        <div>ciao</div>
                    </div>
                </div>
                <div class="col">
                    <div class="my_card flex">
                        <img src="../../assets/staff-picks.png" alt="">
                        <div>ciao</div>
                    </div>
                </div>
                <div class="col">
                    <div class="my_card flex">
                        <img src="../../assets/premium-recipes.png" alt="">
                        <div>ciao</div>
                    </div>
                </div>
                <div class="col">
                    <div class="my_card flex">
                        <img src="../../assets/quick-easy-recipes.png" alt="">
                        <div>ciao</div>
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
    height: 550px;
    background-color: $grey_05_lightBack;
}
.my_section-txt{
    padding-top: 50px;
    padding-bottom: 50px;
    text-align: center;
}

.flex{
    display: flex;
    flex-direction: column;
}

.col{
    padding: 5px;
}
.my_card{
    height: 120px;
    // width: 200px;
    background-color: white;
    align-items: center;
    padding-top: 10px;
    margin-top: 10px;
    font-size: 9px;
    font-weight: bold;
    text-transform: uppercase;
    color: $grey_01;
    
    img{
        width: 70px;
        height: 65px;
        margin-bottom: 15px;
    }
}
</style>