<script >
import LogisticsServices from './LogisticsServices.vue';
import TheCompany from './TheCompany.vue' ;
import Logo from './Logo.vue';

export default{
    name: "AppMain",
    components:{
        LogisticsServices,
        TheCompany,
        Logo,
    }
}

</script>

<template>
    <section>
        <LogisticsServices/>
        <TheCompany/>
        <Logo/>
    </section>
</template>

<style lang="scss" scoped>
    
</style>