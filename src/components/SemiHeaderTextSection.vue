<style scoped>
.semi-header-text-section-ctn{
    margin:0 0 0 6vw;
    width:60%;
    height:100%;
    display:flex;
    place-items:center;
}
.semi-header-text-section-main-ctn{

}
.title{
    font-size:50px;
    letter-spacing:10px;
    text-transform:uppercase;
}
.title:hover{
    color: white;
    transition: all .7s
}
.title-desc{
    font-size:16px;
}
.title-desc:hover{
    color:white;
}
.header-contact{
    margin:20px 0;
    background-color:white;
    border:2px solid hsl(0, 0%, 100%);
    color: rgb(0, 0, 0);
    padding: 10px 20px;
}
.header-contact:hover{
    cursor:pointer;
    background-color: transparent;
    color: white;
    transition: all 2s;
}

@media screen and (max-width:900px) {
    .semi-header-text-section-ctn {
        width: 90%;
    }
}

@media screen and (max-width:400px) {
    .title {
        font-size:30px;
    }
    .title-desc{
        font-size:14px;
    }
}
</style>

<template>
    <div class="semi-header-text-section-ctn">
        <div class="semi-header-text-section-main-ctn">
            <h1 class="title" data-aos="fade-down" data-aos-delay="100">The greatest<br />Architect</h1>
            <p class="title-desc" data-aos="fade-right" data-aos-delay="500">
                I am an architect who seamlessly combines creativity, dedication, and strategic thinking. My journey
                began with early exposure to art, music, and literature. I seek mentorship from architectural pioneers
                like Mies Van Der Rohe and Le Corbusier. My standout portfolio reflects my vision, and I thrive on
                networking, embracing challenges, and fostering personal connections.
            </p>
            <RouterLink to="/">
                <button class="header-contact" data-aos="fade-up" data-aos-delay="700">Get in Touch</button>
            </RouterLink>
        </div>
    </div>
</template>