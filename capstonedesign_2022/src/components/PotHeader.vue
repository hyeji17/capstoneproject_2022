<template>
    <header>
        <div id = "select" class = "check">
            <select v-model="selected">
                <option disabled value = ""><h1> 우리집</h1></option>

            </select>
            <span>Selected: {{ selected}}</span>
        </div> 
        <div class="logo-container">
        <img alt="logo" src="../assets/arram.png">
        </div>
    </header>
</template>

<script>
export default{
    name : 'PotHeader',
     data(){
        return{
            selected : ''
        
        }
    }
}
</script>

<style scoped>
#select{
position: absolute;
width: 375px;
height: 92px;
left: -1px;
top: -8px;

background: #FFD260;
border-radius: 10px;
}
.logo-container{
position: absolute;
width: 20px;
height: 23.33px;
left: 325px;
top: 26px;

/* background: url(pngwing); */
}
</style>