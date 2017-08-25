---
layout: category
title:  "Dramatics"
subtitle: "Express Yourself"
top-word: "Explore"
image: "img/events/dr.jpg"
date:   2015-04-21 12:12:12
---
<section class="no-padding" id="portfolio">
    <div class="container-fluid">
        <div class="row no-gutter">
            {% for drama in site.drama %}
                <div class="col-lg-4 col-sm-6" style="padding: 5px;">
                    <a href="{{ site.baseurl }}{{ drama.url }}" class="portfolio-box">
                        <img src="{{ drama.image }}" class="img-responsive" alt="drama Image">
                        <div class="portfolio-box-caption">
                            <div class="portfolio-box-caption-content">
                                <div class="project-category text-faded center aclonica">
                                    {{ drama.subtitle }}
                                </div>
                                <div class="project-name center aclonica">
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
