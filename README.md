# FreshersTask

## my content

text- alignmnet
view helpder

[a home](Home.md)

[a newhome](newHome.md)

<nav>
  <ul>
    {% for item in site.navigation %}
      <li>
        <a href="{{ item.url }}">{{ item.text }}</a>
      </li>
    {% endfor %}
  </ul>
</nav>
