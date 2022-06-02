Tenhle blog bude hlavně o tom, co zrovna programuju a taky co hraju.

Články nemají žádný řád a nikdy mít nebudou (tak jo možná až budu vědět co dělám) někdy krátký někdy nespisovný atd. Toto jsou jen moje náhodné myšlenky, které mi lítají v hlavě.

Můj úkol je vydat alespoň jeden článek za měsíc, ale uvidím.

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.content }}
      </div>
    </article>
  {% endfor %}
</div>