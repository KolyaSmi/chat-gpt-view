<template>
    <!-- <div class="container blog">
        <div class="blog__title">
            <h1>A lot is happening,
                We are blogging about it.</h1>
        </div>
        <div class="blog__inner">
            <div class="blog__inner__item-big">
                <div class="blog__inner__item__img">
                    <img src="../assets/Rectangle 22.png">
                </div>
                <div class="blog__inner__item__info">
                    <div class="blog__inner__item__info__main">
                        <span>Sep 26, 2021</span>
                        <p>GPT-3 and Open AI is the future. Let us exlore how it is?</p>
                    </div>
                    <a href="#">Read Full Article</a>
                </div>
            </div>

            <div class="blog__inner__block">
                <div class="blog__inner__block__raw">
                    <div class="blog__inner__block__raw">
                        <div class="blog__inner__block__raw__img">
                            <img src="../assets/Rectangle 22-2.png">
                        </div>
                        <div class="blog__inner__block__raw__info">
                            <div class="blog__inner__block__raw__info__main">
                                <span>Sep 26, 2021</span>
                                <p>GPT-3 and Open AI is the future. Let us exlore how it is?</p>
                            </div>
                            <a href="#">Read Full Article</a>
                        </div>
                    </div>

                    <div class="blog__inner__item">
                        <div class="blog__inner__item__img">
                            <img src="../assets/Rectangle 22-3.png">
                        </div>
                        <div class="blog__inner__item__info">
                            <div class="blog__inner__item__info__main">
                                <span>Sep 26, 2021</span>
                                <p>GPT-3 and Open AI is the future. Let us exlore how it is?</p>
                            </div>
                            <a href="#">Read Full Article</a>
                        </div>
                    </div>
                </div>

                <div class="blog__inner__raw">
                    <div class="blog__inner__item">
                        <div class="blog__inner__item__img">
                            <img src="../assets/Rectangle 22-4.png">
                        </div>
                        <div class="blog__inner__item__info">
                            <div class="blog__inner__item__info__main">
                                <span>Sep 26, 2021</span>
                                <p>GPT-3 and Open AI is the future. Let us exlore how it is?</p>
                            </div>
                            <a href="#">Read Full Article</a>
                        </div>
                    </div>

                    <div class="blog__inner__item">
                        <div class="blog__inner__item__img">
                            <img src="../assets/Rectangle 22-5.png">
                        </div>
                        <div class="blog__inner__item__info">
                            <div class="blog__inner__item__info__main">
                                <span>Sep 26, 2021</span>
                                <p>GPT-3 and Open AI is the future. Let us exlore how it is?</p>
                            </div>
                            <a href="#">Read Full Article</a>
                        </div>
                    </div>
                </div>
            </div>


        </div>
    </div> -->

    <div class="blog container">
            <h1>A lot is happening, 
                We are blogging about it.</h1>
            <div class="blog_body">
                <div class="blog_item_big">
                    <div class="blog_item_img_big">
                        <img src="../assets/Rectangle 22.png">
                    </div>
                    <div class="blog_item_big_info">
                        <div class="blog_item_info_main">
                            <span>Sep 26, 2021</span>
                            <p>GPT-3 and Open  AI is the future. Let us exlore how it is?</p>
                        </div>
                        <a href="#">Read Full Article</a>
                    </div>
                </div>

                <div class="blog_body_min">
                    <div class="blog_body_min_raw">
                        <div class="blog_item">
                            <div class="blog_item_img">
                                <img src="../assets/Rectangle 22-2.png">
                            </div>
                            <div class="blog_item_info">
                                <div class="blog_item_info_main">
                                    <span>Sep 26, 2021</span>
                                    <p>GPT-3 and Open  AI is the future. Let us exlore how it is?</p>
                                </div>
                                <a href="#">Read Full Article</a>
                            </div>
                        </div>
        
                        <div class="blog_item">
                            <div class="blog_item_img">
                                <img src="../assets/Rectangle 22-3.png">
                            </div>
                            <div class="blog_item_info">
                                <div class="blog_item_info_main">
                                    <span>Sep 26, 2021</span>
                                    <p>GPT-3 and Open  AI is the future. Let us exlore how it is?</p>
                                </div>
                                <a href="#">Read Full Article</a>
                            </div>
                        </div>
                    </div>
                    
                    <div class="blog_body_min_raw">
                        <div class="blog_item">
                            <div class="blog_item_img">
                                <img src="../assets/Rectangle 22-4.png">
                            </div>
                            <div class="blog_item_info">
                                <div class="blog_item_info_main">
                                    <span>Sep 26, 2021</span>
                                    <p>GPT-3 and Open  AI is the future. Let us exlore how it is?</p>
                                </div>
                                <a href="#">Read Full Article</a>
                            </div>
                        </div>
        
                        <div class="blog_item">
                            <div class="blog_item_img">
                                <img src="../assets/Rectangle 22-5.png">
                            </div>
                            <div class="blog_item_info">
                                <div class="blog_item_info_main">
                                    <span>Sep 26, 2021</span>
                                    <p>GPT-3 and Open  AI is the future. Let us exlore how it is?</p>
                                </div>
                                <a href="#">Read Full Article</a>
                            </div>
                        </div>
                    </div>
                    
                </div>
                
            </div>
        </div>
</template>
  
<script>

export default {
    name: 'BlogBlock'
}
</script>

<style scoped lang="scss">

.blog h1{
    margin: 100px 0;
    background: linear-gradient(90deg, #AE67FA 1.84%, #F49867 102.67%);
    background-clip: text;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    font-size: 62px;
    color: white;
}

.blog_body {
    grid-gap: 47px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    color: white;
}

.blog_item_big_info {
    position: relative;
    color: white;
    margin-top: -7px;
    padding-bottom: 13px;
    background: #042C54;
    width: 350px;
    height: 368px;
}

.blog_item_big_info a{
    position: absolute;
    bottom: 0;
    color: white;
    margin-left: 25px;
    margin-bottom: 15px;
    font-size: 12px;
}

.blog_item_img_big img{
    max-width: 350px;
    width: 100%;
}

.blog_item_info {
    width: 329px;
    margin-top: -7px;
    padding-bottom: 13px;
    background: #042C54;
}

.blog_item_info a {
    margin-left: 25px;
    font-size: 12px;
    color: white;
}

.blog_item_info_main{
    padding-top: 10px;
    padding-left: 25px;
    margin-bottom: 40px;
}

.blog_item_info_main span{
    font-size: 12px;
}

.blog_body_min {
    display: flex;
    flex-direction: column;
    grid-gap: 47px;
}

.blog_body_min_raw {
    grid-gap: 47px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

</style>
  