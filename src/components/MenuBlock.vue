<template>
    <div class="menu-block">
        <div class="menu-block__inner">
            <button class="menu-block__close" @click="$emit('toggleModelFun')">Close</button>
            <nav>
                <ul>
                    <li>
                        <router-link to="/main">Главная</router-link>
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
                <button>Войти</button>
                <button>Регистрация</button>
            </div>
        </div>
    </div>
</template>
  
<script>
export default {
    name: 'MenuBlock'
}
</script>
  
<style scoped lang="scss">
.menu-block {
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    height: 100vh;
    background-color: #042c5452;
    backdrop-filter: blur(5px);
    z-index: 3;

    &__inner {
        display: flex;
        flex-direction: column;
        background-color: #042C54;
        border-radius: 10px 0 0 10px;
        max-width: 500px;
        width: 100%;
        height: 100%;
        margin-left: auto;
        margin-right: 0;
    }

    &__close {
        position: absolute;
        top: 10px;
        right: 10px;
    }
}
</style>
  