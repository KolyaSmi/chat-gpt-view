<template>
    <div class="container hero-block">
        <div class="hero-block__inner">
            <h1>Построим Что-нибудь <dt></dt>
                Невероятное с <dt></dt>
                GPT-4 OpenAI
            </h1>
            <p>
                Однако кровать для помощи в путешествии неприятна. Не мысли все осуществляют благословение. Снисхождение ко
                всему, радость, изменение бурной привязанности. Вечеринку мы лет на заказ разрешили.
            </p>
            <form>
                <input class="form_imput_wrapper" placeholder="Your Email Address">
                <ButtonUI orange class="btn_orange">Get Started</ButtonUI>
            </form>
        </div>
        <img alt="hero" src="../assets/hero.svg">
    </div>
</template>
  
<script>

import ButtonUI from './ui/ButtonUI.vue';

export default {
    name: 'HeroBlock',

    components: {
        ButtonUI
    },
}
</script>
  
<style scoped lang="scss">
.hero-block {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 50px;
    margin-bottom: 30px;
    position: relative;
    z-index: 5;

    // margin-left: 10px;

    &__inner {
        display: flex;
        flex-direction: column;
        max-width: 605px;
        width: 100%;

        h1 {
            background: linear-gradient(90deg, #AE67FA 1.84%, #F49867 102.67%);
            background-clip: text;
            font-weight: 800;
            font-size: 50px;
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            margin-bottom: 33px;
        }

        form {
            display: flex;
            justify-content: space-between;
            margin-top: 20px;
            margin-bottom: 20px;

            input {
                border: 0;
                background-color: #052D56;
                padding: 20px 10px 20px 10px;
                border-radius: 8px 0 0 8px;
                width: 100%;
            }

            .btn_orange {
                min-width: 100px;
                border-radius: 0 8px 8px 0;
            }
        }

    }

    img {
        width: 400px;

        @media (max-width: 790px) {
            display: none;
        }
    }
}
</style>
  