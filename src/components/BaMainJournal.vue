<template>
  <section class="big_container">
    <div class="my_container">
            <div></div>
            <h2 class="section_title">foodie journal</h2>
            <div></div>
    </div>

  </section>
</template>

<script>
export default {

}
</script>

<style scoped lang="scss">
@import '../style/variables';

section{
    background-color: white;
    height: 250px;
}
.my_container{
    width: 95%;
    margin: 0 auto;
    padding: 30px 0;
    display: flex;
    justify-content: center;
    align-items: center;

    div{
        width: calc( 100% - 525px);
        background-color: $grey_04_darkBack;
        height: 1.5px;
    }
    .section_title{
    width: 175px;
    padding: 0 15px;
}

}


</style>