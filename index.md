![AntzBanner2](https://github.com/antzGames/antzGames.github.io/assets/10563814/a85fb8cd-8d59-4112-9bbf-d5702825383d)

# Welcome to AntzGames

Play/explore my games and tools at: [https://antzgames.itch.io/](https://antzgames.itch.io/)

Watch my videos here: [https://www.youtube.com/@AntzGames](https://www.youtube.com/@AntzGames)

Keep up to date here: [https://x.com/AntzGames](https://x.com/AntzGames)

_______________
&nbsp;
 

 {% for post in site.posts %}
  <article class="post h-entry" itemscope itemtype="http://schema.org/BlogPosting">
    <h2 class="post-title p-name" itemprop="name headline">
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h2>
    <p class="post-meta">
    <!--<time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time>-->
        <time class="dt-published" datetime="{{ page.date | date_to_xmlschema }}" itemprop="datePublished">
        {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
        {{ post.date | date: date_format }}
      </time>
    </p>
    <div class="share-links">
      {% include sharelinks.html %}
    </div>
    {{ post.content }}
  </article>
  <p>
   &nbsp;<BR>
   <HR>
   &nbsp;<BR>
  </p> 
{% endfor %}
