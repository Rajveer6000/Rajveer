<template>
<div>
    <Navbar/>
  <p>  hello rajveer </p>
</div>
</template>

<script lang="ts">
import Vue from 'vue'
import Navbar from '~/components/navbar.vue';

export default Vue.extend({
    name: "about",
    components: { Navbar }
})
</script>


<style >
template {
  font-family: 'Helvetica Now', sans-serif;
}
</style>