---
layout: home
para:
  -
    name: test1
    value: val1
  -
    name: test2
    value: val2

---


{% assign para = page.para | where: "name", "test1" %}

{{ para.name }}

os9

