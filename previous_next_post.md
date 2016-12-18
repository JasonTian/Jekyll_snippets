{% if page.previous %}
<a class="prevPost" href="{{ page.previous.url }}" rel="bookmark"><i class="iPrevPost"></i>&laquo; {{ page.previous.title | truncatewords:5 }}</a>
{% endif %}
{% if page.next %}
<a class="nextPost" href="{{ page.next.url }}" rel="bookmark">{{ page.next.title | truncatewords:5 }} &raquo;<i class="iNextPost"></i></a>
{% endif %}
