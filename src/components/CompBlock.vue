<template>
    <div class="container comp-block">
        <div class="comp-block__inner">
            <img alt="google" src="../assets/google.png">
            <img alt="slack" src="../assets/slack.png">
            <img alt="atlassian" src="../assets/atlassian.png">
            <img alt="dropbox" src="../assets/dropbox.png">
            <img alt="shopify" src="../assets/shopify.png">
        </div>
    </div>
</template>
  
<script>

export default {
    name: 'CompBlock'
}
</script>
  
<style scoped lang="scss">
.comp-block {
    display: flex;
    flex-direction: row;
    padding: 0 200px;
    align-items: center;
    position: relative;
    z-index: 2;

    &__inner {
        width: 100%;
        display: flex;
        justify-content: space-between;
    }

    @media (max-width: 885px) {
        box-sizing: border-box;
        padding: 0 0;
        // margin: 0 10px;
    }

}
</style>
  