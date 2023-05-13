<script >

export default{
    name: "Logo",
    
}

</script>

<template>
    <section >
        <div class="d-flex">
            <div>
                <img class="img-special" src="../assets/img/logo-5.png" alt="">
            </div>
            <div>
                <img src="../assets/img/logo-1.png" alt="">
            </div>
            <div>
                <img src="../assets/img/logo-2.png" alt="">
            </div>
            <div>
                <img src="../assets/img/logo-3.png" alt="">
            </div>
            <div>
                <img src="../assets/img/logo-4.png" alt="">
            </div>
            <div>
                <img class="img-special"  src="../assets/img/logo-5.png" alt="">
            </div>
        </div>
        
    </section>
</template>

<style lang="scss" scoped>
    section{
        background-color: #e5ebe5;        
            div{
                width: 55%;
                justify-content: space-between;
                margin: 0 auto;
                text-align: center;
                height: 200px;
                    div{
                        justify-content: center;
                        align-items: center;
                        display: flex;
                            img{
                                width: 40%;
                            }
                            .img-special{
                                width: 25%;
                            }                            
                    }
                    
            }        
    }
</style>