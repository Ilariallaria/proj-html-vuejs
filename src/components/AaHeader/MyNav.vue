<template>
    <div >
        <a href="#">{{liDetails.text}} </a>
    </div>
</template>

<script>
export default {
    props:{
        liDetails: Object
    }

}
</script>

<style scoped lang="scss">
@import '../../style/variables.scss';


    a{
        color: inherit;

        &.current{
        box-shadow: 0 -3px $orange_element inset;
        color: $orange_element;
    }
    }
            
 
</style>