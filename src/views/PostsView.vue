<template>
    <div class="post-view" v-if="getBlogData">
        <div class="container blog-item">
            <div class="blog-item__title">
                <h3>{{ getBlogData[0].title }}</h3>
                <router-link class="link" to="/post">Читать полностью</router-link>
            </div>
            <div class="blog-item__body">
                <h4>{{ getBlogData[0].text }}</h4>
                <p>{{ getBlogData[0].createAt }}</p>
            </div>
        </div>
        
    </div>
</template>
  
<script>
import axios from 'axios';

export default {
    name: 'PostsView',

    data() {
        return {
            blogData: null
        }
    },

    components: {
    },

    computed: {
        getBlogData() {
            return this.blogData
        }
    },

    async mounted() {
        const res = await axios.get('http://0.0.0.0:8761/post')

        this.blogData = res.data
        // fetch('http://0.0.0.0:8761/post')
        //     .then(response => response.json())
        //     .then((res) => {
        //         this.blogData = res
        //     })
        // .catch(err => alert(err));
    }
}
</script>

<style scoped lang="scss">
.blog-item {
    background-color: #042C54;
    position: relative;
    z-index: 5;
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 150px;
    margin: 30px auto;

    .link  {
        white-space: nowrap;
        font-size: 14px;
        font-weight: 300;
        color: #FF8A71;
    }

    &__title {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        height: 100%;
        padding: 20px 0;
    }

    &__body {
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        height: 100%;
        padding: 20px 0;
    }
}
</style>