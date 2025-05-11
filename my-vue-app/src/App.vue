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
    <h1>Komponen Induk</h1>
    
    <!-- Slot Default -->
    <ChildComponent>
      <p>Ini adalah konten yang dimasukkan melalui slot.</p>
    </ChildComponent>
    
    <!-- Named Slots -->
    <ChildComponent>
      <template #header>
        <h3>Ini adalah judul</h3>
      </template>
      
      <template #default>
        <p>Ini adalah konten utama</p>
      </template>
      
      <template #footer>
        <small>Ini adalah footer</small>
      </template>
    </ChildComponent>
  </div>
</template>