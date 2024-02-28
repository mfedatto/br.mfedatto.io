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
