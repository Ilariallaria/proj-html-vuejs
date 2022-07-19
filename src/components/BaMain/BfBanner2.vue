<template>
    <section class="my_section">
        <div class="small_container textBox">
            <div class="titles">
                <h2>Subscribe R receive a free ebook</h2>
                <h4>Lorem ipsum dolor quevit dunche norit perse vacum, lorem ipsum dolor quevit dunche ipsum dolor quevit dunche norit perse vacum</h4>
            </div>

            <div class="input_cont flex">
                <input class="my_input" type="text" placeholder ="Insert your email...*">
                <div id="orangeElement">SUBSCRIBE</div>
            </div>
            <div class="txt_note">Lorem ipsum dolor quevit dunche</div>
        </div>

    </section>
  
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
@import '../../style/variables.scss';

.my_section{
  height: 400px;
  background-color: white;
  display: flex;
  align-items: center;
}
.textBox{
    margin: 0 auto;
}

.titles{
  text-align: center;

  h2{
    font-size: 25px;
    color:$grey_01;
    padding-top:35px
  }
  h4{
    font-size:13px;
    color:$grey_02;
    padding: 20px 0;
  }
}

.input_cont{
  padding: 5px;
  height: 45px;
  color:$grey_03;
  display: flex;
  justify-content: space-between;
    
}
.my_input{
  width: 65%;
  height: 100%;
  padding: 0 10px;
  border: none;
  font-size: 11px;
  font-weight: bold;
  color:$grey_03;
  border: 2px solid $grey_04_darkBack;
  border-radius: 5px;
}
#orangeElement{
  width: 30%;
  background-color: $orange_element;
  padding: 8px 12px;
  border-radius: 3px;
  color: white;
  font-size: 11px;
  text-align: center;
}
.txt_note{
    padding-top: 20px;
    font-size: 9px;
    text-align: center;
}






</style>