---
layout: default
seo:
  title: First post
  meta-description:
  meta-keywords:
  featured-image_path: https://source.unsplash.com//DuD5D3lWC3c
  hide-from-google: false
title: my first post
description: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
author: Corinne Laing
date: 2022-01-01
featured: true
category: travel
featured_image: https://source.unsplash.com//DuD5D3lWC3c

text-content-block:
    heading: This is a really interesting story
    text: >-
     <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
     <p> Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum </p> 
     <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
     <p> Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum </p>
text-column-block:
    heading: This is a really interesting story
    column1: >-
     <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
     <p> Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum</p>
    column2: >-
     <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
     <p> Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum</p>
    column3: >-
     <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
     <p> Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum</p>
video-content-block:
    video_url: https://www.youtube.com/embed/fUn1w3Vfh6U
    h3: Interesting video
    text: <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
gallery-block:
    - image_url: https://source.unsplash.com/8muZ_2cfX4A
    - image_url: https://source.unsplash.com/8muZ_2cfX4A
    - image_url: https://source.unsplash.com/8muZ_2cfX4A
    - image_url: https://source.unsplash.com/8muZ_2cfX4A
    - image_url: https://source.unsplash.com/8muZ_2cfX4A
    - image_url: https://source.unsplash.com/8muZ_2cfX4A
---

<body class="p-5 leading-6">

<header>
</header>

<section class="text-center">
    <h2>{{page.title}}</h2>
    <h2>{{page.author}}</h2>
    <h3>{{page.date | date: "%a, %b %d, %y"}}</h3>
    <img class="mx-auto" width=800 src="{{page.featured_image}}">
</section>

<!-- text column section -->
<section class="p-5 grid gap-1 grid-cols-3">
    <div class="p-5 space-y-2"> 
        <h3> {{page.text-column-block.heading}}</h3>
        <p>{{page.text-column-block.column1}}</p>
    </div>
    <div class="p-5">
        <p>{{page.text-column-block.column2}}</p>
    </div>
    <div class="p-5">
       <p>{{page.text-column-block.column1}}</p>
    </div>
</section>

<!-- gallery section -->

<section class="p-5 m-px grid grid-cols-3">
    {% for item in page.gallery-block %}
    <div>
        <img src="{{item.image_url}}">
    </div>
    {% endfor %}
</section>

<!-- text block section -->

<div class="p-5">
    <h3> {{page.text-content-block.heading}}</h3>
    <p>{{page.text-content-block.text}}</p>
</div>

<!-- youtube embed section -->

<section class="grid gap-8 grid-cols-2">
    <div style="padding: 56.25% 0,0,0; position: relative;"> 
        <iframe class="mx-auto" src="{{page.video-content-block.video_url}}" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="position:absolute; top:0;left:0;width:100%;height:100%;"></iframe>
    </div>
    <div>
        <h3>{{page.video-content-block.heading}}</h3>
        <p>{{page.video-content-block.text}}</p>
    </div>
    
</section>


<!-- banner -->

<!-- footer -->

</body>