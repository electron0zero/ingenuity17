---
layout: category
title:  "Literary"
subtitle: "Storytellers"
top-word: "Explore"
image: "img/events/li.jpg"
date:   2015-04-21 12:12:12
---
<section class="no-padding" id="portfolio">
    <div class="container-fluid">
        <div class="row no-gutter">
            {% for literary in site.literary %}
                <div class="col-lg-4 col-sm-6" style="padding: 5px;">
                    <a href="{{ literary.url }}" class="portfolio-box">
                        <img src="{{ literary.image }}" class="img-responsive" alt="tech Image">
                        <div class="portfolio-box-caption">
                            <div class="portfolio-box-caption-content">
                                <div class="project-category text-faded center aclonica">
                                    {{ literary.subtitle }}
                                </div>
                                <div class="project-name center aclonica">
                                    {{ literary.title }}
                                </div>
                            </div>
                        </div>
                    </a>
                </div>
            {% endfor %}
        </div>
    </div>
</section>