# Various Projects I am working on

- Mixing together some Blender shaders and compositor styles.
- Making a database backend to track mileage and maintenance for a fleet of bicycles.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
