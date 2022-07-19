<template>
  <header>
    <div class="big_container">
        <div class="sx_links">
            <div>
                <a href="#">Downoload App <span id="orangeElement" >iOS</span></a>
            </div>
            <a id="advertise" href="#">Advertise with us</a>
        </div>
        <div class="dx_socials">
            <span><a href="#"><i class="fa-brands fa-facebook-f"></i></a></span>
            <span><a href="#"><i class="fa-brands fa-instagram"></i></a></span>
            <span><a href="#"><i class="fa-brands fa-twitter"></i></a></span>
            <span><a href="#"><i class="fa-brands fa-youtube"></i></a></span>
        </div>
        
    </div>

  </header>
</template>

<script>

export default {

}
</script>

<style scoped lang="scss">
@import '../../style/variables.scss';

header{
    height: 40px;

    a{
        color: $grey_03;
    }
}

.big_container{
    height: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;

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
    #advertise{
        padding-left: 10px;
    }
}

.dx_socials{
    color: $grey_05_lightBack;
    font-size: 12px;
    
    span{
        padding-left: 20px;

        a{
            color: $grey_03;
        }
    }
}


</style>