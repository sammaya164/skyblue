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


{{ page.para | find: "name", "test2" }}


os6

