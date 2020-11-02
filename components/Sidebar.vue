<template>
    <div class="sidebar">
        <img src="../assets/img/search.png" class="search-icon">
        <div class="social-links">
            <img src="../assets/img/fb.png">
            <img src="../assets/img/pt.png">   
            <img src="../assets/img/tw.png">  
        </div>
        <img src="../assets/img/info.png" class="info-icon">
          
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
.sidebar{
    width: 155px;
    height:100vh;
    background: rgba(29, 31, 58, 0.5);
    position: absolute;
    top: 0;
    left: 0;
}

.search-icon{
    width: 20px;
    display: block;
    margin: 120px auto 0;

}

.social-links{
    width: 20px;
    display: block;
    margin: 220px auto 0;
    text-align: center;
}

.social-links img{
    height: 15px;
    margin-bottom:30px;  
}

.info-icon{
    width: 20px;
    position: absolute;
    left: 50%;
    bottom: 30px;
    transform: translateX(-50%);

}

</style>