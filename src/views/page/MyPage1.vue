<template>
  <div>
    <button class="btn btn-secondary" @click="buttonClick">button</button>

  </div>
</template>

<script>
export default {
    methods:{
        buttonClick:function(){
            console.log("buttonClick")
            //storeのmutation (setMyImage)
            this.$store.commit('setMyImage', 99)
        }
    }
}
</script>