---
layout: homepage
---

<span style="font-family:Geneva;color:green;font-weight:700;font-size:20px"> 
## About Me

I am an Integrated PhD student at the Indian Institute of Science, Bangalore, India.

## Research Interests

- **Biophysics**
- **Condensed Matter Physics**

{% for page in site.pages %}
    <a href={{ page.resources.md }}>{{ page.title }}</a>
{% endfor %}

</span>
