---
layout: demotemplate
---

gunjanmaheshwari.hg@gmail.com

{% for item in site.data.titanic %} 
- {{item.Name}}, {{item.Age}} 
{% endfor %}