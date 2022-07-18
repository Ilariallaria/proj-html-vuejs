<template>
  <header>
    <div class="big_container">
        <div class="sx_links">
            <div>
                <a href="#">Downoload App <span id="orangeElement" >iOS</span></a>

            </div>
            <a href="#">Advertise with us</a>
        </div>
        <div class="dx_socials">
            <span><i class="fa-brands fa-facebook-f"></i></span>
            <span><i class="fa-brands fa-instagram"></i></span>
            <span><i class="fa-brands fa-twitter"></i></span>
            <span><i class="fa-brands fa-youtube"></i></span>
        </div>
        
    </div>

  </header>
</template>

<script>

export default {

}
</script>

<style scoped lang="scss">
@import '../style/variables';

header{
    height: 40px;

    a{
        color: $grey_02;
        padding-right: 10px;
    }
}

.big_container{
    height: 100%;
}

.sx_links{
    display: flex;
    align-content: center;
    font-size: 11px;
    
    #orangeElement{
        background-color: $orange_element;
        border-radius: 5px;
        padding: 3px 5px;
        color: white;
        font-size: 9px;
    }
}

.dx_socials{
    color: $grey_03;
    font-size: 12px;
    
    span{
        padding-right: 20px;
    }
}


</style>