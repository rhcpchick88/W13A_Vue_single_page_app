<template> 
<!-- //creating my header -->
    <div id="main">  
        <img src="https://www.pikpng.com/pngl/b/79-790899_8-bit-mario-8-bit-mario-png-clipart.png" alt="Mario">
        <h1>Super Mario is awesome</h1>
        <img src="https://www.pikpng.com/pngl/b/37-375825_luigi-clipart-pixel-mario-8-bits-png-download.png" alt="Luigi">
    </div>
</template>
<script>

export default {
    name: "MyHeader"
}
//exported the component so it is usable
</script>

<style scoped>
#main {
    width:auto;
    display:flex;
    justify-content: center;
    align-items: center;
}
h1 {
    color:white;
    background-color:grey;
    padding:10px;
    position:relative;
}
img {
    height:100px;
}
</style>
