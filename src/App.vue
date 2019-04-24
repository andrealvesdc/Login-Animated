<template>
  <div id = "login">
      <login />


  </div>

  
</template>

<script>
import Login from "./main/Login"


export default {
  components: { Login }

}
</script>

<style>

body {
  margin: 0;
}

#login {
  display: flex;
  flex-direction: column;
  height: 100vh;
  justify-content: center;
  align-items: center;
  text-align: center;

  color: rgb(255, 255, 255);
  background: rgb(34, 130, 175)

}
</style>

