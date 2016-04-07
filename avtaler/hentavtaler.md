---
title: "Konfigurasjon: Hent avtaler for X antall dager"
layout: "docs"
section: "Avtaler"
permission: "Konfigurasjon"
menu: "Innstillinger - Konfigurasjon"
---

Når du henter avtaler fra konsulentenes kalender kan du sette hvor mange dager bakover i tid Mertid skal hente avtaler for.
Bare avtaler som er lagt til eller endret senere enn dagens dato - antall dager vil hentes inn.

Du setter disse dagene ved å sette verdien Avtaler_HentAntallDager:

| Menyvalg      | Rettighet           |
|---------------|---------------------|
| {{page.menu}} | {{page.permission}} |

*Dersom du har rettigheter til det.*

Vi anbefaler å sette den til 32.
Da får du alltid siste måneds avtaler oppdatert.

Benytt den i kombinasjon med [låsing av Periode](periode) så vil du kun hente avtaler for inneværende måned.
