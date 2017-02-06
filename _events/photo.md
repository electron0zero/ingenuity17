---
layout: category
title:  "Photography"
image: "img/events/ph.jpg"
date:   2015-04-21 12:12:12
---
<section class="no-padding" id="portfolio">
    <div class="container-fluid">
        <div class="row no-gutter">
            {% for photo in site.photo %}
                <div class="col-lg-4 col-sm-6">
                    <a href="{{ photo.url }}" class="portfolio-box">
                        <img src="{{ photo.image }}" class="img-responsive" alt="photo Image">
                        <div class="portfolio-box-caption">
                            <div class="portfolio-box-caption-content">
                                <div class="project-category text-faded">
                                    {{ photo.subtitle }}
                                </div>
                                <div class="project-name">
                                    {{ photo.title }}
                                </div>
                            </div>
                        </div>
                    </a>
                </div>
            {% endfor %}
        </div>
    </div>
</section>