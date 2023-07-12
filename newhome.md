<nav>
<ul>
  <li><a href="../../home">Home</a></li>
  <li><a href="news.asp">News</a></li>
  <li><a href="contact.asp">Contact</a></li>
  <li><a href="about.asp">About</a></li>
</ul>
</nav>

<nav>
  <ul>
    {% for item in site.navigation %}
      <li>
        <a href="{{ item.url }}">{{ item.text }}</a>
      </li>
    {% endfor %}
  </ul>
</nav>
