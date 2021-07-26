<template>
  <div id="app">
    <b-navbar toggleable="lg" type="blue" variant="">
      <b-navbar-brand target="/">SISTEM INFORMASI MAHASISWA</b-navbar-brand>
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="ml-auto">
          <b-nav-item>
            <router-link to="/" class="nav-link">Beranda</router-link>
          </b-nav-item>
          <b-nav-item>
            <router-link to="/majors" class="nav-link">Jurusan</router-link>
          </b-nav-item>
          <b-nav-item>
            <router-link to="/students" class="nav-link">Mahasiswa</router-link>
          </b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
    <div class="container" style="padding-top: 80px">
      <router-view />
    </div>
  </div>
</template>

<script>
export default{
  
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: 	#078fff;

}
</style>