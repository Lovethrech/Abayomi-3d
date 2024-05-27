<script setup>

</script>

<style scoped>
.semi-header-image-section-ctn{
    width:40%;
    height:100%;
    display:flex;
    place-items: center;
}
.semi-header-image-section-main-ctn{
    width:100%;
    height:100%;
    display:flex;
    place-items: end;
}
.inner-image-ctn{
    width:400px;
    position:absolute;
    right:0;
    z-index:-1;
    border-top-left-radius: 200px;
    border-bottom-left-radius: 100px;
    box-shadow: 4px 8px 6px hsla(0, 2%, 20%, 0.475), -20px -4px 2px hsla(0, 0%, 30%, 0.623);
}
.inner-image-ctn img{
    width:100%;
    height:100%;
    border-top-left-radius: 200px;
    border-bottom-left-radius: 100px;
}

.outer-image-ctn{
    width:30vw;
    border-top-left-radius: 200px;
    border:2px dashed hsl(0, 0%, 100%);

}
.outer-image-ctn img{
    width:100%;
    height:100%;
    border-top-left-radius: 200px;
}

@media screen and (max-width:1400px) and (min-width:901px){
    .semi-header-image-section-ctn {
        width:60%;
    }
    .outer-image-ctn{
        width:500px;
    }
}
@media screen and (max-width:1300px) {
    .outer-image-ctn {
        margin-right:30px;
    }
}
@media screen and (max-width:900px) {
    .semi-header-image-section-ctn {
        width:100%;
    }
    .semi-header-image-section-main-ctn {
        flex-direction: column;
    }
    .inner-image-ctn{
        position:relative;
        width:300px;
    }
    .outer-image-ctn{
        width:350px;
        margin:-200px 20vw 0 0;
    }
}
@media screen and (max-width:400px) {
    .inner-image-ctn{
        width:200px;
    }
    .outer-image-ctn{
        width:250px;
        margin-top:-150px;
    }
}
</style>


<template>
    <div class="semi-header-image-section-ctn">
        <div class="semi-header-image-section-main-ctn">
            <div class="inner-image-ctn" data-aos="zoom-in-left" data-aos-delay="200">
                <img src="/header-profile.jpg" alt="inner profile">
            </div>
            <div class="outer-image-ctn" data-aos="fade-down-right" data-aos-delay="600">
                <img src="/header-outer.jpg" alt="outer-profile">
            </div>
        </div>
    </div>
</template>