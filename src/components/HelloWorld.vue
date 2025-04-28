<template>
  <h1>Hello World!</h1>
  <p>Welcome to your Vue.js application.</p>
  <p><a href="/support" class="support-link">View MedDocs Support Page</a></p>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'HelloWorld',
});
</script>

<style scoped>
h1 {
  color: #42b983;
}
.support-link {
  display: inline-block;
  margin-top: 20px;
  padding: 10px 20px;
  background-color: #42b983;
  color: white;
  text-decoration: none;
  border-radius: 4px;
  font-weight: bold;
  transition: background-color 0.3s;
}
.support-link:hover {
  background-color: #3aa876;
}
</style>