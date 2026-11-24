# Codebuch: Anne Will Netzwerk (Folgen 500–503, Ukraine 2022)

## Projektbeschreibung
Gerichtetes Two-Mode-Netzwerk der Gästelisten der ARD-Talkshow "Anne Will" zum Thema Ukraine-Krieg (Folgen 500 bis 503, Feb./März 2022) inklusive Parteizugehörigkeit.

## Edgelist (`annewill_edgelist.csv`)
- **from**: ID des Ausgangsknotens (Person als Initialen, z. B. `lk` für Lars Klingbeil).
- **to**: ID des Zielknotens (Sendungsnummer `500`–`503` oder Parteikürzel wie `SPD`, `CDU`).
- **relationship**: `1` = Gastauftritt in der Sendung, `2` = Parteimitgliedschaft.

## Nodelist (`annewill_nodelist.csv`)
- **id**: Eindeutige ID ohne Sonderzeichen/Leerzeichen (Initialen, Sendungsnummern, Parteikürzel).
- **name**: Vollständiger Name, Sendungstitel oder Parteiname.
- **type**: `1` = Person, `2` = Organisation/Event (Sendung oder Partei).
- **party**: Parteizugehörigkeit (`SPD`, `CDU`, `FDP`, `Gruene`, `Linke`; leer bei Parteilosen/Institutionen).
- **sector**: Gesellschaftlicher Bereich (`Politik`, `Wissenschaft`, `Journalismus`, `Medien`, `Partei`).
- **country**: Herkunfts- bzw. Wirkungsland (`Deutschland`, `EU`, `Lettland`, `Ukraine`).
