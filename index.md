---
layout: default
---

# $ sudo pacman -S aboutThisPage
{:id="about"}

Bienvenido a SHOKUSHUU.

Soy TX187, programador que experimenta con distintos tipos de ramas y estudios dentro de la academia como es el arte, los videojuegos y la música.

Desde niño estoy obsesionado con las computadoras y todo lo relacionado con la tecnología, me he interiorizado en distintos tipos de ramas relacionadas a la tecnología como es la programación, el diseño digital, la comunicación digital, los videojuegos y la música electrónica.

También me considero un adicto a la cultura japonesa, más que nada por el anime, los videojuegos y música. Me siento "en familia" con esa cultura y/o país ya que son excesivamente fanáticos por la tecnología y todo lo que involucra.

En este sitio web encontrarás todo tipo de contenido que genere en el transcurso de mi vida virtual, ya sea scripts, códigos, artículos, música y videos.

Siéntete libre de visitar todo.

# $ cat contact.txt
{:id="contact"}

I think that all about this theme is intuitive, but if you want help, please, contact me: [gjuniioor](https://github.com/gjuniioor).

# $ cat posts.txt
{:id="posts"}

<ul>
{% for post in site.categories.posts %}

{% if post.en %}
<li>{{ post.title }} :: <a href="{{ post.url }}" title="{{ post.description }}">en</a> :: <a href="{{ post.pt }}" title="{{ post.description_pt }}">pt_br</a></li>
{% endif %}

{% endfor %}
</ul>

# $ cat articles.txt
{:id="articles"}

<ul>
{% for post in site.categories.articles %}

{% if post.en %}
<li>{{ post.title }} :: <a href="{{ post.url }}" title="{{ post.description }}">en</a> :: <a href="{{ post.pt }}" title="{{ post.description_pt }}">pt_br</a></li>
{% endif %}

{% endfor %}
</ul>
