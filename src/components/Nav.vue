<style scoped>
.nav-main-ctn{
    background-color: hsl(0, 0%, 8%);
    display:flex;
    place-items:center;
    width:100%;
    padding:10px 40px 2px;
    border-radius: 0 0 150px 0;
    box-shadow: 4px 8px 6px hsla(0, 2%, 20%, 0.475), -8px -4px 6px hsla(0, 0%, 30%, 0.308);
}
.nav-semi-ctn{
    width:100%;
    display:flex;
    justify-content:space-between;
}
.logo-ctn{
    width: 100px;
}
.logo-ctn:hover{
    transform:scale(0.9);
    transition: all 2s;
}
.logo-ctn img{
    width:100%;
}
.nav-list-ctn{
    display:flex;
    justify-content:space-evenly;
    gap:2vw;
    list-style:none;
    text-transform:capitalize;
    font-size:16px;
}
.nav-list:hover{
    cursor:pointer;
    color:#ffffff;
    transition: all 2s;
}

@media screen and (max-width:900px){
    .nav-list-ctn{
        display:none;
    }
    .nav-semi-ctn{
        place-items:center;
        justify-content:center;
    }
}
</style>

<template>
    <div class="nav-main-ctn">
        <div class="nav-semi-ctn">
            <div class="logo-ctn">
                <img src="/abass-logo.svg" alt="Abass-logo"/>
            </div>
            <ul class="nav-list-ctn">
                <li class="nav-list">main</li>
                <li class="nav-list">gallery</li>
                <li class="nav-list">projects</li>
                <li class="nav-list">certifications</li>
                <li class="nav-list">contact</li>
            </ul>
        </div>
    </div>
</template>