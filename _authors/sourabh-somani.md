---
title: "Sourabh Somani"
layout: default
permalink: "/author/sourabh-somani"
---
<div class="container">
<div class="row justify-content-center">
    <div class="col-md-8">        
        <div class="row align-items-center mb-5">
            <div class="col-md-9">
                <h2 class="font-weight-bold">{{page.title}} <span class="small btn btn-outline-success btn-sm btn-round"><a href="{{ site.authors.sourabh.twitter }}">Follow</a></span></h2>
                <p><a href="{{ site.authors.sourabh.site }}">{{ site.authors.sourabh.site }}</a></p>
                <p class="excerpt">{{ site.authors.sourabh.bio }}</p>
            </div>
            <div class="col-md-3 text-right">
                <img alt="{{ site.authors.sourabh.name }}" src="{{site.baseurl}}/{{ site.authors.sourabh.avatar }}" class="rounded-circle" height="100" width="100">
            </div>
        </div>
        <h4 class="font-weight-bold spanborder"><span>Posts by {{page.title}}</span></h4>
            {% assign posts = site.posts | where:"author","sourabh" %}
            {% for post in posts %}
                <div class="mb-5 d-flex justify-content-between main-loop-card">
                    <div class="pr-3">
                        <h2 class="mb-1 h4 font-weight-bold">
                        <a class="text-dark" href="{{site.baseurl}}{{post.url}}">{{ post.title }}</a>
                        </h2>
                        <small class="d-block text-muted">
                            In <span class="catlist">
                            {% for category in post.categories %}
                            <a class="text-capitalize text-muted smoothscroll" href="{{site.baseurl}}/categories.html#{{ category | downcase }}">{{ category }}</a><span class="sep">, </span>
                            {% endfor %}
                            </span>
                        </small>
                        <small class="text-muted">
                            {{ post.date | date: '%b %d, %Y' }}
                        </small>
                    </div>
                    {% if post.image %}
                        <div class="col-md-3 pr-0 text-right">
                        <a href="{{site.baseurl}}{{post.url}}">
                        <img class="w-100" src="{% if post.image contains "://" %}{{ post.image }}{% else %}{{ post.image | absolute_url }}{% endif %}" alt="{{ post.title }}">
                        </a>
                        </div>
                    {% endif %}
                </div>
            {% endfor %}
    </div>
</div>
</div>