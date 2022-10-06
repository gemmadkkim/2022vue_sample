<template>

<HeaderView></HeaderView> 
<MainVisual></MainVisual>
  
</template>

<script>
// import DoRong from "./components/HelloWorld.vue"   //import

import HeaderView from "./components/HeaderView.vue"
import MainVisual from "./components/MainVisual.vue"

export default {
    components:{
        HeaderView,
        MainVisual
    }
}

// export default {
//   components:{ DoRong }     //등록
// }
</script>

<style>
*{margin: 0;padding: 0;}
ul,li{list-style: none;}
a:link,a:visited{text-decoration: none;color: #333;}

</style>