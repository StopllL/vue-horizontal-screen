<template>
    <div>
        <div>this is template body</div>
    </div>
</template>
<style>

</style>
<script>
    export default{
        data(){
            return{
                msg:'hello vue'
            }
        },
        activated(){
            this.$store.commit({
                type:'isLoadingHandler',
                amount:false
            });
        },
        components:{
        }
    }
</script>
