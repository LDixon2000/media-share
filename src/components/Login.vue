<template>
  <div class="login">
    <p>Hello</p>
    <form action=""><div class="row">
    <label for="username">Username</label>
    <input id="username" type="text" v-model="username" />
    </div>
    
    <div class="row">
    <label for="Password">Password</label>
    <input id="Password" type="text" v-model="password" />
    </div></form>
    
  </div>
</template>

<script>
export default {
  data() {
    return {
      username: "",
      password: ""
    };
  },
};
</script>

<style></style>
