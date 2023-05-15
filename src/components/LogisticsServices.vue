<script >

export default{
    name: "LogisticsServices",
    
}

</script>

<template>
    <section>
        <div class="container d-flex ">
            <div class="services">
                <span>OUR BUSINESS AREAS</span>
                <h2>Logistics Services</h2>
                <p>We are leaders in providing logistics services with a set of cutting edge technologies and a team of experienced and renowned professionals.</p>
                <div>
                    <button class="me-3">Tradition</button>
                    <button>Quality</button>
                    <button class="ms-3">Security</button>
                </div>
                <div class="read-more">
                    <a href="/">
                        <button>READ MORE</button>
                    </a>
                </div>

            </div>
            <div class="cover-card">
                <div class="card" style="width: 18rem;">
                    <img src="../assets/img/gallery-3.jpg" class="card-img-top" alt="technology-logo">
                    <div class="card-body">
                        <h5 class="card-title">Techonlogy</h5>
                        <p class="card-text">Focused on developing technology solutions adapted to our client's needs.</p>
                    </div>
                </div>
            </div>
            <div class="cover-card">
                <div class="card" style="width: 18rem;">
                    <img src="../assets/img/gallery-5.jpg" class="card-img-top" alt="technology-logo">
                    <div class="card-body">
                        <h5 class="card-title">Transport</h5>
                        <p class="card-text">We develop operational strategies to improve logistical efficiency.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
    section{
        background-color: #e5ebe5;
            .container{
                width: 70%;
                justify-content: space-around;
                padding: 30px;
            }
            .services{
                width: 30%;
                padding: 10px;
                    span{
                        font-weight: 700;
                        color: #63B8C9;
                    }
                    h2{
                        font-size: 50px;
                        font-weight: 900;
                    }
                    p{
                        margin-top: 25px;
                    }
                    div{
                        margin-top: 40px;
                        display: flex;
                        
                            button{
                                padding: 8px;
                                border-radius: 4px;
                                border: none;
                                background-color: #CFE2DE;
                                color: #088181;
                                
                            }                        
                    }
                    .read-more a button{
                        background-color: #088181;
                        color: white;
                        
                    }
            }
            .cover-card{
                border: 30px solid white;
                background-color: white;
                border-radius: 5px;
                    .card{
                        border: none;
                    }
            }
    }
</style>