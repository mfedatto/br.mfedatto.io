---
layout: post
comments: true
author: "M. Fedatto"
title: "Redução do lead time de 170 para 20 dias"
excerpt: "Como conduzi a avaliação e promovi mudanças no fluxo de trabalho do time em busca de maior qualidade e produtividade, alcançando uma redução no lead time médio de 170 para 20 dias."
thumbnail: "/assets/img/lead-time-reduction_thumb.jpg"
permalink: "/pagueveloz-serasa/reducao-do-lead-time/"
categories:
- "Cases"
- "Experiência"
tags:
- "case"
- "lead time"
- "scrum"
- "agile"
- "kanban"
- "liderança"
---

<img src="/assets/img/lead-time-reduction.png" alt="{{ page.title }}" />

Quando a [PagueVeloz Serasa](https://pagueveloz.com.br/) me convidou para avaliar a oportunidade para Coordenador de Desenvolvimento de Software, me foi informado que o time estava trabalhando num Kanban com um rítmo acelerado de entrada de novas demandas, levando-os a acreditar que a dinâmica do time não se adequaria ao Scrum. Pra quem só tem martelo todo problema é prego, mas o Scrum é apenas uma das muitas ferramentas que carrego na minha bagagem. Avançamos no processo e fui selecionado.

A oportunidade era híbrida. Morando em São Paulo eu podia escolher entre o escritório da [Serasa Experian](https://serasa.com.br/) no Morumbi ou o excritório da PagueVeloz em Santana. Em ambos casos eu não teria acesso ao time, pois metade estava presencialmente em Blumenau e a outra metade espalhada pelo Brasil.

Já na segunda semana fui a Blumenau me aproximar da parte do time que estava lá, da liderança, meus pares e áreas correlatas, como sustentação, arquitetura, SRE, produtos e negócios. Nessa viagem tive um bom vislumbre do cenário de trabalho do time e da empresa. Me deparei com demandas sendo aceitas ou repriorizadas quase que de hora em hora. Pull requests enferrujando no cavalete. Quem se manifestava por último, fosse nova demanda ou cobrança de demanda já em curso, entrava na frente das demais.

## Quem não chora não mama

Não foi difícil notar que a cultura vigente era a do "quem não chora não mama". A áera demandante que formalizasse seu pedido e ficasse apenas esperando por um retorno ficaria chupando o dedo, sendo preterida até por demandas estratégicas que sequer foram formalizadas.

Mas o desafio não era apenas priorização, a priorização foi apenas o ponto de destaque nesse primeiro momento. Identifiquei muitos desafios:

* O desafio de priorizar era ampliado pela falta de um planejamento de produto a médio e longo prazo.
* O desafio do planejamento era ampliado pela imprevisibilidade no tempo das entregas.
* O desafio da previsibilidade era amplaido pela concentração de demandas nos profissionais que dominavam o produto em questão.
* O desagio da concentração de demandas em proficionais específicos era ampliada pela falta de documentação e detalhamento das user stories, que poderiam favorecer o desenvolvimento por profissionais que ainda não tem a maior proficiência no produto, mas possuem todo o material de apoio necessário para desempenhar bem seu trabalho.
* O desafio da documentação era apliado pela constante mudança nas prioridades, reduzindo drasticamente a disponibilidade dos profissionais a ataur na documentação.

Formou-se a tempestade perfeita. Um círculo vicioso que precisava ser rompido foi a mim que a liderança da tecnologia da empresa confiou esse desafio.

## Tirando a carroça da frente dos bois

A primeira frente que eu decidi focar foi a priorização e planejamento. Entrei em contato com as áreas de negócio que atendíamos para alinhar que os desenvolvedores do meu time seriam orientados a não aceitar demandas que não estivessem formalizadas, e que atenderiam conforme a prioridade definida pelo responsável pelo produto. Nesse momento estávamos sem PO, portanto essa demanda ficou concentrada no PM. Feito esse alinhamento, fiz o acompanhamento diário de perto para me certificar de que essa estratégia estava sendo cumprida, afinal, "a cultura come a estratégia todos os dias no café da manhã" (não foi exatamente isso que Peter Drucker disse, mas foi assim que ficou popular `¯\_(ツ)_/¯`). Como eu já esperava, levou meses para que esse comportamento, até então intrínsico na cultura da empresa, se tornar exceção.

Feito o alinhamento e os envolvidos concentrando as demandas no PM, que dominava o negócio e o produto mas não conseguia dar conta de escrever as user stories no detalhamento necessário dado o momento do time, ficou evidente não conseguiríamos evoluir sem um PO, que já estava em processo de contratação.

Ao fim da minha terceira semana algumas coisas já estávam muito claras:

* O PM apenas repassava as demandas para o time.
  * Não havia análise de prioridade da demanda frente às demais em curso (não havia fila, tudo chegava e era iniciado).
  * Não havia alinhamento com o time sobre a dor a ser resolvida, as demandas eram mastigadas pelo usuário ou pelo líder técnico e o desenvovledor pouco sabia sobre o contexto amplo a ser impactado pelo seu trabalho.
  * Não havia formalização do escopo da demanda, dando margem ampla para extensão do trabalho a ser feito para entregar a demanda.
  * Não havia qualquer estimativa do tempo necessário para entrega da demanda.
* O líder técnico concentrava em si todo o entendimento e análise da demanda, orientando o desenvolvedor da alteração a sesr feita direto em código.
  * 

{% if page.comments %}
<div id="disqus_thread"></div>
<script>
    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://br-mfedatto-io.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
{% endif %}
