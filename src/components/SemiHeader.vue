<script setup>
import SemiHeaderTextSection from './SemiHeaderTextSection.vue';
import SemiHeaderImageSection from './SemiHeaderImageSection.vue';
</script>


<style scoped>
.semi-header-ctn{
    width:100%;
    height:80vh;
}
.semi-header-main-ctn{
    margin:4vh 0;
    display: flex;
    justify-content: space-between;
    width:100%;
    height:100%;
    display: flex;
    justify-content: space-between;
}
@media screen and (max-width:900px){
    .semi-header-ctn{
        height:100%;
    }
    .semi-header-main-ctn {
        flex-direction: column;
    }
}
</style>

<template>
    <div class="semi-header-ctn">
        <div class="semi-header-main-ctn">
            <SemiHeaderTextSection></SemiHeaderTextSection>
            <SemiHeaderImageSection></SemiHeaderImageSection>
        </div>
    </div>
</template>