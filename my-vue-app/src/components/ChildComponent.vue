<script>
export default {
}
</script>

<template>
  <div class="card">
    <!-- Named slot -->
    <div class="card-header">
      <slot name="header">
        <h3>Header Default</h3>
      </slot>
    </div>
    
    <!-- Default slot -->
    <div class="card-body">
      <slot>
        <p>Tidak ada konten yang disediakan.</p>
      </slot>
    </div>
    
    <!-- Named slot -->
    <div class="card-footer">
      <slot name="footer">
        <small>Footer Default</small>
      </slot>
    </div>
  </div>
</template>
