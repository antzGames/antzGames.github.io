![AntzBanner2](https://github.com/antzGames/antzGames.github.io/assets/10563814/a85fb8cd-8d59-4112-9bbf-d5702825383d)

# Welcome to AntzGames

Play/explore my games and tools at: [https://antzgames.itch.io/](https://antzgames.itch.io/)

<ul class="entries">
  {% for post in paginator.posts %}
  <li>
    <a href="{{ post.url }}">
    <h3>{{ post.title }}</h3>
    <p class="blogdate">{{ post.date | date: "%d %B %Y" }}</p>
    <div>{{ post.content |truncatehtml | truncatewords: 60 }}</div>
    </a>
  </li>
  {% endfor %}
</ul>
