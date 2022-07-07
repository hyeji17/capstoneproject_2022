<template>
    <header>
        <div id = "select" class = "check">
            <select v-model="selected">
                <option disabled value = ""><h1> 동네</h1></option>

            </select>
            <span>Selected: {{ selected}}</span>
        </div> 
        
        <v-icon>알림</v-icon>
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

</style>