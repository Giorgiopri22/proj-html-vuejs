<script >

export default{
    name: "EditorialContent",
}

</script>

<template>
    <section>
        <div class="container">
            <div class="my-3">
                <span>
                    OUR EDITORIAL CONTENT
                </span>
                <h2>
                    Latest News
                </h2>
            </div>
            <div class="d-flex justify-content-between align-items-center">
                <p>Every week we publish content about what is the best in the business world.</p>
                <button>SEE ALL</button>
            </div>
            <div class="my-card my-4">
                <div class="position-relative">
                    <img class="img-card" src="../assets/img/news-1.jpg" alt="">
                    <p>Increasing creativity is possible for everyone</p>
                </div>
                <div class="position-relative">
                    <img class="img-card" src="../assets/img/news-2.jpg" alt="">
                    <p>Because market research is part of the business plan</p>
                </div>
                <div class="position-relative">
                    <img class="img-card" src="../assets/img/news-3.jpg" alt="">
                    <p>Working from home is now a trend</p>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
.container{
    width: 90%;
        span{
            color: #048383;
            font-weight: 700;
        }
        h2{
            font-weight: 900;
            font-size: 40px;
        }
        p{
            line-height: 25px;
            
        }
        button{
            padding: 8px;
            border-radius: 7px;
            color: white;
            background-color: #2F8083;
            border: none;
            width: 8%;
        }
        .my-card{
            display: flex;
            justify-content: space-between;
            text-align: center;
                div{
                    width: calc(100% / 3 - 10px);
                        img{
                            width: 100%;
                            border-radius: 10px;
                            filter: brightness(40%);
                        }
                        p{
                            position: absolute;
                            bottom: 40px;
                            color: white;
                            left:20px;
                            right: 20px;
                            font-size: 30px;
                        }
                        
                }
        }
}


</style>