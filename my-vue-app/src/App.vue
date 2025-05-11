<script>
import ChildComponent from './components/ChildComponent.vue'


export default {
  components: {
    ChildComponent
  },
  methods: {
    handleChildEvent(data) {
      alert('Event dari anak diterima dengan data: ' + data)
    }
  }
}
</script>

<template>
  <div>
    <h1>Komponen Induk</h1>
    <ChildComponent @custom-event="handleChildEvent" />
  </div>
</template>