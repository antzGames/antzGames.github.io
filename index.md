![AntzBanner2](https://github.com/antzGames/antzGames.github.io/assets/10563814/a85fb8cd-8d59-4112-9bbf-d5702825383d)

# Welcome to AntzGames

Play/explore my games and tools at: [https://antzgames.itch.io/](https://antzgames.itch.io/)

 {% for post in site.posts %}
  <article>
    <h2>
      <a href="{{ post.url }}">
        {{ post.title }}
      </a>
    </h2>
    <time datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date_to_long_string }}</time>
    {{ post.content }}
  </article>
{% endfor %}
