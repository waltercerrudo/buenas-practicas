---  
layout: home  
title: Bienvenido a mi sitio  
list_title: Publicaciones recientes  
---  
<nav>  
  <ul class="categories-menu">  
    {% assign categories = site.categories %}  
    {% for category in categories %}  
      <li><a href="{{ '/categories/' | append: category[0] | relative_url }}">{{ category[0] | capitalize }}</a></li>  
    {% endfor %}  
  </ul>  
</nav>  