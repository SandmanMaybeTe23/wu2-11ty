---
title:me
layout:layout.html
---


<ul>
{% for person in persons.items%}
    <li>
        <h3>{{person.name}}</h3>
        <p>{{person.potion}}</p>
        <img src="/img/{{person.picture}}">
     </li>    
{% endfor %}    
</ul>

