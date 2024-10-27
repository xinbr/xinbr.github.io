---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

* _I am currently a graduate student in the College of Civil Engineering at Hunan University, supervised by [Prof. Chao Zhang](https://www.researchgate.net/profile/Chao-Zhang-43). I joined Prof. Zhang's [UNSAT lab](https://chaozhanghnu.github.io) in 2021 as a 3-rd year undergraduate student, and completed my B.S. degree in 2020 at the same institution.

* _My passion lies in comprehending the diverse and intriguing phase equilibrium and transition processes of water in porous media, as well as water droplets, and unraveling their implications on the behaviour of frozen porous materials. I am try to integrate cutting-edge insights from surface and interfacial science, nucleation theory, and soil-water interaction theory, while utilizing advanced microscopic experiments (e.g., X-ray wide/small-angle scattering, infrared spectroscopy, high-speed photography, etc.) to delve into the physics of pore water freezing, ice propagation dynamics, unfrozen water behavior in frozen soil, and the fundamental mechanisms at play. 
* _Within Prof. Zhang's diverse and engaging research group, I have had the invaluable opportunity to deeply participant in various intriguing research topics, such as vapor sorption and capillary condensation in soil (Shaojie Hu), desiccation cracking in porous media (Yuhan Yang), isotope fractionation (Lijun Li), and flow in porous media (Lingyun Gou). My fellow group members are the most incredible, talented, and beautiful partners ever.

* If you are interested in my research, please get in touch with me via email (yhyang@hnu.edu.cn) or [WeChat](../images/wechat.jpg). 

News
======
**Conference(12/24):** I will attend the _AGU Annual Meeting_ and give an oral presentation or a poster titled "Nucleation-percolation transition in clay desiccation cracking".

**Conference(08/24):** I attended the _IUTAM Symposium Interface Mechanics of Complex Flows and Soft Matter_ and presented a poster.

**Patent(06/24):** Our patent was granted (CN202410502010.9), which is about _a new device_ for measuring the fracture toughness of unsaturated clay.

**Conference(06/24):** I attended the _1st International Yuelu Symposium on “Geotechnical and Underground Engineering”_ and presented a poster titled "Fabric, stress, and modulus anisotropies of sands during high-stress oedometer test". 

**Talk(05/24):** I have given an oral presentation about the "Role of substrate roughness in soil desiccation cracking" at _InterPore Annual Meeting_.

**Paper(03/24):** Our paper titled ["Role of substrate roughness in soil desiccation cracking"](https://doi.org/10.1139/cgj-2023-0638) was published in _Canadian Geotechnical Journal_.



<div class="gallery-container">
  <button onclick="prevImage()" class="gallery-button gallery-button-prev"></button>
  <img id="gallery-image" src="../images/Interpore1.jpg" alt="Photo 1" style="max-width: 60%; height: auto;" />
  <button onclick="nextImage()" class="gallery-button gallery-button-next"></button>
</div>

<style>
  .gallery-container {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 5px;
    position: relative;
  }

  .gallery-button {
    width: 50px;
    height: 50px;
    border: none;
    background-color: rgba(255, 255, 255, 0.3); 
    border-radius: 50%; 
    cursor: pointer;
    transition: background-color 0.3s ease;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .gallery-button:hover {
    background-color: rgba(255, 255, 255, 0.5); 
  }

  .gallery-button-prev {
    background: transparent url('../images/LeftArrow.png') no-repeat center;
    background-size: 20px 20px;
  }

  .gallery-button-next {
    background: transparent url('../images/RightArrow.png') no-repeat center;
    background-size: 20px 20px;
  }
</style>

<script>
  const images = [
    "../images/Interpore1.jpg",
    "../images/Interpore2.jpg",
    "../images/Interpore3.jpg",
    "../images/Interface.png"
  ];

  let currentIndex = 0;

  function showImage(index) {
    const imgElement = document.getElementById('gallery-image');
    imgElement.src = images[index];
    imgElement.alt = `Photo ${index + 1}`;
  }

  function nextImage() {
    currentIndex = (currentIndex + 1) % images.length;
    showImage(currentIndex);
  }

  function prevImage() {
    currentIndex = (currentIndex - 1 + images.length) % images.length;
    showImage(currentIndex);
  }
</script>
