<template>
  <div class="applikation-container">

  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component({
  name: 'Applikation'
})
export default class Applikation extends Vue {


  mounted() {
    alert('hej');
  }
}
</script>
<style lang="scss" scoped>

</style>
