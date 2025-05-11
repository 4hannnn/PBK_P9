<script>
import ChildComponent from './components/ChildComponent.vue'

export default {
  components: {
    ChildComponent
  },
  data() {
    return {
      parentMessage: 'Pesan dari induk'
    }
  }
}
</script>

<template>
  <div>
    <h1>Komponen Induk</h1>
    <ChildComponent :message="parentMessage" />
  </div>
</template>