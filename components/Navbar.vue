<template>
  <div>
    <b-nav>
      <b-nav-item active><NuxtLink to="/"> Home </NuxtLink></b-nav-item>
      <b-nav-item><NuxtLink to="/profil"> Profil </NuxtLink></b-nav-item>
      <b-nav-item><NuxtLink to="/einstellungen"> Einstellungen </NuxtLink></b-nav-item>
    </b-nav>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style>
</style>