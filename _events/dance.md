---
layout: category
title:  "Dance"
image: "img/b.jpg"
date:   2015-04-21 12:12:12
---

<section class="no-padding" id="portfolio">
    <div class="container-fluid">
        <div class="row no-gutter">
            {% for dance in site.dance %}
                <div class="col-lg-4 col-sm-6">
                    <a href="{{ dance.url }}" class="portfolio-box">
                        <img src="{{ dance.image }}" class="img-responsive" alt="Dance Image">
                        <div class="portfolio-box-caption">
                            <div class="portfolio-box-caption-content">
                                <div class="project-category text-faded">
                                    {{ dance.subtitle }}
                                </div>
                                <div class="project-name">
                                    {{ dance.title }}
                                </div>
                            </div>
                        </div>
                    </a>
                </div>
            {% endfor %}
        </div>
    </div>
</section>