<template>
  <main>
    <h1>Hello world!</h1>
    <NuxtLink to="/fun">
      Go to fun page.
    </NuxtLink>
    <Sample text="こんにちわ！" />
  </main>
</template>

<script>
import Sample from '../components/Sample'
export default {
  name: 'Index',
  components: { Sample },
}
</script>

<style scoped></style>
