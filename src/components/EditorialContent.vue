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
                <div class="d-flex my-4">
                    <h2 class="me-1 not-special">Latest</h2>
                    <h2 class="special">News</h2>
                </div>
            </div>
            <div class="d-flex justify-content-between align-items-center">
                <p>Every week we publish content about what is the best in the business world.</p>
                <button>SEE ALL</button>
            </div>
            <div class="my-card my-4">
                <div class="position-relative ">
                    <img class="img-card" src="../assets/img/news-1.jpg" alt="">
                    <p>Increasing creativity is possible for everyone</p>
                </div>
                <div class="position-relative ">
                    <img class="img-card" src="../assets/img/news-2.jpg" alt="">
                    <p>Because market research is part of the business plan</p>
                </div>
                <div class="position-relative ">
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
            color: #48A6A8;
            font-weight: 700;
        }
        .special{
            background-color: #DCEBED;
            padding: 10px;
            border-radius: 3px;
            color: #2F8083;
            font-weight: bold;
        }
        .not-special{
            padding: 10px;
            font-weight: bold;
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
            &:hover{
                transition: 1s ease ;
                transform: scale(1.1);
                background-color: white;
                color: #2F8083;
                border: 1px solid #2F8083;
            }
        }
        .my-card{
            display: flex;
            justify-content: space-between;
            text-align: center;

                div{
                    width: calc(100% / 3 - 10px);
                    border-radius: 10px;
                    &:hover{
                        transition: 1s ease ;
                        transform: scale(1.1);
                        box-shadow: 0 3px 30px white;
                        z-index: 2;
                    }
                        img{
                            width: 100%;
                            border-radius: 10px;
                            filter: brightness(40%);
                        }
                        p{
                            position: absolute;
                            bottom: 50px;
                            color: white;
                            left:20px;
                            right: 20px;
                            font-size: 25px;
                        }
                        
                }
        }
}


</style>