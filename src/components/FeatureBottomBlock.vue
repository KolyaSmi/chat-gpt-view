<template>
    <div class="container feature-bottom-block">
        <img src="../assets/feature_image.png">
        <div class="feature-bottom-block__info">
            <a href="#">Request Early Access to Get Started</a>
            <h1>The possibilities are beyond your imagination</h1>
            <p>Yet bed any for travelling assistance indulgence unpleasing. Not thoughts all exercise blessing. Indulgence
                way everything joy alteration boisterous the attachment. Party we years to order allow asked of.</p>
            <a href="#">Request Early Access to Get Started</a>
        </div>
    </div>
</template>
  
<script>
export default {
    name: 'FeatureBottomBlock',
}
</script>
  
<style scoped lang="scss">
.feature-bottom-block {
    display: flex;
    align-items: center;
    justify-content: space-between;
    grid-gap: 70px;
    margin: 70px auto;

    &__info {
        display: flex;
        flex-direction: column;
        grid-gap: 20px;

        h1 {
            background: linear-gradient(90deg, #AE67FA 1.84%, #F49867 102.67%);
            background-clip: text;
            font-weight: 800;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 33px;
        }

        a {
            white-space: nowrap;
            font-size: 14px;
            font-weight: 300;
            color: #FF8A71;
        }
    }

    img {
        max-width: 400px;
        width: 100%;
    }

    @media (max-width: 903px) {
        flex-direction: column;
        grid-gap: 30px;
        padding: 0 100px;
    }
}
</style>
  