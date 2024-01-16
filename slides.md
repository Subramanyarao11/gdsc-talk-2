---
layout: cover
download: https://github.com/Subramanyarao11/gdsc-talk-2
highlighter: shiki
title: Deploying Static Sites
coverAuthor: Subramanya Rao
titleTemplate: '%s - Subramanya Rao'
exportFilename: gdsc-deploy
favicon: /favicon.ico
hideInToc: true
info: |
 <h2>Deploying Static Sites</h2>
  <a href="https://gdsc.community.dev/rns-institute-of-technology-bengaluru/" target="_blank" rel="noreferrer"><img alt="GDSC Logo" class="w-48px" src="https://res.cloudinary.com/startup-grind/image/upload/c_fill,dpr_2.0,f_auto,g_center,h_1080,q_100,w_1080/v1/gcs/platform-data-dsc/events/logo_QTdLJEf.jpg"></a>

  [Subramanya Rao](https://github.com/Subramanyarao11) at [GDSC RNSIT](https://gdsc.community.dev/rns-institute-of-technology-bengaluru/)

  - [Source code](https://github.com/Subramanyarao11/gdsc-talk-2)
---

# Deploying Static Sites

Introduction to deploying static sites using GitHub Pages and Netlify

<div class="uppercase text-sm tracking-widest">
Subramanya Rao
</div>

<div class="abs-bl mx-14 my-12 flex">
  <img src="https://res.cloudinary.com/startup-grind/image/upload/c_fill,dpr_2.0,f_auto,g_center,h_1080,q_100,w_1080/v1/gcs/platform-data-dsc/events/logo_QTdLJEf.jpg" class="h-8 mt-2">
  <div class="ml-3 flex flex-col text-left">
     <div><b>Web Development</b> Workshop @ GDSC, RNSIT</div>
    <div class="text-sm opacity-50">Jan. 16th, 2024</div>
  </div>
</div>

<div class="abs-br mx-14 my-12 flex gap-6">
  <a href="https://github.com/Subramanyarao11/gdsc-talk-2" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

---
hideInToc: true
---

# Table of Content

<Toc listClass="!list-disc" maxDepth="2" />

---

# What is Deployment

<div class="grid grid-cols-2 gap-x-4 h-full">
<v-clicks :every='1'>
<div>
 <img class="h-90" src="https://programmerhumor.io/wp-content/uploads/2021/12/programmerhumor-io-frontend-memes-backend-memes-cac4f3397cd51ab.jpg"></img>
</div>
<div>
 <img class="h-90" src="https://programmerhumor.io/wp-content/uploads/2022/12/programmerhumor-io-backend-memes-programming-memes-471d8c817ae7976.jpg"></img>
</div>

<blockquote class="text-base w-full h-fit col-span-2">
<div class="text-base w-full col-span-2">
    <p>Deployment is the process of making a application available to the world through Internet</p>
</div>
</blockquote>
</v-clicks>
</div>




---

# What are Static Sites?

> Static websites are web pages with fixed content that is displayed the same for every user. They are typically built using HTML, CSS, and JavaScript.

<p v-click class="text-xl text-gray-400 underline underline-offset-6 decoration-dotted">Today we will explore 2 ways to deploy sites built with HTML, CSS & JS</p>

<div class="grid grid-cols-2 gap-x-4 h-full my-6">
<v-clicks :every='1'>
  <div>
    <h2>Github Pages</h2>
    <ul>
      <li>GitHub Pages allows you to host your static website directly from your GitHub repository.</li>
      <li>Easy and free hosting for personal, organization, or project pages.</li>
      <li>Supports custom domains.</li>
      <li>
      <a href="https://pages.github.com/" target="_blank">Learn more about Github Pages</a>
      </li>
    </ul>
  </div>

  <div>
    <h2>Netlify</h2>
    <ul>
      <li>Netlify is a powerful platform for deploying modern web projects.</li>
      <li>Provides continuous deployment from Git, including GitHub.</li>
      <li>Offers features like serverless functions, forms, and more.</li>
      <li>
      <a href="https://www.netlify.com/" target="_blank">Learn more about Netlify Hosting</a>
      </li>
    </ul>
  </div>
  </v-clicks>
</div>

---


# Deploying a Simple Page

<p v-click class="text-xl text-gray-100 underline">Let's deploy a simple static page using both GitHub Pages and Netlify.</p>

<div class="grid grid-cols-2 gap-x-4 h-full my-6">
<v-clicks :every='1'>
  <div>
    <h2>Github Pages Deployment</h2>
    <ul>
      <li>Create a new repository on GitHub.</li>
      <li>Add your HTML, CSS, and JS files to the repository.</li>
      <li>Go to the repository settings, scroll down to the GitHub Pages section.</li>
      <li>Choose the branch you want to deploy (e.g., main), and click "Save."
      </li>
    </ul>
  </div>

  <div>
    <h2>Netlify Deployment</h2>
    <ul>
      <li> Sign in to Netlify and click "New Site from Drag and Drop.</li>
      <li> Drag your project folder or files into the designated area.</li>
      <li>Netlify will automatically deploy your site.</li>
      <li>
      <a href="https://www.netlify.com/" target="_blank">Learn more about Netlify Hosting</a>
      </li>
    </ul>
  </div>
  </v-clicks>
</div>


---

# Comparing GitHub Pages and Netlify

<div class="grid grid-rows-2 gap-y-2 h-full my-6">
<v-clicks :every='1'>
  <div>
    <h2 class="text-xl text-gray-400 underline">Github Pages</h2>
    <ul>
      <li>Simple setup for static sites.</li>
      <li>Limited customization options.</li>
      <li>Supports custom domains.</li>
      <li>Directly linked to GitHub repository.</li>
    </ul>
  </div>
  <div>
    <h2 class="text-xl text-gray-400 underline">Netlify</h2>
    <ul>
    <li>Advanced features like serverless functions.</li>
      <li>More customization options than github pages</li>
      <li>Better support for modern web development workflows.</li>
      <li>Can be integrated with github.</li>
    </ul>
  </div>
  </v-clicks>
</div>


---


# Conclusion

<div class="grid grid-rows-2 gap-y-2 h-full my-6">
<v-clicks :every='1'>
  <div>
    <h2 class="text-xl text-gray-400 underline">Why one should deploy their projects ?</h2>
    <ul>
      <li>Deploying your sites makes it accessible to a global audience</li>
      <li>Users from different regions can access your content quickly and efficiently.</li>
      <li>Deploying provides a tangible way to showcase your development skills.</li>
      <li>Share live project URLs for potential clients or employers to view your work.</li>
      <li>Identify and address potential issues related to load times and responsiveness.</li>
    </ul>
  </div>
  <div>
    <h2 class="text-xl text-gray-400 underline">Resources</h2>
    <ul>
    <li>
    <a href="https://www.netlify.com/blog/2016/10/27/a-step-by-step-guide-deploying-a-static-site-or-single-page-app/" target="_blank">Deploy static site on Netlify</a>
    </li>
      <li><a href="https://medium.com/flycode/how-to-deploy-a-static-website-for-free-using-github-pages-8eddc194853b" target="_blank">Deploy static site on Github Pages</a></li>
      <li><a href="https://stefankudla.com/posts/how-to-deploy-a-static-html-css-and-javascript-website-to-vercel" target="_blank">Deploy static site on Vercel</a></li>
      <li><a href="/link.html" target="_blank">Other Static sites hosting provider</a></li>
    </ul>
  </div>
  </v-clicks>
</div>





---
hideInToc: true
layout: statement
---

# Thanks.

<twemoji-evergreen-tree class="text-4xl"  />
<twemoji-evergreen-tree class="text-4xl"  />
<twemoji-woman-superhero class="text-4xl player"  />
<twemoji-evergreen-tree class="text-4xl"  />
<twemoji-evergreen-tree class="text-4xl"  />
<twemoji-evergreen-tree class="text-4xl"  />
<twemoji-alien-monster class="text-3xl alien"  />
<twemoji-evergreen-tree class="text-4xl"  />

<style>
  @keyframes buzz {
    0% {
      transform: translateX(0px) rotate(0deg);
    }
    50% {
      transform: translateX(5px) rotate(12deg);
    }
    100% {
      transform: translateX(0px) rotate(0deg);
    }
  }

  .alien {
    animation: buzz 900ms infinite ease-in-out;
  }

  @keyframes breeth {
    0% {
      transform: translateY(0px);
    }
    50% {
      transform: translateY(-1px);
    }
    100% {
      transform: translateY(0px);
    }
  }

  .player {
    animation: breeth 1500ms infinite ease-in-out;
  }
</style>
