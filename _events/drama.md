---
layout: category
title:  "Dramatics"
top-word: "Explore"
image: "img/events/dr.jpg"
date:   2015-04-21 12:12:12
---
<section class="no-padding" id="portfolio">
    <div class="container-fluid">
        <div class="row no-gutter">
            {% for drama in site.drama %}
                <div class="col-lg-4 col-sm-6">
                    <a href="{{ drama.url }}" class="portfolio-box">
                        <img src="{{ drama.image }}" class="img-responsive" alt="drama Image">
                        <div class="portfolio-box-caption">
                            <div class="portfolio-box-caption-content">
                                <div class="project-category text-faded">
                                    {{ drama.subtitle }}
                                </div>
                                <div class="project-name">
                                    {{ drama.title }}
                                </div>
                            </div>
                        </div>
                    </a>
                </div>
            {% endfor %}
        </div>
    </div>
</section>
