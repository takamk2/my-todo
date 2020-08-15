<template>
  <p>{{ text }}</p>
</template>

<script>
export default {
  name: 'Sample',
  props: {
    text: {
      type: String,
      required: true,
    },
  },
}
</script>

<style scoped></style>
