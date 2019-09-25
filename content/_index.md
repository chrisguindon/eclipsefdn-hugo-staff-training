---
title: "Home"
seo_title: "EclipseFdn Hugo Staff Training"
headline: "EclipseFdn Hugo Staff Training"
description: "Demo website for my Contributing Website Content training session to EclipseFdn staff."
tagline: "Demo website for my Contributing Website Content training session to EclipseFdn staff."
hide_page_title: true
hide_sidebar: true
hide_breadcrumb: true
show_featured_story: true
date: 2019-09-10T15:50:25-04:00
layout: "single"
---

Hey, this is Anne.

<div class="row margin-top-50">
  <div class="col-sm-12 news-list">
    {{< taxonomy_list taxonomy="categories" section="news" term="announcements" >}} 
       <ul class="list-inline news-list-links">
        <li class="news-list-links-view-all"><a href="categories/announcements">View all</a></li>
        <li class="news-list-links-rss"><a href="news/index.xml" title="Subscribe to our RSS-feed">Subscribe to our RSS-feed <i class="fa fa-rss"></i></a></li>
      </ul>
  </div>
  <div class="col-sm-12 news-list">
    {{< taxonomy_list taxonomy="categories" section="news" term="community-news" >}}
      <ul class="list-inline news-list-links">
        <li class="news-list-links-view-all"><a href="categories/community-news">View all</a></li>
        <li class="news-list-links-rss"><a href="news/index.xml" title="Subscribe to our RSS-feed">Subscribe to our RSS-feed <i class="fa fa-rss"></i></a></li>
      </ul>
  </div>
</div>
