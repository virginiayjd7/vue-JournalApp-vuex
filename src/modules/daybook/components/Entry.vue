<template>
    <div class="entry-container mb-3 pointer p-2">

        <div class="entry-title d-flex">
            <span class="text-success fs-5 fw-bold">15</span>
            <span class="mx-1 fs-5" >Julio</span>
            <span class="mx-2 fw-light">2022, Miercoles</span>
        </div>
        <div class="entry-description">
        Do do nisi do incididunt cillum et excepteur laboris non enim. Fugiat Lorem sunt excepteur duis commodo ad occaecat. Deserunt et laboris deserunt Lorem irure tempor adipisicing. Et mollit qui sunt aute proident officia aliqua id eu minim tempor. Aute amet minim officia in sunt reprehenderit ex velit qui magna proident commodo aliqua.
        </div>
    </div>
</template>

<script>
export default{

}
</script>

<style lang="scss" scoped>
.entry-container {
    border-bottom: 1px solid #2c3e50;
    transition: 0.2s all ease-in;
    
    &:hover{
        background-color:lighten($color:grey,$amount:45);
        transition: 0.2s all ease-in;
    }
    .entry-description{
        font-size:12px;
    }
}
</style>