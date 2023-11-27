<template>
    <nav>
        <h1>Header</h1>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav>
    <router-view/>
  </template>


<script>
export default {
    name: 'WebHeader',
}
</script>
