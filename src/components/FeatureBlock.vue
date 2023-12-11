<template>
    <div class="container feature-block">
        <div class="feature-block__title">
            <h1>The Future is Now and <br /> You Just Need To Realize <br /> It. Step into Future Today<br /> & Make it
                Happen.</h1>
            <a href="#">Request Early Access to Get Started</a>
        </div>
        <div class="feature-block__info">
            <div class="feature-block__info__item">
                <h4>Improving end distrusts instantly</h4>
                <p>From they fine john he give of rich he. They age and draw mrs like. Improving end distrusts may instantly
                    was household applauded.</p>
            </div>
            <div class="feature-block__info__item">
                <h4>Become the tended active</h4>
                <p>Considered sympathize ten uncommonly occasional assistance sufficient not. Letter of on become he tended
                    active enable to.</p>
            </div>
            <div class="feature-block__info__item">
                <h4>Message or am nothing</h4>
                <p>Led ask possible mistress relation elegance eat likewise debating. By message or am nothing amongst
                    chiefly address.</p>
            </div>
            <div class="feature-block__info__item">
                <h4>Really boy law county</h4>
                <p>Really boy law county she unable her sister. Feet you off its like like six. Among sex are leave law
                    built now. In built table in an rapid blush.</p>
            </div>
        </div>
    </div>
</template>

<script>

export default {
    name: 'FeatureBlock'
}

</script>

<style scoped lang="scss">
.feature-block {
    display: flex;
    justify-content: space-between;
    align-items: center;

    &__title {

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

    &__info {
        display: flex;
        flex-direction: column;
        max-width: 650px;
        width: 100%;
        grid-gap: 20px;

        &__item {
            display: flex;
            justify-content: space-between;
            align-items: center;

            h4 {
                max-width: 150px;
                // margin-right: 30px;
            }

            h4::before {
                background: linear-gradient(103deg, #ae67fa -13.86%, #f49867 99.55%), #fff;
                content: "";
                display: block;
                height: 3px;
                width: 38px;
                margin-bottom: 10px;
            }

            p {
                max-width: 400px;
                width: 100%;
            }
        }
    }

    @media (max-width: 1070px) {
        flex-direction: column;
        grid-gap: 30px;
    }
}
</style>