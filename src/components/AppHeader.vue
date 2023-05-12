<script >

export default{
    name: "AppHeader",
}

</script>

<template>
    <header>
        <div class="bg-social">
            <section class="d-flex justify-content-between">
                <div>
                    <i class="fa-solid fa-clock"></i>
                    <span>Open Hours: Mon-Sat -9:00-18:00</span>
                </div>
                <div class="info-social">
                    <div>
                        <i class="fa-solid fa-phone"></i>
                        <span>+1(305)1234-5678</span>
                        <i class="fa-solid fa-envelope"></i>
                        <span>hello@example.com</span>
                    </div>
                </div>
                <div class="p-1">
                    <i class="fa-brands fa-facebook"></i>
                    <i class="fa-brands fa-twitter"></i>
                    <i class="fa-brands fa-linkedin-in"></i>
                </div>                
            </section>
        </div>
        <div class="jumbo">
            <nav class="d-flex justify-content-between">
                <div>
                    <span>NEXTGEN</span>
                </div>
                <div>
                    <ul class="d-flex">
                        <a href="/">
                            <li>
                                HOME
                            </li>
                        </a>
                        <a href="/">
                            <li>
                                SERVICES
                            </li>
                        </a>
                        <a href="/">
                            <li>
                                SKILLS
                            </li>
                        </a>
                        <a href="/">
                            <li>
                                PARTNERS
                            </li>
                        </a>
                        <a href="/">
                            <li>
                                BLOG
                            </li>
                        </a>
                        <a href="/">
                            <li>
                                GET IN TOUCH
                            </li>
                        </a>
                    </ul>
                </div>
            </nav>
            <div class="logistic-info">
                <h1>Logistics that goes further.</h1>
                <p>For 20 years working with the most innovative in the field of transport.</p>
                <div>
                    <button class="btn-1">GET IN TOUCH</button>
                    <button class="btn-2">READ MORE</button>
                </div>
            </div>
        </div>
    </header>
</template>

<style lang="scss" scoped>

.bg-social{   
    background-color: #4d5a65;    
        section{
            width: 70%;
            margin: 0 auto;
            padding: 15px;
                div{
                    color:white
                }
            }   
    }
.jumbo::before{
    background-image: url(../assets/img/jumbo.jpg);
    height: 700px;
    background-size: cover;
    background-repeat: no-repeat;
    filter: brightness(50%);
    inset: 0;
    position: absolute;
    content:"";
}
.jumbo{
    position: relative;
    height: 700px;    
        nav{
            width: 70%;
            margin: 0 auto;
            padding: 20px;
            position: absolute;
            left: 50%;
            transform: translateX(-50%);
                span{
                    font-size: 20px;
                    color: white;
                }
                ul{
                    list-style-type: none;
                    font-size: 20px;
                        a{
                            text-decoration: none;
                            color: white;
                            padding: 8px;
                        }
                }
        }
        .logistic-info{
            position:absolute;
            left: 68%;
            transform: translateY(+30%);
            color: white;
            width: 15%;
                h1{
                    font-size: 65px;
                }
                p{
                    font-size: 20px;
                }
                div{
                    
                        .btn-1{
                            background-color: #048383;
                            padding: 7px;
                            color: white;
                            border-radius: 7px;
                            margin-left: 20px;
                        }
                        .btn-2{
                            border-color: #048383;
                            padding: 7px;
                            border-radius: 7px;
                        }
                    };
            }        
    }


</style>