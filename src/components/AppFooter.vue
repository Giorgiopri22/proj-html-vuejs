<script >

export default{
    name: "AppFooter",
}

</script>

<template>
    <section>
        <div class="box d-flex justify-content-between align-items-center p-5">
            <div class="card-box my-5 p-5">
                <div class=" contacts">
                    <div class="mb-3">
                        <span class="special"><strong>N E X</strong></span>
                        <span><strong> G E N</strong></span>
                    </div>
                    <p class="my-2">
                        A Functional HTML Template for Corporate & Business.
                    </p>
                    <div class="d-flex my-3 align-items-center">
                        <div class="me-2 cerchio">
                            <i class="fa-solid fa-phone"></i>
                        </div>
                        <div>
                            <span>+1 (305) 1234-5678</span>
                        </div>
                    </div>
                    <div class="d-flex my-3 align-items-center">
                        <div class="me-2 cerchio">
                            <i class="fa-solid fa-envelope"></i>
                        </div>
                        <div>
                            <span>hello@example.com</span>
                        </div>
                    </div>
                    <div class="d-flex my-3 align-items-center">
                        <div class="me-2 cerchio">
                            <i class="fa-solid fa-location-dot"></i>
                        </div>
                        <div>
                            <span>Main Avenue, 987</span>
                        </div>
                    </div>
                    <div>
                        <button class="my-3">GET IN TOUCH</button>
                    </div>
                </div>
            </div>
            <div class="card-cover my-3 p-5">
                <div>
                    <h3>About</h3>
                    <ul>
                        <li class="d-flex align-items-center ">
                            <i class="fa-solid fa-chevron-right me-2"></i>
                            <span>The Company</span>
                        </li>
                        <li class="d-flex align-items-center ">
                            <i class="fa-solid fa-chevron-right me-2"></i>
                            <span>Institutional</span>
                        </li>
                        <li class="d-flex align-items-center  ">
                            <i class="fa-solid fa-chevron-right me-2"></i>
                            <span>Social & Events</span>
                        </li>
                        <li class="d-flex align-items-center ">
                            <i class="fa-solid fa-chevron-right me-2"></i>
                            <span>Innovation</span>
                        </li>
                        <li class="d-flex align-items-center ">
                            <i class="fa-solid fa-chevron-right me-2"></i>
                            <span>Environment</span>
                        </li>
                        <li class="d-flex align-items-center ">
                            <i class="fa-solid fa-chevron-right me-2"></i>
                            <span>Technology</span>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="card-cover my-3 p-5">
                <div>
                    <h3>Transport</h3>
                    <ul>
                        <li class="d-flex align-items-center ">
                            <i class="fa-solid fa-chevron-right me-2"></i>
                            <span>Industrialized</span>
                        </li>
                        <li class="d-flex align-items-center ">
                            <i class="fa-solid fa-chevron-right me-2"></i>
                            <span>Chemicals</span>
                        </li>
                        <li class="d-flex align-items-center  ">
                            <i class="fa-solid fa-chevron-right me-2"></i>
                            <span>Packaged Liquids</span>
                        </li>
                        <li class="d-flex align-items-center ">
                            <i class="fa-solid fa-chevron-right me-2"></i>
                            <span>Construction</span>
                        </li>
                        <li class="d-flex align-items-center ">
                            <i class="fa-solid fa-chevron-right me-2"></i>
                            <span>Laminated Wood</span>
                        </li>
                        <li class="d-flex align-items-center ">
                            <i class="fa-solid fa-chevron-right me-2"></i>
                            <span>And Others</span>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="card-cover my-3 p-5">
                <div>
                    <h3>Support</h3>
                    <ul>
                        <li class="d-flex align-items-center">
                            <i class="fa-solid fa-chevron-right me-2"></i>
                            <span>Responsibility</span>
                        </li>
                        <li class="d-flex align-items-center">
                            <i class="fa-solid fa-chevron-right me-2"></i>
                            <span>Term of Use</span>
                        </li>
                        <li class="d-flex align-items-center ">
                            <i class="fa-solid fa-chevron-right me-2"></i>
                            <span>About Cookies</span>
                        </li>
                        <li class="d-flex align-items-center">
                            <i class="fa-solid fa-chevron-right me-2"></i>
                            <span>Privacy Policy</span>
                        </li>
                        <li class="d-flex align-items-center">
                            <i class="fa-solid fa-chevron-right me-2"></i>
                            <span>Accessibility</span>
                        </li>
                        <li class="d-flex align-items-center">
                            <i class="fa-solid fa-chevron-right me-2"></i>
                            <span>Information</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
    <div id="credits">
        <div class="box-2 d-flex justify-content-between">
            <span>
                Enjoy the low price. We are tracking any intention of piracy.
            </span>
            <div>
                <i class="fa-regular fa-copyright"></i>
                <span>
                    2020 NEXGEN is Proudly Powered by <span id="coding">Codings</span>
                </span>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
section{
    
    background-image: url('../assets/img/bg-10.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    background-position:center;
        .box{
            width: 68%;
            margin: 0 auto;
                .card-box{
                    width: calc(100% / 4 - 15px);
                    color: #C0C3D0;
                    padding: 10px;
                        button{
                            width: 70%;
                            color: white;
                            background-color: inherit;
                            border-radius: 4px;
                            padding: 7px;
                            border: 1px solid #2B7477;
                            &:hover{
                                transition: 1s ease ;
                                transform: scale(1.1);
                                background-color: white;
                                color: #2F8083;
                                border: 1px solid #2F8083;
                            }
                        }
                        .special{
                        color: #3DA4A6;
                        background-color: #1D3237;
                        padding-top: 7px;
                        padding-left: 20px;
                        padding-bottom: 7px;
                        padding-right: 5px;
                        border-top-left-radius: 20px;
                        border-bottom-left-radius: 20px;
                    }                    
                }
        }
        .card-cover{
            border-radius: 10px;
            background-color: rgba(255, 255, 255, 0.06);
                h3{
                    color: #F9F9F9;
                }            
                ul{
                    list-style-type: none;
                    color: #9A9A94;
                    padding: 0;
                        li{
                            padding: 5px;
                            &:hover{
                                color: crimson;
                            }
                        }
                }
            }

}
#credits{
    background-color: #0D0D11;
    padding: 15px;
        .box-2{
            width: 65%;
            margin: 0 auto;
            padding-top: 20px;
            color: #8F8981;
                #coding{
                    color: #246272;
                }
        }
}
</style>