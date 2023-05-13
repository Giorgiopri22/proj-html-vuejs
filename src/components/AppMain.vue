<script >
import LogisticsServices from './LogisticsServices.vue';
import TheCompany from './TheCompany.vue' ;
import Logo from './Logo.vue';
import EditorialContent from './EditorialContent.vue';
import Newsletter from './Newsletter.vue';
import Form from './Form.vue'; 

export default{
    name: "AppMain",
    components:{
        LogisticsServices,
        TheCompany,
        Logo,
        EditorialContent,
        Newsletter,
        Form,
    }
}

</script>

<template>
    <section>
        <LogisticsServices/>
        <TheCompany/>
        <Logo/>
        <EditorialContent/>
        <Newsletter/>
        <Form/>
    </section>
</template>

<style lang="scss" scoped>
    
</style>