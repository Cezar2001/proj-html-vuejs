<template>
    <div class="container">
        
        <div>
            <img src="@/assets/logo-img-01.png" alt="">
        </div>

        <div>
            <ul>
                <li v-for="link in option" :key="link.id">
                    <span><i class="fas fa-long-arrow-alt-right"></i>{{ link.label }}</span>
                </li>
                <li><i class="fas fa-search"></i></li>
                <li><i class="fas fa-list"></i></li>
            </ul>
        </div>
    
    </div>
</template>

<script>
export default {
    props: {
        option: Object
    }
}
</script>

<style lang="scss" scoped>
@import '../style/variables.scss';
@import '../style/NavBar.scss';
</style>