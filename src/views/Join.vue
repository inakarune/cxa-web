<template>
<div>
    <img class="markLogo" src="../assets/img/full_logo.jpg" alt="Crytocurrency eXchange Alliance">
  <div class="joinWrap">
    <h1><router-link to="/">CXA</router-link></h1>
    <div class="h2Wrap">
        <h2>Join</h2>
        <span class="grLine"></span>
    </div>
    <form name="signUp" method="GET">
        <div>
            <label class="label-helper" for="name">name</label>
            <input type="text" name="name" id="name" required>
        </div>
        <div>
            <label class="label-helper" for="pw">PW</label>
            <input type="password" name="pw" id="pw" required>
        </div>
        <div>
            <label class="label-helper" for="re_pw">Re_PW</label>
            <input type="password" name="re_pw" id="re_pw" required>
        </div>
        <div>
            <label class="label-helper" for="email">E-Mail</label>
            <input type="email" name="email" id="email" required>
        </div>
        <div>
            <label class="label-helper" for="tel">Tel</label>
            <input type="tel" name="tel" id="tel" required>
        </div>
        <button>Sign Up</button>
    </form>
  </div>  
</div> 
</template>
<style lang="scss" scoped>

</style>