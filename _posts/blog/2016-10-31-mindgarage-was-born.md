---
layout: post
title:  "MindGarage was Born"
date:   2016-10-31 19:00:00
author: Marcus Liwicki
categories:
- blog
- fun
img: 2016-10-31-mindgarage-was-born.jpg
thumb: default.png
images:
- image_path: /assets/img/blog/2016-10-31-mindgarage-was-born/1.jpg
- image_path: /assets/img/blog/2016-10-31-mindgarage-was-born/2.jpg
- image_path: /assets/img/blog/2016-10-31-mindgarage-was-born/3.jpg
- image_path: /assets/img/blog/2016-10-31-mindgarage-was-born/4.jpg
- image_path: /assets/img/blog/2016-10-31-mindgarage-was-born/5.jpg
- image_path: /assets/img/blog/2016-10-31-mindgarage-was-born/6.jpg
- image_path: /assets/img/blog/2016-10-31-mindgarage-was-born/7.jpg
- image_path: /assets/img/blog/2016-10-31-mindgarage-was-born/8.jpg
- image_path: /assets/img/blog/2016-10-31-mindgarage-was-born/9.jpg
- image_path: /assets/img/blog/2016-10-31-mindgarage-was-born/10.jpg
permalink: /blog/:title/
---

By the end of October 2016 we received the computers and began setting them up as well as moving the last furniture into the MindGarage. Here you find some impressions of our activities!

Thanks for all the volunteers who helped and made everything possible!

<ul class="photo-gallery">
  {% for image in page.images %}
    <li>
    	<a href="{{ image.image_path | prepend: site.baseurl }}" target="_blank">
        <img src="{{ image.image_path }}" alt="">
        </a>
    </li>
  {% endfor %}
</ul>