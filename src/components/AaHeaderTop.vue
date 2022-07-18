<template>
  <header>
    <div class="big_container">
        <div class="sx_links">
            <div>
                <a href="#">Downoload App <span id="ios" >iOS</span></a>

            </div>
            <a href="#">Advertise with us</a>
        </div>
        <div class="dx_socials">
            <!-- <div><i class="fa-brands fa-facebook-f"></i></div>
            <span><i class="fa-brands fa-instagram"></i></span>
            <span><i class="fa-brands fa-twitter"></i></span>
            <span><i class="fa-brands fa-youtube"></i></span> -->
            <span>ico</span>
            <span>ico</span>
            <span>ico</span>
            <span>ico</span>
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
    

    #ios{
        background-color: $orange_element;
        border-radius: 5px;
        padding: 3px 5px;
        color: white;
        font-size: 9px;
    }
}

.dx_socials{
    color: black;
}


</style>