<template>
  <v-container>
    <v-row class="text-center">  
     <div class="settingAddress">
      <span class="setAddressBtn" @click="setAddress">현재 주소</span>
    </div>
    </v-row>
 </v-container>
</template>

<script>
export default {
  methods: {
    setAddress() {
      // this.$emit("removeAll");
      this.$store.commit('현재 주소');
    },
  },
};
</script>

<style scoped>
.settingAddress {
  width: 10rem;
  height: 50px;
  line-height: 55px;
  background-color: rgb(196, 176, 176);
  border-radius: 5px;
  margin: 0 auto;
}
.setAddressBtn {
  color: #685c5c;
  display: block;
}
</style>