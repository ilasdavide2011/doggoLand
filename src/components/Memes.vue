<template>
  <div class="bg-1">
    <div v-for="i in images" class="flex justify-center align-center">
      <img :src="i" class="my-3"/>
    </div>
  </div>
</template>
<script>
  var o = [];
  var imgsM = 48;
  for (let i = 0;i<imgsM;i++) {
    o.push("/images/memes/" + i + ".jpg");
  }
  
  console.log(o);
  export default {
    data() {
      return {
        images: o
      }
    }
  }
</script>
