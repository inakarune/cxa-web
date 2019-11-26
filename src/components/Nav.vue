<template>
<div class="headerWrap">
    <div class="header">
        <h1 id="h1"><a href="#">CXA</a></h1>
        <div class="joinUs"><router-link to="/login">join</router-link></div><!--//.joinUs-->
        <div class="navWrap">
            <a class="menuImg" href="#"></a>
            <ul class="nav">
                <li><a href="#article1">About</a></li>
                <li><a href="#article2">Buisness</a></li>
                <li><a href="#article2_1">Alliance</a></li>
                <li><a href="#article3">Roadmap</a></li>
                <li><a href="#article4">Contact</a></li>
                <li><router-link to="/login">join us</router-link></li>
            </ul>
        </div><!--//.navWrap-->
    </div><!--//.header-->
</div><!--//.headerWrap-->
</template>
<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class Nav extends Vue {
 
}
</script>
<style lang="scss">

</style>
