---
---

# Welcome

## Games
{% for game in site.games %}
  <div class="game">
    <h3>{{ game.title }}</h3>
    {{ game.excerpt | remove: '<p>' | remove: '</p>' }}
  </div>
{% endfor %}

<style>
  .game {
    background: cornsilk;
    width: 50%;
  }
</style>
