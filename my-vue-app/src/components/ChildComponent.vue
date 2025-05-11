<script>
export default {
  props: {
    message: {
      type: String,
      required: true
    }
  }
}
</script>

<template>
  <div>
    <p>Pesan yang diterima: {{ message }}</p>
  </div>
</template>