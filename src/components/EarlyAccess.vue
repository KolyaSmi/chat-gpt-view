<template>
    <div class="early-access">
        <div class="early-access__inner">
            <h1>Do you want to step in to the future before others</h1>
            <button class="btn-trans">
                <span class="btn-text">Request Early Access</span>
            </button>
        </div>
    </div>
</template>

<script>

export default {
    name: 'EarlyAccess'
}

</script>

<style scoped lang="scss">
.early-access {
    margin-top: 80px;
    background-color: #031B34;

    &__inner {
        display: flex;
        flex-direction: column;
        align-items: center;
        margin: 0 auto;
        padding-top: 50px;
        max-width: 620px;
        width: 100%;
        text-align: center;

        h1 {
            background: linear-gradient(90deg, #AE67FA 1.84%, #F49867 102.67%);
            background-clip: text;
            font-weight: 800;
            font-size: 50px;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 33px;
        }

        button {
            background: none;
            border-color: white;
            padding: 20px 50px;
            max-width: 250px;
        }
    }
}
</style>