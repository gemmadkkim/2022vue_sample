<template>
  <div class="container">
    <ul class="d_icon">
        <li v-for="item in data" :key="item">
            <a :href="item.href">
                <img :src="`images/directs/${item.src}`" alt="">
                <div class="txt">
                    {{item.name}}
                </div>
            </a>

        </li>
        <!-- <li v-for="item in directs" :key="item">
            <a :href="item.href">
                <img :src="`../images/directs/${item.src}`" alt="">
                <div class="txt">
                    {{item.name}}
                </div>
            </a>
        </li> -->
    </ul>
  </div>
</template>

<script>

    export default {
        props:["data"],
        data(){
            return{

            }
        }

    }
</script>

<style lang="scss">
    .d_icon{
        display: flex;
        gap:20px;
        li{

        }
        img{
            width: 100%;
        }
        .txt{
            text-align: center;
        }
    }
</style>