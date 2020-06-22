---
title: Ubuntu_Labe
subtitle: Programa de inovação aberta em cidades inteligentes para a redução da desigualdade racial no Rio de Janeiro.
layout: layouts/base.njk
---

## Dia 26 de junho teremos nossa sessão de abertura!


O programa do Ubuntu Labe é transformador e pretende inspirar pessoas negras e pardas e desenvolverem projetos com Impacto Positivo para a cidade do Rio de Janeiro.

Em busca de informação sobre o projeto? Sinta-se livre para entrar em contato pelos nossos canais abaixo:

[Instagram](https://www.instagram.com/ubuntulabe/) | [WhatsApp](https://chat.whatsapp.com/FoFtt1Wwim2JnmnUeVCznn) | [Mande um e-mail!](mailto:ubuntulab@pet.coppe.ufrj.br)



## Saiba mais sobre o programa!

<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a>
    <!-- <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time> -->
  </li>
{%- endfor -%}
</ul>




