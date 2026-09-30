# Nonhlanhla Kunene | Portfolio

Software Developer Intern based in Cape Town, South Africa.

Live site: https://portfolio-vue-eta-vert.vercel.app/

Original portfolio site: https://nonhlanhlakunene.github.io/my-portfolio/

## About

This is my personal portfolio, rebuilt in Vue.js. It started as a vanilla HTML, CSS and Bootstrap site, and I transferred it to Vue to work with a component-based frontend framework.

## What changed in the move to Vue

- The single index.html is now split into Vue components, one for each section
- The navbar links, About text, skills and project cards are lists of data, drawn with v-for
- Project buttons only appear when a link exists, using v-if
- The light and dark mode is a Vue component that uses a ref, instead of the old CSS checkbox
- The contact form sends the subject field, and email and message are required
- Screenshots and image paths are fixed, and the Vue starter files are removed

## Challenges

- Theme toggle: my old dark and light mode depended on a hidden checkbox sitting before everything else in the HTML, which does not work well in Vue. I rebuilt it as a component that uses a ref and switches a class on the body.
- CSS that stopped working: the gap between my project buttons and contact links disappeared, because gap only works on a flex container and my rules were missing display: flex. In the old page a space in the HTML hid the problem.
- Components not showing: a component did not appear because I imported it but never added its tag to the template. Both are needed.

## Future improvements

- Remember the chosen theme after a refresh, using localStorage
- Add my backend and full-stack projects, and Node.js, Express and MySQL to the skills list
- Show a thank-you message after the contact form is sent, instead of leaving the page
- Add a short write-up for each project about the problem, my role and what I learned
- Test on more phones and screen sizes, and improve accessibility

## Built with

Vue 3, Vite, JavaScript, Bootstrap 5, Font Awesome, Devicon, Web3Forms, Vercel

## Run it locally

    git clone https://github.com/nonhlanhlakunene/portfolio-vue.git
    cd portfolio-vue
    npm install
    npm run dev

## Contact

Email: knonhlanhla585@gmail.com
LinkedIn: https://linkedin.com/in/nonhlanhla-kunene-8416ba369
GitHub: https://github.com/nonhlanhlakunene
