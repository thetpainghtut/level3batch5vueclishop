<template>
  <Header title="About Page" subtitle="Say Something!"/>
  <div class="about">
    <h1>This is an about page</h1>
  </div>
</template>
<script>
import Header from '@/components/Header.vue';
  export default {
    name: "AboutView",
    components: { Header }
}
</script>