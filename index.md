---
layout: home
title: ""
author_profile: true
---

Welcome to My Personal Website
=============================

I'm **Rejane Paulino**, a PhD candidate in Biosystems Engineering at Mississippi State University, specializing in aquatic remote sensing.

<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.css"/>

<div class="swiper mySwiper">
  <div class="swiper-wrapper">

    <div class="swiper-slide">
      <img src="{{ '/assets/images/slide_1.jpg' | relative_url }}">
    </div>

    <div class="swiper-slide">
      <img src="{{ '/assets/images/slide_2.png' | relative_url }}">
    </div>

    <div class="swiper-slide">
      <img src="{{ '/assets/images/slide_3.jpg' | relative_url }}">
    </div>

    <div class="swiper-slide">
      <img src="{{ '/assets/images/slide_4.jpg' | relative_url }}">
    </div>

    <div class="swiper-slide">
      <img src="{{ '/assets/images/slide_5.jpg' | relative_url }}">
    </div>

    <div class="swiper-slide">
      <img src="{{ '/assets/images/slide_6.jpg' | relative_url }}">
    </div>

    <div class="swiper-slide">
      <img src="{{ '/assets/images/slide_7.jpg' | relative_url }}">
    </div>

    <div class="swiper-slide">
      <img src="{{ '/assets/images/slide_8.jpg' | relative_url }}">
    </div>

    <div class="swiper-slide">
      <img src="{{ '/assets/images/slide_9.jpg' | relative_url }}">
    </div>

    <div class="swiper-slide">
      <img src="{{ '/assets/images/slide_10.jpg' | relative_url }}">
    </div>

    <div class="swiper-slide">
      <img src="{{ '/assets/images/slide_11.png' | relative_url }}">
    </div>

  </div>
</div>

<script src="https://cdn.jsdelivr.net/npm/swiper@10/swiper-bundle.min.js"></script>

<script>
  new Swiper(".mySwiper", {
    loop: true,
    spaceBetween: 30,
    centeredSlides: true,
    autoplay: {
      delay: 3500,
      disableOnInteraction: false,
    }
  });
</script>
