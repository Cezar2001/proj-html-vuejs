<template>
    <div class="container">
        
        <h1>Testimonials.</h1>
        
        <div class="up">
            <i class="fas fa-long-arrow-alt-up"></i>
        </div>
        
        <div class="person">
            
            <img src="../assets/h3-img-04.png" alt="">
            
            <h4>Cynthia Clark</h4>
            
            <span>"Lorem ipsum dolor sit amet, consectetur adipiscing elit sed eiusmod tempor incididunt ut labore et dolore magna aliqua."</span>
            
            <div class="flex">
                <div>01</div>
                <div class="line"></div>
                <div class="line-empty"></div>
                <div>03</div>
            </div>
        </div>

        <div class="left">
            <i class="fas fa-long-arrow-alt-left"></i>
        </div>

        <div class="right">
            <i class="fas fa-long-arrow-alt-right"></i>
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
    height: 550px;
    text-align: center;
    position: relative;

    .left, .right{
        color: $light-grey-color;
        position: absolute;
        font-size: 35px;
        top: 250px
    }

    .left{
        left: 40px;
    }

    .right{
        right: 40px;
    }

    .up{
        position: absolute;
        right: 10px;
        top: 120px;
        padding: 10px 13px;
        background-color: $white-color;
        border-radius: 50%;
        color: $orange-color;
        }

    h1{
        font-size: 150px;
        color: $grey-color;
    }

    .person{
        color: $light-grey-color;
        width: 450px;
        position: absolute;
        top: 110px;
        left: 370px;

        img{
            border: 3px $white-color solid;
            border-radius: 50%;
        }

        h4{
            color: $white-color;
            padding: 15px 0;
        }

        .flex{
            display: flex;
            justify-content: center;
            align-items: center;
            margin-top: 20px;

            div{
                padding: 0 10px;
            }

            .line{
                border-bottom: 2px $clear-grey-color solid;
                width: 35px;
            }

            .line-empty{
                border-bottom: 1px $light-grey-color solid;
                width: 75px;
            }
        }


    }
}
</style>