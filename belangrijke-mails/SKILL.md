---
name: belangrijke-mails
description: Gebruik als de gebruiker vraagt om een overzicht van belangrijke, relevante of ongelezen e-mails, bijvoorbeeld 'welke mails zijn belangrijk' of 'wat moet ik lezen in mijn mail'. Niet voor het beoordelen van vacatures: daarvoor is de skill vacatures-checken.
---

# Belangrijke mails

Geef een overzicht van de ongelezen mails van de laatste 24 uur die er voor de gebruiker toe doen.

## Bron

- Alleen Gmail: het gekoppelde Gmail-account, via de Gmail-connector.
- Staan de Gmail-tools niet aan in deze chat? Zeg dat in een zin en vraag de gebruiker Gmail aan te zetten via de + knop linksonder in de chat, dan Connectors. Ga niet zoeken via een browser.

## Alleen lezen

- Verander niets in de mailbox: niet op gelezen zetten, niet archiveren, geen labels, niet verwijderen, geen concepten of antwoorden.

## Stap 1: ophalen

- Zoek met: `is:unread newer_than:1d -in:sent`
- Haal per mail afzender, onderwerp, ontvangsttijd en snippet op.
- Is de snippet te kort om de mail goed samen te vatten of de prio te bepalen? Open dan de volledige mail (platte tekst).

## Stap 2: filteren

Laat deze mails weg:
- Nieuwsbrieven (ook als de afzender bekend is)
- Reclame en aanbiedingen
- Social media-meldingen (LinkedIn, Facebook, Instagram, X en dergelijke)
- Bestelbevestigingen
- Bezorging van post en pakketten (track & trace, PostNL, DHL en dergelijke)
- Verificatiecodes en 2FA-codes die al verlopen zijn (vergelijk de geldigheidsduur in de mail met de huidige tijd)
- Vacaturemails: job alerts en vacaturemailings (LinkedIn, ICTerGezocht, Indeed, Nationale Vacaturebank en dergelijke). Tel ze wel (zie Stap 4).

Laat deze twijfelgevallen WEL zien:
- Beveiligingsmeldingen (inlogpogingen, nog geldige codes, wachtwoordwijzigingen)
- Rekeningen en facturen
- Berichten van bank of cursusplatform
- Persoonlijke berichten van recruiters of werkgevers (altijd prio Hoog)

## Stap 3: prio bepalen

- **Hoog**: er wordt een actie of antwoord gevraagd, of er staat een deadline in.
- **Middel**: persoonlijk of relevant, maar zonder directe actie.
- **Laag**: informatief, kan wachten. Een beveiligingsmelding over iets wat de gebruiker zelf net heeft gedaan, is Laag.

## Stap 4: uitvoer

Antwoord in het Nederlands. Toon een tabel, gesorteerd op prio (Hoog, dan Middel, dan Laag). Binnen dezelfde prio: nieuwste eerst.

| Prio | Afzender | Onderwerp | Samenvatting |
|---|---|---|---|

- Samenvatting: maximaal 1 a 2 korte zinnen. Noem een deadline of gevraagde actie expliciet.
- Rekeningen en facturen: open altijd de volledige mail en noem het bedrag en de uiterste betaaldatum. Staat er alleen een termijn (bijv. 30 dagen), reken dan de datum uit vanaf de rekeningdatum.
- Herhaal nooit verificatiecodes of wachtwoorden in de uitvoer.
- Noem onder de tabel in een regel welke mails zijn weggefilterd.
- Zijn er vacaturemails weggefilterd? Voeg dan een regel toe, bijvoorbeeld: "3 vacaturemails gevonden. Vraag 'check vacatures' voor het overzicht."
- Geen relevante mails? Geef alleen een korte melding, bijvoorbeeld: "Geen belangrijke ongelezen mails in de laatste 24 uur." Noem eventuele vacaturemails dan nog wel.
- Geen em dash gebruiken.
