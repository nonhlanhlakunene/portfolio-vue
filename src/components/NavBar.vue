<script setup>
const links = [ { label: 'Home', id: 'home' }, { label: 'About', id: 'about' }, { label: 'Skills', id: 'skills' }, { label: 'Projects', id: 'projects' }, { label: 'Contact', id: 'contact' } ] 
</script> 

<template> 
    <header> 
        <nav class="navbar"> 
            <div class="logo">NK</div> 
            <ul class="nav-links"> 
                <li v-for="link in links" :key="link.id"> <a :href="'#' + link.id">{{ link.label }}</a> </li> 
            </ul> 
        </nav> 
    </header> 
</template>