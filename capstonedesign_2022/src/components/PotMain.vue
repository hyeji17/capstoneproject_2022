<template>
        <div id="menu-container">
        <button @click = "menu"><img alt="logo" src="../assets/메뉴찾기.png">
        </button>
        </div>
        <div id="delivery-search-container">
        <button @click = "search"><img alt="logo" src="../assets/배달팟찾기.png">
        </button>
        </div>
        <div id="delivery-create-container">
        <button @click = "create"><img alt="logo" src="../assets/배달팟구하기.png">
        </button>
        </div>
</template>

<script>
export default{
    name : 'PotMain',

}
</script>

<style scoped>
#menu-container{
position: absolute;
width: 147px;
height: 147px;
left: 113px;
top: 195px;
}
#delivery-search-container{
position: absolute;
width: 147px;
height: 147px;
right: 198px;
top: 364px;
}
#delivery-create-container{
position: absolute;
width: 152px;
height: 147px;
left: 195px;
top: 364px;
}

</style>