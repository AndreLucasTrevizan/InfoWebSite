<template>
    <div class="publicacao">
        <div class="title-pub">
            <h2>Lorem Ipsum sit Ammet</h2>
            <span>11 de Ago - 14:15</span>
        </div>
        <div class="img-pub">
            <img src="@/assets/lobo1.jpg">
        </div>
        <div class="descricao">
            <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin dapibus sem sem, ac dignissim ante mollis eget. 
                Donec ante nibh, iaculis id tempor scelerisque, sollicitudin vulputate ante. Quisque ut eleifend nisl. 
                Vivamus et ante dolor. Proin accumsan nisl egestas massa suscipit, vel vestibulum felis gravida. 
                Duis posuere non nulla accumsan maximus. Phasellus mollis efficitur tellus, et pellentesque nunc fermentum vel. 
                Integer sollicitudin tempor feugiat. Aliquam vitae turpis placerat, luctus ante non, gravida risus. 
            </p>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Pub'
}
</script>

<style scoped>
    .publicacao {
        padding: 10px;
        margin-bottom: 2vh;
        border: 1px solid #1D1E20;
        background-color: white;
        border-radius: 5px;
    }

    .title-pub span{
        font-size: 13px;
    }

    .img-pub img{
        width: 100%;
        margin-bottom: 2vh;
    }

    .descricao {
        text-align: justify;
        font-size: 16px;
    }
</style>