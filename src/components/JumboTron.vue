<template>
    <div class="container">
        <div class="specialities">
            <h1>Our specialities<span>.</span></h1>
            <span>Lorem ipsum dolor sit amet, consectetur adipiscing elit</span>
            <div class="line"></div>
        </div>

        <div class="skills">

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
    background-color: $grey-color;
    height: 700px;
    display: flex;
    justify-content: center;

    .specialities{
        width: 1100px;
        height: 500px;
        top: 570px;
        text-align: center;
        position: absolute;
        background-color: $white-color;

        h1{
            margin: 50px 0 10px 0;

            span{
                color: $orange-color;
                border: none;
            }
        }

        span{
            color: $light-grey-color;
        }

        .line{
            border-bottom: 2px $orange-color solid;
            width: 50px;
            margin: 15px 0 0 530px;
        }
    }

    .skills{
        
    }
}
</style>