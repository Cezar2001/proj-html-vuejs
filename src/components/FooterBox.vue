<template>
<div class="container">
    
    <div class="terms">
       
    </div>
         
    <div class="footer-bar">
        <span>Copyright Everlead © MikadoThemes</span>
    </div>
    
</div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import '../style/variables.scss';
.container{
    background-color: $dark-grey-color;
    height: 500px;
    
    .terms{
        height: 470px;
    }

    .footer-bar{
        color: $white-color;
        background-color: $orange-color;
        text-align: center;
        height: 30px;
        line-height: 30px;
    }
}
</style>