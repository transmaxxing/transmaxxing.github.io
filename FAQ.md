---
layout: default
nav_order: 7
---

# Frequently Asked Questions

<style type="text/css">
img {
    max-height: 500px;
    height: 100%;
    width: auto;
}
</style>

{% for faq in site.data.faq -%}
<details>
<summary><b>{{ faq.question }}</b></summary>

{{ faq.answer }}
{% if faq.image %}
<br>
<img src="{{ faq.image }}" alt="" title="">
{% endif %}

</details>
{%- endfor -%}