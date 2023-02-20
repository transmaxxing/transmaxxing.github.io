---
layout: default
nav_order: 7
---

<style type="text/css">
img.resize {
    max-height: 500px;
    height: 70%;
    width: auto;
}
</style>

# Frequently Asked Questions

{% for faq in site.data.faq -%}
<details>
<summary><b>{{ faq.question }}</b></summary>

{{ faq.answer }}
{% if faq.image %}
<img src="{{ faq.image }}" alt="" title="">
{% endif %}

</details>
{%- endfor -%}