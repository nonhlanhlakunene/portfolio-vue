<script setup> const skills = [ { name: 'HTML', icon: 'devicon-html5-plain colored' }, { name: 'CSS', icon: 'devicon-css3-plain colored' }, { name: 'JavaScript', icon: 'devicon-javascript-plain colored' }, { name: 'Git', icon: 'devicon-git-plain colored' }, { name: 'GitHub', icon: 'devicon-github-original colored' }, { name: 'Bootstrap', icon: 'devicon-bootstrap-plain colored' } ] 
</script> 

<template> 
    <section id="skills"> 
        <div class="container section-card"> 
            <h2>Tech Stack</h2> 
            <div class="accent-line"></div> 
            <p>Technologies I currently work with:</p> 
            <div class="skills-grid"> 
                <div class="skill" v-for="skill in skills" :key="skill.name"> 
                    <i :class="skill.icon"></i> <span>{{ skill.name }}</span> 
                </div> 
            </div> 
        </div> 
    </section> 
</template>