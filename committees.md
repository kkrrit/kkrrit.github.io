---
layout: default
title: Komitety
index: 2
column: 1
---

#### Komitet programowy

##### Przewodniczący

Tadeusz Więckowski – Politechnika Wrocławska

##### Wiceprzewodniczący

Józef Modelski – Politechnika Warszawska

##### Członkowie

{% for person in site.data.program %}
- {{person.name}}, <em>{{person.affiliation}}</em>
{% endfor %}


##### Komitet Organizacyjny

{% for person in site.data.organizers %}
{{person.name}},{% endfor %}
