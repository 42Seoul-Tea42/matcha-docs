```mermaid
---
title: 프론트 디렉토리
---

graph LR

root(page: landing)

root --> auth --> sign(/signup)
auth(/auth) --> login(/login)

root --> home(/home)

home --> nav(layout: nav, footer)
home --> fancy(/fancy)
home --> chat(/chat)
home --> search(/search)
home --> history(/history)
home --> setting(/setting)
home --> loigout(/logout)
```
