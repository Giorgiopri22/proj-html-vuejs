<script >

export default{
    name: "AppFooter",
}

</script>

<template>
    <section>
        <div class="box d-flex justify-content-between">
            <div class="card-box">
                <div class="my-5 p-5 contacts">
                    <span>Example Inc.</span>
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
            <div class="card-cover my-5 p-5">
                <div>
                    <h3>About</h3>
                    <ul>
                        <li class="d-flex align-items-center             justify-content-center">
                            <i class="fa-solid fa-chevron-right me-2"></i>
                            <span>The Company</span>
                        </li>
                        <li class="d-flex align-items-center             justify-content-center">
                            <i class="fa-solid fa-chevron-right"></i>
                            <span>The Company</span>
                        </li>
                        <li class="d-flex align-items-center             justify-content-center ">
                            <i class="fa-solid fa-chevron-right"></i>
                            <span>The Company</span>
                        </li>
                        <li class="d-flex align-items-center             justify-content-center">
                            <i class="fa-solid fa-chevron-right"></i>
                            <span>The Company</span>
                        </li>
                        <li class="d-flex align-items-center             justify-content-center">
                            <i class="fa-solid fa-chevron-right"></i>
                            <span>The Company</span>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="card-cover my-5 p-5">
                <div>
                    <h3>About</h3>
                    <ul>
                        <li class="d-flex align-items-center justify-content-center">
                            <i class="fa-solid fa-chevron-right"></i>
                            <span>The Company</span>
                        </li>
                        <li class="d-flex align-items-center justify-content-center">
                            <i class="fa-solid fa-chevron-right"></i>
                            <span>The Company</span>
                        </li>
                        <li class="d-flex align-items-center justify-content-center ">
                            <i class="fa-solid fa-chevron-right"></i>
                            <span>The Company</span>
                        </li>
                        <li class="d-flex align-items-center justify-content-center">
                            <i class="fa-solid fa-chevron-right"></i>
                            <span>The Company</span>
                        </li>
                        <li class="d-flex align-items-center justify-content-center">
                            <i class="fa-solid fa-chevron-right"></i>
                            <span>The Company</span>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="card-cover my-5 p-5">
                <div>
                    <h3>About</h3>
                    <ul>
                        <li class="d-flex align-items-center             justify-content-center">
                            <i class="fa-solid fa-chevron-right"></i>
                            <span>The Company</span>
                        </li>
                        <li class="d-flex align-items-center             justify-content-center">
                            <i class="fa-solid fa-chevron-right"></i>
                            <span>The Company</span>
                        </li>
                        <li class="d-flex align-items-center             justify-content-center ">
                            <i class="fa-solid fa-chevron-right"></i>
                            <span>The Company</span>
                        </li>
                        <li class="d-flex align-items-center             justify-content-center">
                            <i class="fa-solid fa-chevron-right"></i>
                            <span>The Company</span>
                        </li>
                        <li class="d-flex align-items-center             justify-content-center">
                            <i class="fa-solid fa-chevron-right "></i>
                            <span>The Company</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
section{
    height: 900px;
    background-image: url('../assets/img/bg-10.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
        .box{
            width: 68%;
            margin: 0 auto;
                .card-box{
                    width: calc(100% / 4 - 15px);
                    color: white;
                        button{
                            width: 70%;
                            color: white;
                            background-color: inherit;
                            border-radius: 4px;
                            padding: 7px;
                            border: 1px solid #2B7477;
                        }                    
                }
        }
        .card-cover{
            border: 1px solid red;
            border-radius: 10px;            
                ul{
                    list-style-type: none;
                }
            }

}
</style>