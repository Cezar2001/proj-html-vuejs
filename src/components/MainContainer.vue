<template>
    <div class="container">
        <div class="tabble">
            <div class="grey-background events">
                <h1>Upcoming Events</h1>
            </div>
            
            <div class="flex white-background">
                <div class="date-box">
                    <h3>07</h3>
                    <span>Jan. 2022</span>
                </div>

                <div class="journey">
                    <h3>Melbourne Coaching</h3>
                    <div><i class="far fa-clock"></i>9:00 am - 5:00 pm, Jan 7, 2022</div>
                    <div><i class="fas fa-map-marker-alt"></i>Cambridge, MA 02138, USA</div>
                    <h5>READ MORE</h5>
                </div>
            </div>
            
            <div class="flex grey-background">
                <div class="date-box">
                    <h3>11</h3>
                    <span>Jan. 2022</span>
                </div>

                <div class="journey">
                    <h3>New York Coaching</h3>
                    <div><i class="far fa-clock"></i>9:00 am - 5:00 pm, Jan 11, 2022</div>
                    <div><i class="fas fa-map-marker-alt"></i>Cambridge, MA 02138, USA</div>
                    <h5>READ MORE</h5>
                </div>
            </div>

            <div class="flex grey-background">
                <div class="date-box">
                    <h3>21</h3>
                    <span>Jan. 2022</span>
                </div>

                <div class="journey">
                    <h3>London Coaching</h3>
                    <div><i class="far fa-clock"></i>9:00 am - 5:00 pm, Jan 21, 2022</div>
                    <div><i class="fas fa-map-marker-alt"></i>Cambridge, MA 02138, USA</div>
                    <h5>READ MORE</h5>
                </div>
            </div>
        </div>

        <div class="up">
            <i class="fas fa-long-arrow-alt-up"></i>
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
    background: url("../assets/h1-img-09.jpg") no-repeat;
    background-size: cover;
    height: 670px;
    position: relative;

    .tabble{
        padding: 75px 0 0 200px;
    }

    .events{
        width: 450px;
        padding: 20px;
    }

    .flex{
        display: flex;
        width: 450px;
        padding: 20px;
        border-top: 1px $border-grey-color solid;
        
        .date-box{
            color: $white-color;
            background-color: $orange-color;
            width: 90px;
            height: 50px;
            padding: 5px;
            margin-right: 15px;
            text-align: center;
        }

        .journey{
            
            h3{
                padding-bottom: 10px;
            }

            div{
                padding: 5px 0;
                color: $light-grey-color;

                i{
                    color: $orange-color;
                    padding-right: 10px;
                }
            }

            h5{
                padding-top: 10px;
            }
        }
    }

    .white-background{
        background-color: $white-color;
    }

    .grey-background{
        background-color: $clear-grey-color;
    }

    .up{
        position: absolute;
        right: 10px;
        top: 375px;
        padding: 10px 13px;
        background-color: $white-color;
        border-radius: 50%;
        box-shadow: 2px 2px 5px $light-grey-color;
        color: $orange-color;
    }
}
</style>