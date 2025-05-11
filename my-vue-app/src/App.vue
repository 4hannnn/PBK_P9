<script>
import ChildComponent from './components/ChildComponent.vue'

export default {
  components: {
    ChildComponent
  }
}
</script>

<template>
  <div>
    <h1>Ini Komponen Induk</h1>
    <ChildComponent />
  </div>
</template>