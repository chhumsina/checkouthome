<template> 
<div>
<h2>HTML Iframes</h2>
<p v-for="(i, index) in 100" :key="index"> {{index}} - You can use the height</p>
<button style="position:fixed; bottom:0;">save</button>
</div>
</template>

<script>
export default {
  data(){
    return {
open: false,
    }
  },
  methods:{
    opens(){
      this.open = !this.open
    }
  }
}
</script>

<style>
.iframe{
  top: 0;
  left: 0;
  position: absolute;
  width:100%; height: 100%;
}
</style>