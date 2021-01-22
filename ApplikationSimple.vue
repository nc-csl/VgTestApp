<template>
  <p>{{ greeting }} World</p>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component({
  name: 'Applikation'
})
export default class Applikation extends Vue {
  private greeting = 'Hello3';
}
</script>

