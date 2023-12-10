<!DOCTYPE html>
<html lang="en">
  {% include head.md %}
  <body>
      {% include header.md %}
      <section id="about">
        {% include about.md %}
      </section>
      <section id="projects">
        {% include projects.md %}
      </section>
        {{ content }}
      {% include footer.md %}
  </body>
