<script>
import MainHeader from '../src/components/MainHeader.vue'
export default {
  components: { MainHeader },
  data() {
    return {}
  }
}
</script>

<template>
  <main>
    <header>
      <MainHeader />
    </header>
    <RouterView />
  </main>
</template>
