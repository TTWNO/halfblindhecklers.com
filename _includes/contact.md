<div id="contact">
  <p>You can message us and follow us at the following locations:</p>
  <ul>
    {% for cc in site.data.contact %}
      <li>{{ cc.pretext }} <a href="{{ cc.link }}">{{ cc.linktext }}</a></li>
    {% endfor %}
  </ul>
</div>
