<template>
    <div id = "FooterIcon">
        <button @click = "find">검색</button>
        <button @click="chat">채팅</button>
        <button @click="pod">팟</button>
        <button @click="MyPage">마이페이지</button>
    </div>
</template>

<script>
export default{
    name : 'PotFooter',
    methods: {
            find(){

            },
            chat(){

            },
            pod(){
                
            },
            MyPage(){

            }
            ,
        },
}
</script>

<style scoped>
.FooterIcon{
  Font-family: sans-serif;
  border: 1px solid #eee;
  border-radius: 2px;
  padding: 20px 30px;
  margin-top: 1em;
  margin-bottom: 40px;
  user-select: none;
  overflow-x: auto;
}
</style>