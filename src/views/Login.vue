<template>
<div>
    <img class="markLogo" src="../assets/img/full_logo.jpg" alt="Crytocurrency eXchange Alliance">
  <div class="joinWrap">
    <h1><router-link to="/">CXA</router-link></h1>
    <div class="h2Wrap">
        <h2>login</h2>
        <span class="grLine"></span>
    </div>
    <form name="login" method="GET">
        <div>
            <label for="id">ID</label>
            <input type="text" name="id" id="id" required>
        </div>
        <div>
            <label for="pw">PW</label>
            <input type="password" name="pw" id="pw" required>
        </div>
        <button>login</button>
    </form>
    <div class="goToSignup">
        <p>Didn't you have?</p>
        <router-link to="/join">Create account</router-link>
    </div>
  </div>
</div>
</template>
<style lang="scss" scoped>

</style>
