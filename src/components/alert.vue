<template>
<div>
<div class="alert alert-success" role="alert">
<div v-if="$slots.title">
<slot name="title" :items="title">
</slot>
    <span>
        title
        24464664
    </span>
</div>
<slot name="text">  
</slot>
  <hr>
  <p class="mb-0">Whenever you need to, be sure to use margin utilities to keep things nice and tidy.</p>
</div>
    
</div>
</template>


<script >
export default{

    data:()=>({
     title:'hahahahaha'
    }),

    mounted(){
        this.$slots
    }
    }

</script>


<style lang="scss"> 


</style>