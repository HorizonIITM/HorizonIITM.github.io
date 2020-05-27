---
layout: gallery
title: Gallery
permalink: /gallery/

---
{% assign sorted_photos = site.gallery | sort: "weight" %}
{% assign rsorted= sorted_photos | reverse %}
<div class="photo-gallery">
<ul>
  {% for image in rsorted %}
    <div class='gbox'>
        <li >
            <div class='gtext'>
                <span>
                        <span class='title'>
                        {{ image.title }} </span>
                    {% if image.description %}
                        <span class='desc'>- {{ image.description }}</span>
                    {% endif %}
                </span>
            </div>
            <img src="{{ image.image_path }}" alt="{{ image.title}}"/>
        </li>
    </div>
  {% endfor %}
</ul>
</div>