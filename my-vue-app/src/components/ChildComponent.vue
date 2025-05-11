<script>
export default {
  methods: {
    triggerEvent() {
      this.$emit('custom-event', 'Halo dari komponen anak!')
    }
  }
}
</script>

<template>
  <div>
    <button @click="triggerEvent">Kirim Event ke Induk</button>
  </div>
</template>