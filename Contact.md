---
layout: demotemplate
---

{% for item in site.data.titanic %} 
1. {{item.Name}},  {{item.Age}} 
{% endfor %}