---
name: vacatures-checken
description: Gebruik als de gebruiker vraagt om vacatures te checken of te beoordelen, bijvoorbeeld 'check vacatures', 'welke vacatures passen bij mij' of 'zitten er goede vacatures in mijn mail'. Zoekt IT- en netwerkvacatures in Gmail en beoordeelt ze tegen het profiel van de gebruiker.
---

# Vacatures checken

Zoek in Gmail naar vacaturemails van de laatste 7 dagen, haal de IT- en netwerkvacatures eruit en beoordeel per vacature of die bij de gebruiker past.

## Bron

- Alleen Gmail: het gekoppelde Gmail-account, via de Gmail-connector.
- Staan de Gmail-tools niet aan in deze chat? Zeg dat in een zin en vraag de gebruiker Gmail aan te zetten via de + knop linksonder in de chat, dan Connectors.

## Alleen lezen

- Verander niets in de mailbox: niet op gelezen zetten, niet archiveren, geen labels, niet verwijderen, geen concepten of antwoorden.
- Solliciteer nergens en vul geen formulieren in.

## Stap 1: vacaturemails ophalen

- Kijk naar alle mails van de laatste 7 dagen, gelezen en ongelezen.
- Zoek bijvoorbeeld met: `newer_than:7d -in:sent (vacature OR vacatures OR job OR jobs OR sollicitatie OR recruiter OR from:ictergezocht.nl OR from:linkedin.com OR from:indeed.com OR from:nationalevacaturebank.nl)`
- Vacaturemails zijn job alerts, vacaturemailings en berichten van recruiters of werkgevers.
- Open elke vacaturemail volledig (platte tekst) en haal alle vacatures eruit, ook die onder kopjes als "gemist".

## Stap 2: selecteren

- Neem alleen IT- en netwerkfuncties op (bijv. netwerkbeheer, systeembeheer, servicedesk, helpdesk, IT-support, werkplekbeheer, cloud, security).
- Staat dezelfde vacature in meerdere mails? Toon hem maar een keer.

## Stap 3: details opzoeken

- Voor elke vacature die na een eerste beoordeling "Past goed" of "Past deels" scoort: open de vacaturepagina via de link in de mail (met WebFetch) en lees de eisen, taken, uren, contractvorm en standplaats.
- Volg een doorverwijzing naar een andere website als dat nodig is.
- Lukt het openen niet (bijv. inlog nodig of pagina niet bereikbaar)? Beoordeel dan op basis van de mail en zeg in de kolom Waarom dat de details ontbreken.
- Vat de pagina samen in eigen woorden. Kopieer geen lappen tekst.

## Stap 4: beoordelen

Beoordeel elke vacature tegen het profiel hieronder op niveau, reisafstand, salaris, eisen en type werk.

- **Past goed**: niveau, afstand en salaris passen, en de eisen zijn haalbaar.
- **Past deels**: een of twee punten passen niet of zijn onduidelijk.
- **Past niet**: duidelijk te ver, te senior of niet IT-gericht genoeg.

## Stap 5: uitvoer

Antwoord in het Nederlands. Toon een tabel, gesorteerd op beoordeling (Past goed, dan Past deels, dan Past niet). Binnen dezelfde beoordeling: de kortste reistijd eerst.

| Past? | Functie | Bedrijf | Plaats | Salaris | Waarom |
|---|---|---|---|---|---|

- Waarom: een of twee korte zinnen met de belangrijkste argumenten. Noem bij "Past goed" en "Past deels" de belangrijkste eisen van de vacaturepagina en of de gebruiker daaraan voldoet.
- Zet de link naar de vacature bij de functienaam als je die hebt.
- Reistijden en bruto-netto-omrekeningen zijn schattingen. Zeg dat erbij.
- Mist er informatie om een vacature goed te beoordelen? Stel onder de tabel korte, genummerde vragen. Stel geen vragen die het profiel al beantwoordt.
- Geen IT-vacatures gevonden? Geef alleen een korte melding, bijvoorbeeld: "Geen IT-vacatures gevonden in de laatste 7 dagen."
- Geen em dash gebruiken.

## Profiel van de gebruiker

Het persoonlijke profiel staat niet in deze openbare versie. Vul hier zelf in:

- **Woonplaats:**
- **Reisafstand:** (bijv. maximaal 45 minuten met de auto, leaseauto een plus)
- **Opleiding:**
- **Certificaten en cursussen:**
- **Ervaring:**
- **Gewenst niveau:**
- **Contract en uren:**
- **Salaris:** (minimum, netto of bruto)

Ontbreekt het profiel? Vraag de gebruiker eerst om deze gegevens voordat je vacatures beoordeelt.
