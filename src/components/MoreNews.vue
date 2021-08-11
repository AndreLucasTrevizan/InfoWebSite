<template>
    <div class="more-news">
        <div class="side-news">
            <div class="side-news">
                <h4>Lorem Ipsum</h4>
                <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin dapibus sem sem, ac dignissim ante mollis eget. 
                    Donec ante nibh, iaculis id tempor scelerisque, sollicitudin vulputate ante.
                </p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'MoreNews'
}
</script>

<style scoped>
    .more-news {
        width: 30%;
        background-color: white;
        height: max-content;
        padding: 10px;
        border: 1px solid #1D1E20;
        border-radius: 5px;
    }

    .side-news {
        margin-bottom: 2vh;
    }

    .side-news p {
        font-size: 14px;
        margin-top: 5px;
        padding-left: 10px;
    }
</style>