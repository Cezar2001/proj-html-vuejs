<template>
<div class="container">
    
    <div class="terms">
       
        <div class="about"
        v-for="about in about" :key="about.id">
            
            <h2>{{about.title}}</h2>
            
            <div class="line"></div>
            
            <p>{{about.text}}</p>
            
            <div>
                <i class="fab fa-linkedin-in"></i>
                <i class="fab fa-facebook-f"></i>
                <i class="fab fa-twitter"></i>
            </div>
        
        </div>
    
        <div class="twitter"
        v-for="twitter in twitter" :key="twitter.id">
            
            <h2>{{twitter.title}}</h2>
            
            <div class="line"></div>
            
            <div class="twitter-flex">
                
                <div class="twitter-icon">
                    <i class="fab fa-twitter"></i>
                    <i class="fab fa-twitter"></i>
                </div>
                
                <div>
                    <p>{{twitter.text}}</p>
                    <p>{{twitter.secondaryText}}</p>
                </div>
            
            </div>
        </div>
         
        <div class="links"
        v-for="link in links" :key="link.id">

            <h2>{{link.title}}</h2>
            
            <div class="line"></div>

            <ul>
                <li>{{link.me}}</li>
                <li>{{link.us}}</li>
                <li>{{link.language}}</li>
                <li>{{link.coach}}</li>
                <li>{{link.events}}</li>
            </ul>

        </div>

        <div class="contact"
        v-for="contact in contact" :key="contact.id">

            <h2>{{contact.title}}</h2>
            
            <div class="line"></div>

            <div class="info">
                <i class="fas fa-map-marker-alt"></i>
                <span>{{contact.position}}</span>
            </div>

            <div class="info">
                <i class="fas fa-phone"></i>
                <span>{{contact.phone}}</span>
            </div>

            <div class="info">
                <i class="far fa-envelope"></i>
                <span>{{contact.mail}}</span>
            </div>

            <div class="info">
                <input type="text" placeholder="Your Name"><span class="subscribe">SUBSCRIBE</span>
            </div>

        </div>

        <div class="up">
            <a href="#top">
                <i class="fas fa-long-arrow-alt-up"></i>
            </a>
        </div>
    
    </div>

    <div class="footer-bar">
        <span>Copyright Everlead © MikadoThemes</span>
    </div>

</div>
</template>

<script>
export default {
    props: {
        about: Array,
        twitter: Array,
        links: Array,
        contact: Array,
    }
}
</script>

<style lang="scss" scoped>
@import '../style/variables.scss';
@import '../style/FooterBox.scss';
</style>