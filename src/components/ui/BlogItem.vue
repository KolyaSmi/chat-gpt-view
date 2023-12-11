<template>
    <!-- <button class="btn" v-if="link.length === 0" :class="{'btn__orange': orange}">
        <slot></slot>
    </button>
    <router-link class="btn" v-else>
        <slot></slot>
    </router-link> -->

    <div class="blog-item">



    </div>
</template>
  
<script>

export default {
    name: 'BlogItem',

    props: {
        link: {
            type: String,
            default: "",
            
        },
        orange: {
            type: Boolean,
            default: false
        }
    }
}
</script>
  
<style scoped lang="scss">

.btn {
    padding: 10px 30px;
    border: 0;
    border-radius: 30px;
    background-color: black;
}

.btn__orange {
    padding: 10px;
    border-radius: 8px;
    background-color: #FF4820;
}

</style>
  