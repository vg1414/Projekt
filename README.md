# Projekt

En personlig startsida som samlar länkar till alla mina publicerade webbprojekt, i rymdtema.

**Live:** https://vg1414.github.io/Projekt/

## Funktioner

- 3D-stjärnfält som flyger mot dig, nebulosor, stjärnfall och lätt parallax när musen rör sig
- Namnet i vitt som tonar in bokstav för bokstav, med ett diskret silverskimmer, plus en skrivmaskinsrad
- Alla appar som glaskapslar (logga, namn, tagg, pil) i en lista, i ordning efter hur stora projekten är:
  Reduceraren, Krokens Copa, Bokis, ABC & 123, Black Book, WSOP Fantasy, Badläget, Träningslogg
- Hovra en kapsel: den lyfter, lyser i appens färg, loggan vrider sig och pilen fylls; beskrivningen visas som tooltip
- Klick → hyperspace-hopp (stjärnorna blir streck, blixt i appens färg) och sedan öppnas appen
- Ctrl/Cmd-klick öppnar i ny flik som vanligt
- Respekterar "minska rörelse" i enhetens inställningar
- Egen ikon och webbmanifest: kan läggas på hemskärmen och öppnas som en app i helskärm
- Dold för sökmotorer (`noindex`), sidan är för eget bruk

## Lägga till ett projekt

1. Lägg appens logga (helst 192×192 px) i `logos/`.
2. Lägg till en rad i listan `APPS` i `index.html`: namn, tagg, logga, glow-färg, beskrivning och adress. Ordningen i listan är ordningen på sidan.
