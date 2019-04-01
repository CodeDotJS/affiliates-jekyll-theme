---
layout: page
title: "Opinion"
---

<section class="featured-posts">

    <div class="section-title">

    </div>

    <div class="row listfeaturedtag">

    {% for post in site.posts %}

        {% if post.opinion == true %}

            {% include featuredbox.html %}

        {% endif %}

    {% endfor %}

    </div>

</section>
