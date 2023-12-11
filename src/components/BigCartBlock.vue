<template>
    <div class="container big-card">
        <!-- <img src="../assets/Ellipse 40.png" class="big-cart-img-1"> -->
        <!-- <img src="../assets/Ellipse 39.png" class="big-cart-img-2"> -->
        <div class="big-card__title">
            <h3>
                What is GPT-3
            </h3>

            <p>
                We so opinion friends me message as delight. Whole front do of plate heard oh ought. His defective nor
                convinced residence own. Connection has put impossible own apartments boisterous. At jointure ladyship an
                insisted so humanity he. Friendly bachelor entrance to on by.
            </p>
        </div>
        <div class="big-card__main">
            <h1>
                The possibilities are beyond your imagination
            </h1>
            <a href="#">Explore The Library</a>
        </div>
        <div class="big-card__list">
            <ul>
                <li>
                    <h3>
                        Chatbots
                    </h3>
                    <p>
                        We so opinion friends me message as delight. Whole front do of plate heard oh ought.
                    </p>
                </li>
                <li>
                    <h3>
                        Knowledgebase
                    </h3>
                    <p>
                        At jointure ladyship an insisted so humanity he. Friendly bachelor entrance to on by. As put
                        impossible own apartments b
                    </p>
                </li>
                <li>
                    <h3>
                        Education
                    </h3>
                    <p>
                        At jointure ladyship an insisted so humanity he. Friendly bachelor entrance to on by. As put
                        impossible own apartments b
                    </p>
                </li>
            </ul>
        </div>
    </div>
</template>
  
<script>

export default {
    name: 'BigCartBlock'
}
</script>

<style scoped lang="scss">
.big-card {
    background-color: #042C54;
    margin: 60px auto;
    padding: 40px;

    .big-cart-img-1 {
        position: absolute;
        left: 0;
        top: 0;
        z-index: 0;
    }

    .big-cart-img-2 {
        position: absolute;
        right: 0;
        bottom: 0;
    }

    a {
        white-space: nowrap;
        font-size: 14px;
        font-weight: 300;
        color: #FF8A71;
    }

    h3::before {
        background: linear-gradient(103deg, #ae67fa -13.86%, #f49867 99.55%), #fff;
        content: "";
        display: block;
        height: 3px;
        width: 38px;
        margin-bottom: 10px;
    }

    &__title {
        display: flex;
        justify-content: space-between;
        margin-bottom: 60px;
        z-index: 3;

        h3 {
            z-index: 1;
        }

        p {
            max-width: 700px;
            width: 100%;
        }

        @media (max-width: 537px) {
            flex-direction: column;
            grid-gap: 30px;
        }
    }

    &__main {
        display: flex;
        align-items: center;
        justify-content: space-between;
        margin-bottom: 60px;

        h1 {
            background: linear-gradient(90deg, #AE67FA 1.84%, #F49867 102.67%);
            background-clip: text;
            font-weight: 800;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            max-width: 600px;
            width: 100%;
        }

        @media (max-width: 578px) {
            flex-direction: column;
            grid-gap: 30px;
        }
    }

    &__list {

        ul {
            display: flex;
            justify-content: space-between;
            z-index: 3;

            li {
                max-width: 300px;
                width: 100%;

                h3 {
                    margin-bottom: 15px;
                }
            }


            @media (max-width: 730px) {
                flex-direction: column;
                grid-gap: 30px;
            }
        }
    }
}
</style>
  