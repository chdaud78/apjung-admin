<template>
  <div class="login">
    <form action="">
      <label for="uId">아이디</label>
      <input type="text" id="uId" >
      <label for="uPw">비밀번호</label>
      <input type="text" id="uPw">
    </form>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "LoginPage",
  props: {

  },
  computed: {

});
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
</style>
