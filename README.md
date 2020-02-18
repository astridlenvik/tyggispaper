# Påvirker tyggis konsentrasjonen?
Dette er et fiktivt forskningsprosjekt hvis eneste hensikt er å teste ut samarbeid i artikkelskriving med papaja. Dette gjennomføres som del av en workshop på HVL Kronstad 27.2.2020.

## Forskningsprosjektet
Til workshopen har vi fått bruke forskningsspørsmål og innsamlet data fra et forskningsprosjekt gjennomført av elever i syvendeklasse på en barneskole i Oslo. Disse elevene ønsket å undersøke hvorvidt tygging av tyggis påvirket konsentrasjon og arbeidsro i skoletimer.

Til å undersøke dette satte de sammen [dette spørreskjemaet](spørreskjema.pdf), hvor item 1-3 er ment å måle konsentrasjon og item 4-6 er ment å måle arbeidsro. Items 2 og 5 er reversert.

Med dette skjemaet samlet de data i to skoleklasser på femtetrinn ved skolen sin. De to skoleklassene gjennomførte den samme mattetimen med den samme læreren. En god del av timen ble brukt til å jobbe selvstendig med oppgaver. I én av klassene fikk elevene tygge tyggis mens de jobbet. Dette ble av læreren presentert som en belønning for at de hadde vært flinke i en tidligere time, og det ble ikke nevnt noe om forskningsprosjektet. I slutten av timen i begge klassene ble elevene presentert for spørreskjemaet, av elevene som gjennomførte forskningsprosjektet. De ble fortalt at det var en undersøkelse som handlet om konsentrasjon og arbeidsmiljø på skolen. Det ble ikke nevnt for noen av klassene at dette hadde noe med tyggis å gjøre. I [datasettet](data/tyggisdata.csv) har klasse "1" fått tyggis. Klasse "2" har ikke fått tyggis.

## Gjennomføring
Vi deler i grupper. Hver gruppe jobber med hver sin del av artikkelen.

### Gruppe 1: Innledning
- Finner relevant litteratur, og legger det til i Zotero-biblioteket "tyggispaper"
- Skriver innledning og teoretisk bakgrunn, inkl. hypoteser

### Gruppe 2: Metode
- Skriver Method-delen. Beskriver utvalget, datainnsamling og måleverktøyene som er brukt.
- Bruk fortrinnsvis inline-kode og funksjoner som `r printnum()` til å beskrive utvalget i teksten.
- Korrelasjonsmatrise?

### Gruppe 3: Analyser og resultat
- Skriver Results-delen.
- Bruk kodechunks innledningsvis under overskriften Results til å gjennomføre analysene.

## Noen kjøreregler
- Hver gruppe lager sin egen branch, og committer til denne.
- I RMarkdown-dokumentet er det angitt med kommentarer hvilket område gruppene skal holde seg innenfor. Hensikten med dette er å forebygge merge-konflikter.
- Når dere anser dere som ferdige åpner dere en pull request.
- Kun "ansvarlig førsteforfatter" merger pull requests. Ikke gjør dette selv.
