---
layout: page
title: Johtokunta
tags: johtokunta
---

Lukuvuoden alussa pidettävässä vuosikokouksessa yhdistykselle valitaan
johtokunta, joka huolehtii käytännön toiminnasta. Johtokunta kokoontuu
lukuvuoden aikana muutaman kerran, joko kasvotusten Martin koulun
tiloissa, taikka etänä.

Toivomme lisää huoltajia mukaan toimintaan joko johtokuntaan taikka
"apukäsiksi" tapahtumiin.
Kaikki koulun oppilaiden huoltajat ovat tervetulleita mukaan kokouksiin.

{% for jasen in site.johtokunta %}
### {{ jasen.name }}
<span class="vanhis-position">{{ jasen.position }}</span>

{{ jasen.content }}

{% endfor %}
