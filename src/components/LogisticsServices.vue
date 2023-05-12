<script >

export default{
    name: "LogisticsServices",
    
}

</script>

<template>
    <section>
        <div class="container d-flex">
            <div class="services">
                <span>OUR BUSINESS AREAS</span>
                <h2>Logistics Services</h2>
                <p>We are leaders in providing logistics services with a set of cutting edge technologies and a team of experienced and renowned professionals.</p>
                <button>Tradition</button>
                <button>Quality</button>
                <button>Security</button>
                <div>
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
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                    </div>
                </div>
            </div>
            <div class="cover-card">
                <div class="card" style="width: 18rem;">
                    <img src="../assets/img/gallery-5.jpg" class="card-img-top" alt="technology-logo">
                    <div class="card-body">
                        <h5 class="card-title">Transport</h5>
                        <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
    section{
        background-color: #edf4ec;
            .container{
                width: 70%;
                justify-content: space-around;
                padding: 30px;
            }
            .services{
                width: 30%;
            }
            .cover-card{
                background-color: white;
            }
    }
</style>