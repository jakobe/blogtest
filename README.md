<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | prepend:site.baseurl }}">{{ post.title }} {{post.date | date_to_long_string}}</a>
    </li>
  {% endfor %}
</ul>