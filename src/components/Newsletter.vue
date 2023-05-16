<script >

export default{
    name: "Newsletter",
}

</script>

<template>
    <section>
        <div class="container">
            <div>
                <div class="my-3 p-4">
                    <span>
                        NEWSLETTER
                    </span>
                    <div class="d-flex my-2">
                        <h2 class="me-1 special">Know</h2>
                        <h2 class="not-special">First</h2>
                    </div>
                    <p>
                        Follow closely and receive content about our company and the news of the current market.
                    </p>
                </div>
            </div>
            <div>
                <div class="my-4">
                    <input type="text" placeholder="   Name">
                </div>
                <div class="my-4">
                    <input type="e-mail" placeholder="   Email">
                </div>
                <button>SUBSCRIBE</button>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
section{
    background-image: url("../assets/img/bg-1.jpg");    
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
        .container{
            width: 80%;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 100px;
                div{
                    width: 85%;    
                        span{
                            color: #048383;
                            font-weight: 700;
                        }
                        .special{
                            background-color: #1C3238;
                            padding: 10px;
                            border-radius: 3px;
                            color: #FFFFFF;
                            font-size: 40px;
                        }
                        .not-special{
                            padding: 10px;
                            color: #FFFFFF;
                            font-size: 40px;
                        }                 
                        p{
                            color: white;
                        }
                }
                input{
                    width:100%;
                    border-radius: 3px;
                    opacity: 0.6;
                    height: 40px;
                    border: none;
                }
                button{
                    color: white;
                    background-color: #048383;
                    padding: 8px;
                    width: 20%;
                    border-radius: 4px;
                    border: none;
                }
        }
}
</style>