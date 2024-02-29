# Quem sou eu?

Sou coordenador de desenvolvimento de software experiente, com histórico comprovado na liderança de transformações ágeis e no fornecimento de soluções de software de alta qualidade. Minha experiência reside na liderança de equipes, gerenciamento de projetos e na promoção de uma cultura de colaboração e inovação. Com paixão por tecnologia e dedicação à melhoria contínua, prospero em ambientes dinâmicos onde posso causar um impacto significativo.

## Cases

<ul>
    {% for post in site.posts %}
    {% if post.categories contains "Cases" %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      {{ post.excerpt }}
    </li>
    {% endif %}
    {% endfor %}
</ul>

<script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-element-bundle.min.js"></script>
<swiper-container>
  <swiper-slide>Slide 1</swiper-slide>
  <swiper-slide>Slide 2</swiper-slide>
  <swiper-slide>Slide 3</swiper-slide>
  <swiper-slide>Slide ...</swiper-slide>
</swiper-container>
