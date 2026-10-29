Heimasíða Gagnaglímufélags Íslands
==================================

Heimasíða [Gagnaglímufélags Íslands](https://ggfi.is), byggð með
[Zola](https://www.getzola.org/). 

Fannstu eitthvað að? Langar þig að bæta einhverju við? Ekki hika við að senda inn breytingatillögu!

## Staðbundin þróun

Settu upp þá útgáfu af Zola sem er tilgreind í `.zola-version`.
Zola sér um alla byggingu vefsins. Engar viðbótarskriftur eða önnur
keyrsluumhverfi eru nauðsynleg.

Til að forskoða vefinn og sjá breytingar jafnóðum:

```sh
zola serve
```

Opnaðu <http://127.0.0.1:1111>.

Til að yfirfara vefinn og byggja útgáfu til birtingar:

```sh
zola check --skip-external-links
zola build
```

Tilbúinn vefur verður í `public/` og er birtur beint þaðan. 
