<template>
  <div>
    <Row2Col/>
    <Timeline/>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import Row2Col from "~/components/Row2Col.vue";
import Timeline from "~/components/Timeline.vue";

export default Vue.extend({
  name: 'IndexPage',
  components: {Timeline, Row2Col},
})
</script>
