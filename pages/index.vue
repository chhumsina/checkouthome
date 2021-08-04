<template> 
<div>
<h2>HTML Iframes</h2>
<p>You can use the height and width attributes to specify the size of the iframe:</p>

<button @click="open=true">Open</button>

<iframe v-if="open" src="https://checkoutiii-chhumsina.vercel.app/"  class="iframe" title="Iframe Example"></iframe>

</div>
</template>

<script>
export default {
  data(){
    return {
open: false,
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