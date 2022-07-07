<template>
  <v-container>
    <v-row class="button-first">  
     <div class="btnFirst">
      <span class="fBtn" @click="first">일번</span>
      <span class="fBtn" @click="second">이번</span>
      <span class="fBtn" @click="third">삼번</span>
      <span class="fBtn" @click="fourth">사번</span>
    </div>
    </v-row>
 </v-container>
</template>

<script>
export default {
  methods: {
    first() {
      // this.$emit("removeAll");
      this.$store.commit('일번');
    },
    second() {
      // this.$emit("removeAll");
      this.$store.commit('이번');
    },
    third() {
      // this.$emit("removeAll");
      this.$store.commit('삼번');
    },
    fouth() {
      // this.$emit("removeAll");
      this.$store.commit('사번');
    },
  },
};
</script>

<style scoped>
.btnFirst .fBtn{
  display:inline-block;
  width: 5rem;
  height: 50px;
  line-height: 50px;
  background-color: white;
  border-radius: 5px;
  margin: 4px;
}
.fBtn {
  color: #1a2ee4;
  display: block;
}
</style>