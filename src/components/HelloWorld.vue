<template>
<div>Capacity: {{capacity}}</div>
</template>

<script lang="ts">

export default {
  props: {
    name: String
  },
  setup(name: string, context) {
      // eslint-disable-next-line no-console
      console.log(name, context);
  }
}

</script>
