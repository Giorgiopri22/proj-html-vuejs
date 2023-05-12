<script >

export default{
    name: "TheCompany",
    
}

</script>

<template>
    <section class="d-flex">
        <div class="about-company">
            <div>
                <span>
                    ABOUT THE NETWORK
                </span>
                <h2>The Company</h2>
                <p>With all of this expertise and capability comes an unrivalled commitment to customer service.</p>
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
            background-color: #121117;
            width: 50%;
            color: white;
                div{
                    width: 50%;
                    margin-left: 80px;
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