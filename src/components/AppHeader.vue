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
                    <i class="fa-solid fa-clock me-3"></i>
                    <span >Open Hours: Mon-Sat -9:00-18:00</span>
                </div>
                <div class="info-social">
                    <div class="d-flex">
                        <div class="me-4">
                            <i class="fa-solid fa-phone me-2"></i>
                            <span>+1(305)1234-5678</span>
                        </div>
                        <div class="me-2">
                            <i class="fa-solid fa-envelope me-2"></i>
                            <span>hello@example.com</span>
                        </div>
                    </div>
                </div>
                <div class="p-1">
                    <i class="fa-brands fa-facebook me-5"></i>
                    <i class="fa-brands fa-twitter me-5"></i>
                    <i class="fa-brands fa-linkedin-in "></i>
                </div>                
            </section>
        </div>
        <div class="jumbo">
            <nav class="d-flex justify-content-between align-items-center">
                <div>
                    <span class="special"><strong>N E X</strong></span>
                    <span><strong> G E N</strong></span>
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
                <div class="relative">
                    <h1>Logistics</h1>
                    <h1>that goes further.</h1>
                    <p>For 20 years working with the most innovative in the field of transport.</p>
                </div>
                <div>
                    <button class="btn-1 me-3">GET IN TOUCH</button>
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
                
                
                    .special{
                        color: #3DA4A6;
                        background-color: #5A6E6E;
                        padding-top: 7px;
                        padding-left: 20px;
                        padding-bottom: 7px;
                        padding-right: 5px;
                        border-top-left-radius: 20px;
                        border-bottom-left-radius: 20px;
                    }
                    
                
                
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
                            padding: 20px;
                        }
                }
                ul a:hover{
                    background-color: #2F8083;
                    border-radius: 5px;
                }
        }
        .logistic-info{
            position:absolute;
            left: 68%;
            transform: translateY(+30%);
            color: white;
            width: 15%;
                .relative{
                    position: relative;
                    z-index: 999;
                    h1{
                        font-size: 65px;
                        &::before{
                            content: "";
                            position: absolute;
                            background-color: #3A6B6B;
                            height: 30px;
                            width: 70%;
                            top: 45px;
                            z-index: -1;
                            border-radius: 5px;
                            
                        }
                    }
                    
                    p{
                        font-size: 20px;
                    }
                }
                div{
                    
                        .btn-1{
                            background-color: #048383;
                            padding: 13px;
                            color: white;
                            border-radius: 7px;
                            border: none;
                            
                        }
                        .btn-2{
                            padding: 13px;
                            border-radius: 7px;
                            background-color: inherit;
                            color: white;
                            border: 2px solid #048383;
                        }
                    };
            }        
    }

</style>