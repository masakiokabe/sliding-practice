<template>
    <div class="navbar">
        <div class="logo">
            <img src='../assets/img/logo.png'>
        </div>
        <nav>
            <ul>
                <li><a>About</a></li>
                <li><a>Library</a></li>
                <li><a>Blog</a></li>
                <li><a>Contact</a></li>
            </ul>
        </nav>
        <div class="user">
            <p>Geraldine Thomas</p>
            <img src="../assets/img/user.png">
        </div>

    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
.navbar{
    width: 100%;
    height: 60px;
    display: flex;
    align-items: center;
    background: rgba(29, 33, 61, 0.5);
    padding: 0 60px;
    box-sizing: border-box;

    position: relative;
    top: 28px 

}

.logo{
    width: 155px;
}

.logo img{
    width: 30px;
    position: relative;
    z-index: 10;
    cursor: pointer;
}

nav{
    flex: 1;
}

nav ul li{
    list-style: none;
    display: inline-block;
    margin-right: 60px;
}

nav ul li a{
    text-decoration: none;
    color: #fff;
    font-size: 14px;
}

.user{
    display: flex;
    align-items: center;
    color: #fff;
    font-size:14px;
}

.user img{
    width: 30px;
    marginleft: 15px;
    cursor: pointer;
}


</style>