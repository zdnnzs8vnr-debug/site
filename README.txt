MEATBAG.BEST — struttura repo
=============================

index.html    sito completo (10 lingue, countdown, campo CA vuoto)
404.html      pagina errore brandizzata
favicon.svg   icona tab
robots.txt    regole crawler + sitemap
sitemap.xml   sitemap
CNAME         dominio custom: meatbag.best
.nojekyll     disattiva Jekyll

AGGIORNARE IL CONTRACT ADDRESS AL LANCIO
----------------------------------------
1. apri index.html
2. cerca:  var CA="";
3. incolla il mint dentro le virgolette:  var CA="ABC...xyz";
4. commit + push
5. GitHub Pages ripubblica in ~40 secondi
6. ricarica con Cmd+Shift+R

Il CA si propaga da solo su: campo in home, barra mobile,
tutti i bottoni BUY e il grafico DexScreener.

DNS (Porkbun)
-------------
A     @    185.199.108.153
A     @    185.199.109.153
A     @    185.199.110.153
A     @    185.199.111.153
CNAME www  zdnnzs8vnr-debug.github.io

Poi: GitHub > Settings > Pages > Enforce HTTPS (ON)
