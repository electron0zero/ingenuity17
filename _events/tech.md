---
layout: category
title:  "Technical"
subtitle: "Hello World"
top-word: "Explore"
image: "img/events/te.png"
date:   2015-04-21 12:12:12
---
<section class="no-padding" id="portfolio">
    <div class="container-fluid">
        <div class="row no-gutter">
            {% for tech in site.tech %}
                <div class="col-lg-4 col-sm-6" style="padding: 5px;">
                    <a href="{{ tech.url }}" class="portfolio-box">
                        <img src="{{ tech.image }}" class="img-responsive" alt="tech Image">
                        <div class="portfolio-box-caption">
                            <div class="portfolio-box-caption-content">
                                <div class="project-category text-faded center aclonica">
                                    {{ tech.subtitle }}
                                </div>
                                <div class="project-name center aclonica">
                                    {{ tech.title }}
                                </div>
                            </div>
                        </div>
                    </a>
                </div>
            {% endfor %}
        </div>
    </div>
</section>