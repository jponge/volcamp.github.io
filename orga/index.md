---
layout: default
title: Volcamp - Sponsors
---
<section class="page-header" style="background-image:url(https://www.volcamp.io/asset/images/chainedespuys_header.jpg);">
    <div class="container">
        <div class="row justify-content-center">
            <div class="col-lg-8">
                <div class="content text-center">
                    <h1 class="mb-3 text-white text-capitalize letter-spacing">L'équipe</h1>
                    <div class="divider mx-auto mb-4 bg-white"></div>
                </div>
            </div>
        </div>
    </div>
</section>
<section class="section-speaker section">
    <div class="container">
        <div class="row section-heading">
            <div class="col-lg-8">
                <div class="heading">
                    <div class="pl-90">
                        <h2>Les Organisateurs</h2>
                    </div>
                </div>
            </div>
        </div>
        <div class="row">
            <div class="col-lg-12">
                <p>
                Volcamp est organisée par une équipe de bénévoles membres de Geek&Terroir, une association loi 1901, créée pour cet événement.
                </p>
            </div>
        </div>
        <div class="row">
        {% for member in site.data.crew %}
            <div class="col-lg-4">
                <img src="{{ site.baseurl }}/asset/images/orga/{{ member.photo }}" alt="{{ member.name }}" class="float-left orga">{{ member.name }}<br><br>
                <a href="https://twitter.com/{{ member.twitter }}" class="tw"><i class="icon-twitter"></i>{{ member.twitter }}</a><br>
                <a href="https://www.linkedin.com/in/{{ member.linkedin }}" class="lnked"><i class="icon-linkedin-squared"></i>{{ member.linkedin }}</a>
            </div>
        {% endfor %}
        </div>
    </div>
</section>