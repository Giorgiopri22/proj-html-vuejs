<script >

export default{
    name: "AppHeader",
}

</script>

<template>
    <header>
        <div class="bg-info">
            <section class="d-flex justify-content-between">
                <div>
                    <i class="fa-solid fa-clock"></i>
                    <span>Open Hours: Mon-Sat -9:00-18:00</span>
                </div>
                <div class="info-social">
                    <div>
                        <i class="fa-solid fa-phone"></i>
                        <span>+1(305)1234-5678</span>
                        <i class="fa-solid fa-envelope"></i>
                        <span>hello@example.com</span>
                    </div>
                </div>
                <div>
                    <i class="fa-brands fa-facebook"></i>
                    <i class="fa-brands fa-twitter"></i>
                    <i class="fa-brands fa-linkedin-in"></i>
                </div>
                
            </section>
        </div>
    </header>
</template>

<style lang="scss" scoped>

.bg-info{   
background-color: #230929;    
    section{
        width: 70%;
        margin: 0 auto;
        padding: 15px;
    }
}


</style>