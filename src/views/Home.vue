<template>
  <div class="fruits">
    <FruitList></FruitList>
  </div>
</template>

<script>
// @ is an alias to /src
import FruitList from '@/components/FruitList.vue';

export default {
  name: 'Home',
  components: {
    FruitList,
  },
};
</script>
