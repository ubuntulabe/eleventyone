---
title: Ubuntu_Labe
subtitle: Programa de inovação aberta em cidades inteligentes para a redução da desigualdade racial no Rio de Janeiro.
layout: layouts/base.njk
---

## As inscrições ao nosso programa estão abertas e encerram dia 14 de Junho! 
### [Clica aqui para acessar o formulário de inscrição!](https://docs.google.com/forms/d/e/1FAIpQLSd_HZLW_CTgWbgV8Bm4nCDupwNf6BIrVEwaI1LJUzrY_1dm_A/viewform)


O programa do Ubuntu Labe é transformador e pretende inspirar pessoas negras e pardas e desenvolverem projetos com Impacto Positivo para a cidade do Rio de Janeiro.

Se você quer participar mas tem algumas limitações, entre em contato pelas nossas redes! 

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




