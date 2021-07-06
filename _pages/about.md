---
title: About Me
description: "Anang Sahroni is geophysics student and Python developer"   
about: true
permalink: /about
nav: about
--- 

<figure class="about-picture"><img src="" alt="" title="Anang Sahroni" id="aboutImg"><figcaption id="aboutImgCaption"></figcaption>
</figure>

<noscript>
<figure class="about-picture"><img src="https://res.cloudinary.com/dm62lnxoi/image/upload/c_scale,h_400/v1625550199/blog/default_wyi86g.jpg" alt="" title="Anang Sahroni">
<figcaption>That’s me</figcaption></figure>
</noscript>

I’m a geophysics student and part time Python developer: studying earth rumbles and dynamics using physics, coding scientific softwares, and building websites with Python.

🤓&emsp;Student<br>
🌏&emsp;Earth science<br>
📚&emsp;Physics<br>
👨‍💻&emsp;Codes<br>
⚽&emsp;Football<br> 
🇮🇩&emsp;Live in Indonesia<br>

## Contact 

📫&emsp;{{ site.email }}

💬&emsp;You can find me on [LinkedIn](https://www.linkedin.com/in/anang-sahroni), [Twitter](https://twitter.com/anangsahroni) and [GitHub](https://github.com/anangsahroni). 


## Colophon 

This is a [small b blog](https://tomcritchlow.com/2018/02/23/small-b-blogging/). It's meant to be lighthearted, rough around the edges and an ongoing work in progress. Blog articles mostly written in Bahasa Indonesia but i am on my way to make this website work both for English and Bahasa Indonesia.

I use [Jekyll](https://jekyllrb.com) to build a static site and adapting/forking/copying/and modifying beautiful, simple, and elegant theme from Derek Kedziora: [source code on GitHub](https://github.com/derekkedziora/derekkedziora.com) or [blog](https://derekkedziora.com/).

<script>
const photos = [
"https://res.cloudinary.com/dm62lnxoi/image/upload/c_scale,h_400/v1625550452/blog/traditional_c_epwtj3.png", 
"https://res.cloudinary.com/dm62lnxoi/image/upload/c_scale,w_400/v1625550453/blog/earth1_c_rfvv4i.png", 
"https://res.cloudinary.com/dm62lnxoi/image/upload/c_scale,w_400/v1625550200/blog/sea_ve6mye.jpg",
"https://res.cloudinary.com/dm62lnxoi/image/upload/c_scale,h_400/v1625550200/blog/vulcano1_fiwbjv.jpg",
"https://res.cloudinary.com/dm62lnxoi/image/upload/c_scale,h_400/v1625550199/blog/default_wyi86g.jpg"
]

const captions = [
"Me in traditional javanese clothes",
"In my element (volcano)",
"Not in my element (sea)",
"In front of Merapi Volcano",
"Default me"
]

const selectedPhoto = Math.floor(Math.random() * photos.length)

document.getElementById("aboutImg").setAttribute("src", photos[selectedPhoto]);
document.getElementById("aboutImgCaption").innerHTML = captions[selectedPhoto];
</script>