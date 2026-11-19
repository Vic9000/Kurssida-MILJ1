---
tags:
  - milj1
  - admin
draft: "true"
---
```base
views:
  - type: table
    name: View
    filters:
      and:
        - file.hasTag("milj1")
        - file.hasTag("admin")
    order:
      - file.name
      - grp1
      - grp2
      - grp3
      - grp4
      - grp5
      - grp6
      - grp7

```
