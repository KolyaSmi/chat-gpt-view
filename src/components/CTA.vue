<template>
    <div class="container cta-block">
        <div class="cta-block__inner">
            <div class="cta-block__inner__info">
                <p>Request Early Access to Get Started</p>
                <h3>Register today & start exploring the endless possiblities.</h3>
            </div>
            <ButtonUI class="btn_dark">
                <span class="btn_text">Get Started</span>
            </ButtonUI>
        </div>
    </div>
</template>
  
<script>
import ButtonUI from './ui/ButtonUI.vue';

export default {
    name: 'CTA',

    components: {
        ButtonUI
    }
}
</script>
  
<style scoped lang="scss">

.cta-block {
    background: linear-gradient(90deg, #AE67FA 1.84%, #F49867 102.67%);
    padding: 30px 40px;
    border-radius: 10px;

    &__inner {
        display: flex;
        justify-content: space-between;

        &__info {
            p {
                color: black;
            }

            h3 {
                color: black;
            }
        }
    }
}

</style>
  