<script >

export default{
    name: "Form",
}

</script>

<template>
    <section>
        <div class="box d-flex justify-content-around">
            <div class="my-5 p-4 form">
                <span>
                    SEND A MESSAGE
                </span>
                <div class="d-flex">
                    <h2 class="normal">
                        Get in 
                    </h2>
                    <h2 class="ms-2 special">
                        Touch
                    </h2>
                </div>
                <p class="mt-2">
                    We will respond to your message as soon as possible.
                </p>
                <div class="my-5">
                    <div class="my-3">
                        <input class="me-2 p-1 form-size" type="text" placeholder="  Name">
                        <input class="p-1 form-size" type="email" placeholder="  Email">
                    </div>
                    <div class="my-3">
                        <input class="me-2 p-1 form-size" type="number" placeholder="  Phone">
                        <select class="p-1 form-size"  name="" id="">
                            <option selected value="">More Info</option>
                        </select>
                    </div>
                    <div>
                        <textarea name="" id="text-area" placeholder="  Message"></textarea>
                    </div>
                    <div class="my-3">
                        <button>SEND</button>
                    </div>
                </div>
            </div>

            <div class="my-5 p-5 contacts">
                <span>Example Inc.</span>
                <p class="my-2">
                    Lorem ipsum dolor, sit amet consectetur adipisicing elite.
                </p>
                <p>
                    Praesent diam lacus,dapibus sed imperdiet consectetur.
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
                    <button>VIEW MAP</button>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
section{
    background-color: #e5ebe5;
    .box{
        width: 70%;
        margin: 0 auto;
            .form{
                width: 70%;
                ::placeholder{
                    color: #000000;
                }
                span{
                    color: #45A5A6;
                    font-weight: 700;
                }
                
                .form-size{
                    width: 40%;
                    border: none;
                    border-radius: 5px;
                    background-color: #DDE2DB;
                    
                }
                #text-area{
                    width: 81%;
                    height: 150px;
                    border: none;
                    border-radius: 5px;
                    background-color: #DDE2DB;
                    
                    
                }
                button{
                    padding: 7px;
                    width: 8%;
                    border: none;
                    border-radius: 5px;
                    color: white;
                    background-color: #088181;
                }
                .special{
                    background-color: #CFE2DE;
                    color: #2F8083;
                    padding: 7px;
                    border-radius: 6px;
                    font-weight: 900;
                }
                .normal{
                    padding: 7px;
                    font-weight: 900;
                }
            }
            .contacts{
                width: 25%;
                    .cerchio{
                        border-radius: 50%;
                        background-color: #CFE2DE;
                        width: 40px;
                        height: 40px;
                        display: flex;
                        align-items: center;
                        justify-content: center;
                       
                        i{
                            color: #338184;
                        }
                    }
                    button{
                        padding: 7px;
                        width: 35%;
                        border: 1px solid #35808F;
                        color: #73878E;
                        border-radius: 5px;
                    }   
                }
        }
}
</style>