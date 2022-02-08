<template>
<div class="main-container">
    <div class="background">

        <nav-bar />
        
        <div class="info">
            <h1>Our Team<span>.</span></h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam excepturi quasi consequuntur magnam cupiditate necessitatibus earum!</p>

            <div class="button">
                <div class="button-info">
                    <span class="border-black">READ MORE</span>
                    <i class="fas fa-long-arrow-alt-right"></i> 
                </div>

                <div class="button-buy">
                    <span class="border-white">PURCHASE</span>
                    <i class="fas fa-long-arrow-alt-right"></i> 
                </div>
            </div>
        
        </div>
    
        <i class="fas fa-long-arrow-alt-left absolute left"></i>
        <i class="fas fa-long-arrow-alt-right absolute right"></i>

    </div>
</div>
</template>

<script>
import NavBar from './NavBar.vue';
export default {
    components: {
        NavBar
    }
}
</script>

<style lang="scss" scoped>
@import '../style/variables.scss';
@import '../style/HeaderBox.scss';
</style>