<template>
  <div>
    <div class="bg-neutral-400 flex items-center place-content-around">

      <ul class="px-2 py-4  justify-start">
        <li class="px-2 logo_1 justify-start">
          <a href="#"><img src="rajveer.png" /></a>
        </li>
      </ul>
      <ul class="text-black flex justify-end gap-7">
        <li class="px-2 font-semibold"><a href="#">Home</a></li>
        <li class="px-2 font-semibold"><a href="#">Works</a></li>
        <li class="px-2 font-semibold"><a href="#">Skill's</a></li>
        <li class="px-2 font-semibold"><a href="#">Eduction</a></li>
        <!-- <li class="px-2"><a href="#">FAQs</a></li> -->
        <li class="px-2 font-semibold"><a href="#">Contect</a></li>
        <li class="px-2 font-semibold brand"><a href="#"></a></li>
      </ul>

    </div>
  </div>
</template>

<script>
export default {
  name: 'navbar',
}
</script>
<style >
/* .right_shift{
  align-items: center;
}*/
.logo_1 {
  display: inline-block;
  vertical-align: top;
  /* margin-left: 225px; */
  width: 50px;
  /* height: 50px; */
}

li {
  display: inline;
}
</style>
