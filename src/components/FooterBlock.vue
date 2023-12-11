<template>
    <footer class="footer">
        <div class="container footer__inner">
            <div class="footer__inner-main">
                <a href="#">
                    <img src="../assets/GPT-3.svg">
                </a>
                <p>Crechterwoord K12 182 DK Alknjkcb, All Rights Reserved</p>
            </div>
            <nav  class="footer__inner-nav">
                <ul>
                    <li>Links</li>
                    <li><a href="#">Overons</a></li>
                    <li><a href="#">Social Media</a></li>
                    <li><a href="#">Counters</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>

                <ul>
                    <li>Company</li>
                    <li><a href="#">Terms & Conditions</a></li>
                    <li><a href="#">Privacy Policy</a></li>
                    <li><a href="#">Contact</a></li>
                </ul>

                <ul>
                    <li>Get in touch</li>
                    <li><a href="#">Crechterwoord K12 182 DK Alknjkcb</a></li>
                    <li><a href="#">085-132567</a></li>
                    <li><a href="#">info@payme.net</a></li>
                </ul>
            </nav>
        </div>
    </footer>
</template>
  
<script>
export default {
    name: 'FooterBlock',
}
</script>
  
<style scoped lang="scss">

.footer {
    padding-top: 100px;
    padding-bottom: 20px;
    background-color: #031B34;
    position: relative;
    z-index: 3;

    &__inner {
        display: flex;
        justify-content: space-between;

        &-main {
            display: flex;
            flex-direction: column;
            grid-gap: 10px;
        }

        &-nav {
            display: flex;
            grid-gap: 50px;

            ul {
                display: flex;
                flex-direction: column;
                grid-gap: 20px;

                li {
                    a {
                        color: #8f8f8f;
                    }
                }
            }
        }
    }

    
}

</style>
  