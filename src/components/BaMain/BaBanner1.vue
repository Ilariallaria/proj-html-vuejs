<template>
<section>
  <div class="small_container textBox">
    
    <div id="orangeElement">TODAY'S PICK</div>

    <div class="titles">
      <h2>Food Corner: Top Japanese Resturant for Sushi</h2>
      <h4>March 25, 2019</h4>
    </div>
  </div>

  <div class="spamBox">
    <div class="spam">
      <span id="icon"><i class="fa-solid fa-folder-open"></i></span>
      <div>Demos</div>
    </div>
    <div class="spam">
      <div id="discount"><sup>$</sup>39</div>
      <div>On Sale</div>
    </div>
  </div>
</section>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
@import '../../style/variables.scss';
section{
  height: 480px;
  background-image: url('../../assets/single-post-img3-1200x790.jpg');
  background-size:cover;
  background-position: center;
  background-repeat: no-repeat;
  display: flex;
  align-items: center;
  position: relative;
}
.textBox{
  background-color: white;
  height: 170px;
  border-radius: 10px;
  position: relative;
}
#orangeElement{
  width: fit-content;
  background-color: $orange_element;
  padding: 8px 12px;
  border-radius: 7px;
  color: white;
  font-size: 11px;
  position: absolute;
  top: -8%;
  left: 40%;
  box-shadow: 0 6px 15px 0 rgba(0, 0, 0, 0.19);
}
.titles{
  text-align: center;

  h2{
    font-size: 33px;
    color:$grey_01;
    padding-top:35px
  }
  h4{
    font-size:13px;
    color:$grey_02;
    padding: 20px 0;
  }
}

.spamBox{
  position: absolute;
  top: -15%;
  right: 1%;

  .spam{
    width: 45px;
    height: 45px;
    background-color: white;
    border-radius: 5px;
    box-shadow: 0 -1px 18px 0 rgba(0, 0, 0, 0.19);
    margin-bottom: 5px;
    font-size: 11px;
    color:$grey_01;
    text-align: center;    
  }
  #icon{
    font-size: 17px;

    i{
      padding-top: 9px;
    }
  }
  #discount{
    color:$green_element;
    font-size: 20px;
    font-weight: 700;
  }
}


</style>