<template>
  <header>
    <img src="../../assets/avada-food-logo.png" alt="">
    <div class="small_container">
        <div class="navBar">
           
        <MyNav v-for="element, index in menuLinks" :key="index" :liDetails="element" />
        
        </div>

        <!-- <ul>
            <li v-for="link, index in menuLinks" :key="index" 
                :class="{ 'current': link.current }">
                <a :href="link.url">{{ link.text }}</a>
            </li>
            <li><a href="#"><i class="fa-solid fa-magnifying-glass"></i></a></li>
        </ul> -->
    </div>
    


  </header>
</template>

<script>
import MyNav from './MyNav.vue'
export default {
    components:{
        MyNav,
    },
  data() {
        return {
            menuLinks: [
                {
                    text: 'Home',
                    url: '#',
                    current: true
                },
                {
                    text: 'Recipes',
                    url: '#',
                    current: false
                },
                {
                    text: 'Places',
                    url: '#',
                    current: false
                },
                {
                    text: 'Blog',
                    url: '#',
                    current: false
                },
                {
                    text: 'About',
                    url: '#',
                    current: false
                },
                {
                    text: 'Contact',
                    url: '#',
                    current: false
                },
                
            ],
        };
    }

}
</script>

<style scoped lang="scss">
@import '../../style/variables.scss';

header{
    height: 150px;
}

img{
    height: 80px;
    width: auto;
    margin: 0 auto 25px auto;
}

.small_container{
    height: 45px;
    .navBar{
        height: 100%;
        display: flex;
        justify-content: space-between;
        align-items: center;
        font-size: 13px;
        li{
            height: 60%;

            a{
                color: inherit;
            }
            
            &.current{
                box-shadow: 0 -3px $orange_element inset;
                color: $orange_element;
            }

        }
    }

}



</style>