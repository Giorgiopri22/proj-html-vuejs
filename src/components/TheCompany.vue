<script >

import RadialProgress from "vue3-radial-progress";

export default{
    name: "TheCompany",
    components:{
        RadialProgress,
    }
}

</script>

<template>
    <section class="d-flex">
        <div class="about-company">
            <div class="box">
                <div>
                    <span class="span-title">
                        ABOUT THE NETWORK
                    </span>
                    <div class="d-flex my-4">
                        <h2 class="me-1 special">The</h2>
                        <h2 class="not-special">Company</h2>
                    </div>
                    <p>With all of this expertise and capability comes an unrivalled commitment to customer service.</p>
                </div>
                
                <div class="d-flex justify-content-between my-4">
                    <RadialProgress class="d-flex justify-content-center align-items-center pippo" diameter="120" total-steps="100" completedSteps="0">
                        <span class="percent">0%</span>
                    </RadialProgress> 
                    <div>
                        <h4>Leadership</h4>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
                <div class="d-flex justify-content-between my-4">
                    <RadialProgress class="d-flex justify-content-center align-items-center pippo" diameter="120" total-steps="100" completedSteps="0">
                        <span class="percent">0%</span>
                    </RadialProgress> 
                    
                    <div>
                        <h4>Psychology</h4>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
                <div class="d-flex justify-content-between my-4">
                    <RadialProgress class="d-flex justify-content-center align-items-center pippo" diameter="120" total-steps="100" completedSteps="1">
                        <span class="percent">1%</span>
                    </RadialProgress> 
                    <div>
                        <h4>Flexybility</h4>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
                
            </div>
        </div>
        <div>
            <img src="../assets/img/about-5.jpg" alt="company-building">
        </div>
    </section>
</template>

<style lang="scss" scoped>
   section{
    width: 100%;
        .about-company{
            background-color: #111117;
            display: flex;
            padding-left: 20%;
            color: white;
                .box{
                    width: 100%;
                    align-self: center;
                        .span-title{
                            font-weight: 700;
                            color: #3CA29E;
                        }
                        h2{
                            font-weight: 900;
                            font-size: 50px;
                        }
                        .percent{
                            font-size: 25px;
                            font-weight: 900;
                            transform: rotate(90deg);
                        }
                        
                        .special{
                            background-color: #12262D;
                            padding: 10px;
                            border-radius: 3px;
                        }
                        .not-special{
                            padding: 10px;
                        }                        
                }
                
                .pippo{
                    transform: rotate(-90deg);
                }
        }
        div{
            width: 50%;
                img{
                    width: 100%;
                }
        }
   }
</style>