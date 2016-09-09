---
title: "Grenseverdier for arbeidsdager"
layout: "docs"
section: "Innstillinger"
permission: "Konfigurasjon"
menu: "Innstillinger - Konfigurasjon"
---

Grenseverdiene for en arbeidsdag vil endre kriteriene til fargeindikatorene.

Fargeindikatorene brukes i [kalenderen](../../introduksjon/dashboard) til konsulenter og i oversikten, [HeatMap]().

Du setter disse grenseverdiene ved å sette verdien Hours_Limits:

| Menyvalg      | Rettighet           |
|---------------|---------------------|
| {{page.menu}} | {{page.permission}} |

*Dersom du har rettigheter til det.*

Betydning:

| Navn          | Forklaring                                |
|---------------|-------------------------------------------|
| WorkDayLimits | Grenseverdi for en arbeidsdag             |
| HolyDayLimits | Grenseverdi for en helligdag              |
| WeekendLimits | Grenseverdi for en helg                   |
| PeriodLimits  | Grenseverdi i gjennomsnitt for en periode |

Verdienes mening (heltall):

| Navn    | Forklaring                    |
|---------|-------------------------------|
| LL      | Rød indikator (lavest)        |
| L       | Orasje indikator (lav)        |
| H       | Lys lilla indikator (høy)     |
| HH      | Mørk lilla indikator (høyest) |

Relaterte instillinger:

-	[Sett antall timer for en normal arbeidsdag]()
-	[Sett oppdeling av arbeidstime]()
