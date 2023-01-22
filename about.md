---
layout: page
title: Um félagið
permalink: /about/
order: 6
---

Gagnaglímufélag Íslands (661021-2170) var stofnað 14. september, 2021, en hafði þá starfað í óformlegri mynd frá árinu 2020. Aðalmarkmið félagsins er að halda utan um þátttöku Íslands í Netöryggiskeppni Evrópu, *European Cybersecurty Challenge* (ECSC). Félagið sér um framkvæmd Netöryggiskeppni Íslands, *Gagnaglímunnar*, sem notuð er til að velja keppnishóp Íslands fyrir ECSC. GGFÍ sinnir einnig þjálfun keppnishópsins og stendur einnig fyrir öðrum viðburðum tengdum netöryggi, sem samrýmast markmiði GGFÍ um að efla þekkingu og færni á sviði netöryggis á Íslandi.

### Stjórn félagsins

Stjórn Gagnaglímufélags Íslands skipa

<div class="board">
{% for member in site.data.board.members %}
    <div class="board-member">
        <span class="member-name">{{ member.name }}</span>,
        <span class="member-role"> {{ member.role }} </span>
    </div>
{% endfor %}
</div>

Stjórn þessi var kosin á síðasta aðalfundi GGFÍ, þann {{ site.data.board.formed }}.

### Merki félagsins

Merki gagnaglímufélagsins sækir innblástur til galdrastafsins gapaldurs. Gapaldur var einn tveggja galdrastafa sem notaðir voru við glímugaldur, en glímukappar rituðu þá stafinn á blað eða ristu á spón og lögðu undir hæl hægri fótar. Galdurinn átti þá að tryggja glímukappanum sigur undir ákveðnum kringumstæðum.
