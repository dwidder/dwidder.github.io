---
layout: page
title: Welcome!
---

I am a student in the [Robert D. Clark Honors College](http://honors.uoregon.edu) at the University of Oregon in Eugene, Oregon studying Computer and Information Science. Right now, I am writing my Undergraduate Thesis  on the programming practices of research programmers, where I am advised by [Professor Stephen Fickas](http://ix.cs.uoregon.edu/~fickas/new_home/). I am excited to move to Pittsburgh in August 2017 to pursue a PhD in Software Engineering at Carnegie Mellon University’s [Institute for Software Research](http://isri.cmu.edu/index.html).

I do [research](/research) at the intersection of Software Engineering and Human Computer Interaction, with an aim to improve Computer Science Education. I was born in [Tillamook, Oregon](https://en.wikipedia.org/wiki/Tillamook,_Oregon) but grew up in Berlin, Germany and Singapore. Apart from my research interests, I enjoy painting, running and rowing.

I am always excited to meet new people and hear about new ideas and opportunities. Feel free to [reach out!](/contact)

<div class="feeds clearfix">
  <div class="feed-container">
    {% for post in site.posts limit:2 %}
      <article class="post">

        <h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>

        <div class="entry">
          <div class="date"> {{ post.date | date_to_long_string }}</div>
          {{ post.excerpt }}
        </div>

        <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
      </article>
    {% endfor %}
  </div><div class="feed-container">
    <a class="twitter-timeline" href="https://twitter.com/davidthewid" data-tweet-limit="2">Tweets by davidthewid</a> <script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>
    <!-- <a class="twitter-timeline"
      href="https://twitter.com/DavidTheWid">
    Tweets by @DavidTheWid
    </a> -->
  </div>  
</div>

<script>window.twttr = (function(d, s, id) {
  var js, fjs = d.getElementsByTagName(s)[0],
    t = window.twttr || {};
  if (d.getElementById(id)) return t;
  js = d.createElement(s);
  js.id = id;
  js.src = "https://platform.twitter.com/widgets.js";
  fjs.parentNode.insertBefore(js, fjs);

  t._e = [];
  t.ready = function(f) {
    t._e.push(f);
  };

  return t;
}(document, "script", "twitter-wjs"));</script>
