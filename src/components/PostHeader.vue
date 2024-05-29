<style scoped>
.post-header-ctn{
    padding:200px 0;
    width:100%;
    height:100%
}
.about-title{
    color:white;
    font-style: italic;
    text-align: center;
    font-size:50px;
    text-transform: uppercase;
    letter-spacing: 15px;
}
.post-header-main-ctn{
    width:100%;
    height:1000%;
    display:flex;
    justify-content: space-between;
}
.img-ctn{
    width:40%;
}
.img-ctn img{
    width:100%;
    border-top-right-radius: 300px;
}
.text-ctn{
    width:60%;
}
</style>


<template>
    <div class="post-header-ctn">
        <h2 class="about-title">About me</h2><br/><br/>
        <div class="post-header-main-ctn">

            <div class="img-ctn">
                <img src="/post-header-img.jpg" alt="">
            </div>
            <div class="text-ctn"></div>
        </div>
    </div>
</template>