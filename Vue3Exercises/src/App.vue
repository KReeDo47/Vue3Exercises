<script>
  export default {
    data() {
      return {
        text: 'page',
        href: 'page.html',
      }
    }
  }
</script>

<template>
  <div class="body">
    <div class="main"> 
      <a :href="page">Tap here)</a>
    </div>
  </div>    
</template>

