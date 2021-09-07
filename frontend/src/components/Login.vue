<template>
  <div class="login-form">
<form @submit.prevent="submitLogin">
    <div class="form-input">
      <input type="text" placeholder="användarnamn" id="username" class="input-user" >
      <input type="password" placeholder="xxxxx" id="password" class="input-pass" >

    
    </div>
    <button>logga in</button>

    
 </form>
 <button class="register-button" @click="movetoReg" >skapa konto</button>
    
  </div>
</template>

<script>
export default {
  data()
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
