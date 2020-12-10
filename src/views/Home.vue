<template>
  <div class="home">
    <LoginPage />
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";
import LoginPage from "@/components/LoginPage.vue"; // @ is an alias to /src

export default defineComponent({
  name: "Home",
  components: {
    LoginPage,
  }
});
</script>
