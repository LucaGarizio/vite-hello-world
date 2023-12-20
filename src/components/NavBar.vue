<script>

</script>

<template>
  <nav class="nav-bar">
    <div class="path-section">
        <ul class="flex">
            <li>
                <a href="#">Story</a>
            </li>
            <li>
                <a href="#">Characters</a>
            </li>
        </ul>
    </div>
    <div class="logo">
        <a href="#">
            <img src="../assets/ciao2.jpg" alt="">
        </a>
    </div>
    <div class="path-section">
        <ul class="flex">
            <li>
                <a href="#">Villain</a>
            </li>
            <li>
                <a href="#">Credits</a>
            </li>
        </ul>
    </div>
  </nav>
</template>

<style scoped>
.nav-bar{
    height: 100px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: black;
    color: white;
}

img {
    height: 100px;
}

.nav-bar ul{
    display: flex;
    list-style: none;    
}

.nav-bar a{
    text-decoration: none;
    color: #dd0202;
}

.nav-bar li{
    margin: 0 100px;
    font-size: 30px;
}
</style>