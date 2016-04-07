---
title: "Låsing av periode"
layout: "docs"
section: "Avtaler"
permission: "Konfigurasjon"
menu: "Ordrer - Opprett ordrer"
---

Etter endt periode(måned)og evt. ordrebehandling bør perioden låses.
Når en periode er låst vil avtaler før denne datoen ikke hentes og oppdateres lenger. 

Denne innstillingen overstyrer [Antall dager](hentavtaler) og jobber sammen med den innstillingen slik at man f.eks henter siste 32 dager for å hente hele måneden,
men setter perioden låst frem til den 1. i inneværende måned.

Mertid vil da gjennom hele måneden kun hente fra låsingsdato (1. i måneden) og frem til dagens dato.


Dersom du har behov for å hente avtaler bak låsingperiode f.eks for å hente inn oppdarte avtaler etter fakturering fordi en konsulent hadde glemt en timeføring e.l. så kan du 
justere låsingsperioden lenger tilobake for å plukke opp endringen. Hente avtalene også sette låsingsperioden tilbake igjen.

Gå til:

| Menyvalg      | Rettighet           |
|---------------|---------------------|
| {{page.menu}} | {{page.permission}} |

*Dersom du har rettigheter til det.*

Velg dato og trykk Lås periode
