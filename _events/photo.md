---
layout: category
title:  "Photography"
subtitle: "Looking through the glasses"
top-word: "Explore"
image: "img/events/pht.png"
date:   2015-04-21 12:12:12
---
<section class="no-padding" id="portfolio">
    <div class="container-fluid">
        <div class="row no-gutter">
            {% for photos in site.photo %}
                <div class="col-lg-4 col-sm-6" style="padding: 5px;">
                    <a href="{{ photos.url }}" class="portfolio-box">
                        <img src="{{ photos.image }}" class="img-responsive" alt="tech Image">
                        <div class="portfolio-box-caption">
                            <div class="portfolio-box-caption-content">
                                <div class="project-category text-faded center aclonica">
                                    {{ photos.subtitle }}
                                </div>
                                <div class="project-name center aclonica">
                                    {{ photos.title }}
                                </div>
                            </div>
                        </div>
                    </a>
                </div>
            {% endfor %}
        </div>
    </div>
</section>