# Data-Driven Scholar's Toolkit

{% include css.html %}

{% include nav.html %}

---

Below is a large list of tools arranged by topic if you want to explore either familar tools or go beyond the scope of the course. You are free to incorporate any tool or resource for your projects. Links for online help, popular DH discussion spots, professional associations, journals, blogs, and applied historical tutorials all can help you forge your own path and grow as a scholar long after this class is over.

---

{% for category in site.data.toolkit %}

# {{ category.name }}

<ul>
    {% for item in category.items %}
    <li><a href="{{ item.link }}">{{ item.name }}</a> - {{item.description}}</li>
    {% endfor %}
</ul>

{% endfor %}
