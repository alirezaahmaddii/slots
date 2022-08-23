<template>
<div class="container">
<Alert>
  <template #title="aa">
      <h2>hello </h2>
  <span>{{aa.items}}</span>

</template>
  <template #text>

<p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Obcaecati cumque repellat ipsum commodi, tenetur cupiditate? Itaque provident sed incidunt, eveniet sint natus eos at minus doloremque atque. Atque, tempore saepe?  </p>

</template>
</Alert>

</div>

</template>



<script>
import Alert from "./components/alert.vue";

export default{
  components:{
    Alert
  }
}


</script>


<style lang="scss">

</style>