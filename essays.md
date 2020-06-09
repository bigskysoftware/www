---
layout: layout.html
---

## Essays

<div>
<ul> 
{%- for essay in collections.essay reversed -%}
<li>
  <a href="{{ essay.url  }}">{{ essay.data.title }}</a>
</li>
{%- endfor -%}
  </ul>
</div>
