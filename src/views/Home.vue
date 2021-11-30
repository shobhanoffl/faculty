<template>
<div class="home-wrap">
    <!-- <div class="home-title">Welcome Mr.John</div> -->
    <NewPostBar />
    <UsualPost />
    
</div>
</template>

<script>
import NewPostBar from '/fac/faculty/src/components/NewPostBar.vue'
import UsualPost from '/fac/faculty/src/components/UsualPost.vue';

const app = new Vue({
  el: '#home',
  components: {
    NewPostBar,UsualPost,
  }
});
</script>

<style>

</style>