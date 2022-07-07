<template>
<v-container>
  <div class="inputBox shadow">
    <span class="newTodoItem" @click="first">메뉴 찾기</span>
    <span class="newTodoItem" @click="first">배달팟 구하기</span>
    <span class="newTodoItem" @click="first">배달팟 찾기</span>
</div>
</v-container>
</template>

<script>

</script>

<style scoped>
input:focus {
  outline: none;
}
.inputBox .newTodoItem{
  background: rgb(222, 212, 247);
  width: 300px;
  height: 150px;
  line-height: 150px;
  border-radius: 5px;
  margin:40px;
}
.newTodoItem {
  color: rgb(252, 250, 250);
  /* vertical-align: middle; */
  display: block;
}
</style>
