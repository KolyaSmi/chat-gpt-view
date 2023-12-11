<template>
    <header class="container header">
        <!-- <img alt="blur-1" src="../assets/blur-01.png" /> -->

        <h1>GPT-4</h1>
        <nav>
            <ul>
                <li>
                    <router-link to="/">Главная</router-link>
                </li>
                <li>
                    <router-link to="/whatIs">Что такое GPT?</router-link>
                </li>
                <li>
                    <router-link to="/openAI">Open AI</router-link>
                </li>
                <li>
                    <router-link to="/main">Кейсы</router-link>
                </li>
                <li>
                    <router-link to="/main">Библиотека</router-link>
                </li>
            </ul>
        </nav>
        <div class="btn_header">
            <button class="singIn">Войти</button>
            <ButtonUI orange>Регистрация</ButtonUI>
        </div>
        <ButtonUI orange @click="toggleModel" class="btn__menu">Ещё</ButtonUI>
        <MenuBlock class="header__modal" v-if="isOpen" @toggleModelFun="toggleModel"></MenuBlock>
    </header>
</template>
  
<script>
import MenuBlock from './MenuBlock.vue';
import ButtonUI from './ui/ButtonUI.vue';

export default {
    name: 'HeaderBlock',

    data() {
        return {
            isOpen: false
        }
    },

    components: {
        MenuBlock,
        ButtonUI
    },

    methods: {
        toggleModel() {
            this.isOpen = !this.isOpen
        }
    }
}
</script>
  
<style scoped lang="scss">
.header {
    display: flex;
    align-items: center;
    width: 100%;
    justify-content: space-between;

    img {
        position: absolute;
        left: 0;
        z-index: 0;
    }

    h1 {
        z-index: 3;
    }

    .singIn {
        background: none;
        border: none;
        padding: 0 20px;
    }

    nav {
        z-index: 3;
        ul {
            display: flex;
            grid-gap: 20px;
        }

        @media (max-width: 790px) {
            display: none;
        }
    }

    .btn_header {
        display: flex;
        z-index: 3;

        @media (max-width: 790px) {
            display: none;
        }
    }

    .btn__menu {
        display: none;

        @media (max-width: 790px) {
            display: block;
        }
    }

    // &__modal {
    //     display: none;
    // }
}
</style>
  