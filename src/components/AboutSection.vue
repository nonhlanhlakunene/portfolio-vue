<script setup> 
const paragraphs = [ "I'm Nonhlanhla, a developer in training based in Cape Town. I started coding because I wanted to build things that actually exist in the world - something real that people can open, use and feel. That idea still drives everything I do.", "I work with HTML, CSS and JavaScript, and I am currently building web applications as part of my SheCodes Foundation training. Every project teaches me something I did not expect.", "In two years I want to be working at a tech company, freelancing, and building my own products. I am not boxing myself into one lane. I want to grow fast, build well, and do work that has real value in the world." ] 
</script> 

<template> 
    <section id="about"> 
        <div class="container section-card about-wrapper"> 
            <div class="about-img"> 
                <img src="/images/undraw_programming_j1zw.png" alt="Programming illustration" /> 
            </div> 
            <div class="about-text"> 
                <h2>About Me</h2> 
                <div class="accent-line"></div> 
                <p v-for="(text, index) in paragraphs" :key="index">{{ text }}</p> 
            </div> 
        </div> 
    </section> 
</template>