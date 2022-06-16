<script>
import { defineComponent } from 'vue';
import PlanRIco from '@/plan-r-ico.vue';

export default defineComponent({
  name: 'ServeDev',
  components: {
    PlanRIco
  }
});
</script>

<template>
  <div id="app">
    <plan-r-ico class-icon="Up"/>
  </div>
</template>
