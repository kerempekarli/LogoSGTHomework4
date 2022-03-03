<template>

    <div>
        <div id="page-top">

        <WrapperComponent/>

        <ScrollComponent/>

        <LogoutComponent/>


        </div>
    </div>


</template>

<script>
    import ScrollComponent from "./Components/ScrollComponent.vue"
    import WrapperComponent from "./Components/WrapperComponent.vue" 
    import LogoutComponent from "./Components/LogoutComponent.vue"
    export default {
        components :{
            ScrollComponent,
            WrapperComponent,
            LogoutComponent
        }
    }
</script>


