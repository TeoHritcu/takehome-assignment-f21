<template>
  <!-- PART 4: Add your code here -->
  <div>
    <p>
      {{name}}
    </p>
    <Counter count="episodes_seen"/>
  </div>
</template>

<script>
// PART 4: Add your code here

// I GOT STUCK HERE I'M STILL TRYING TO UNDERSTAND HOW TO CORRECTLY UTILISE PROPS
import Instructions from "./Instructions.vue";
import Counter from "./Counter.vue";

export default {
  props:[
    'id',
    'name',
    'episodes_seen'
  ]
};
</script>

<style>
</style>
