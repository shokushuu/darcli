---
layout: default
---

# $ sudo pacman -S Posts
{:id="posts"}

<ul>
{% for post in site.categories.posts %}

{% if post.en %}
<li>{{ post.title }} :: <a href="{{ post.url }}" title="{{ post.description }}">leer</a></li>
{% endif %}

{% endfor %}
</ul>

# $ sudo pacman -S Artículos
{:id="articles"}

<ul>
{% for post in site.categories.articles %}

{% if post.en %}
<li>{{ post.title }} :: <a href="{{ post.url }}" title="{{ post.description }}">leer</a></li>
{% endif %}

{% endfor %}
</ul>

# $ sudo pacman -S SobreTX187
{:id="about"}

Soy TX187, programador, adicto (obsesionado) por las computadoras y la tecnología. 
En el año 2004 conocí y experimenté todo lo relacionado a Linux y sus distribuciones, inicié con Mandrake y luego con el nacimiento de Ubuntu empecé a sentir una pasión más fuerte sobre lo que es Linux y software libre.

Mis otros gustos son el anime, los videojuegos, la música, la cocina, la cultura denpa y la literatura.

#### Información para nerds:
◕ Laptops: 2
<br>◕ SO: Manjaro Linux y Windows 7
<br>◕ Consoles: PlayStation 3 (hackeada), Super Nintendo (mod para super famicom), PS One (en proceso de reparación)
<br>◕ Lenguajes: Python, Java, Javascript, C#, Ruby
<br>◕ Móvil: HTC One m7

# $ sudo pacman -S ContactoTX187
{:id="contact"}
  
  ◕ mail: merz.bow@protonmail.com
  <br>◕ IRC: tx187 en rizon.net
  <br>◕ Twitter: [tx187](https://twitter.com/tx187) (español e inglés)
  <br>◕ Twitter: [cosmicdeath1111](https://twitter.com/cosmicdeath1111) (japonés) 
  <br>◕ Discord: Shokushuu#1800
  <br>◕ github: [shokushuu](https://github.com/shokushuu)
