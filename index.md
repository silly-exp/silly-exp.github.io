# index.md

lien

<a href="/_documents/patates/patates.html"> patates <a>

<ul>
  {% for doc in site.documents %}
    <li>
      <h2><a href="{{ doc.url }}">{{ doc.title }}</a></h2>
      <p>{{ doc.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
