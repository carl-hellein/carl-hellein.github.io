# Various Projects I am working on

- Mixing together some Blender shaders and compositor styles.
- Making a database backend to track mileage and maintenance for a fleet of bicycles.
- Learning Rust to try to make something:
  - Possibly link it to itch.io
  - Looking in to using the Bevy engine.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
