---
layout: category
title:  "Music"
subtitle: "It Feels"
top-word: "Explore"
image: "img/events/mu.jpg"
date:   2015-04-21 12:12:12
---
<section class="no-padding" id="portfolio">
    <div class="container-fluid">
        <div class="row no-gutter">
            {% for music in site.music %}
                <div class="col-lg-4 col-sm-6" style="padding: 5px;">
                    <a href="{{ site.baseurl }}{{ music.url }}" class="portfolio-box">
                        <img src="{{ music.image }}" class="img-responsive" alt="music Image">
                        <div class="portfolio-box-caption">
                            <div class="portfolio-box-caption-content">
                                <div class="project-category text-faded center aclonica">
                                    {{ music.subtitle }}
                                </div>
                                <div class="project-name center aclonica">
                                    {{ music.title }}
                                </div>
                            </div>
                        </div>
                    </a>
                </div>
            {% endfor %}
        </div>
    </div>
</section>
