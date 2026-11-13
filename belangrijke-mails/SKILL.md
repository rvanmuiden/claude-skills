---
name: belangrijke-mails
description: Gebruik als de gebruiker vraagt om een overzicht van belangrijke, relevante of ongelezen e-mails, bijvoorbeeld 'welke mails zijn belangrijk' of 'wat moet ik lezen in mijn mail'.
---

# Belangrijke mails

Geef een overzicht van de ongelezen mails van de laatste 24 uur die er voor de gebruiker toe doen, plus een apart overzicht van IT- en netwerkvacatures met een beoordeling of ze bij de gebruiker passen.

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

Zet vacaturemails eerst apart (zie Stap 5). Laat daarna deze mails weg:
- Nieuwsbrieven (ook als de afzender bekend is)
- Reclame en aanbiedingen
- Social media-meldingen (LinkedIn, Facebook, Instagram, X en dergelijke), behalve vacaturemeldingen
- Bestelbevestigingen
- Bezorging van post en pakketten (track & trace, PostNL, DHL en dergelijke)
- Verificatiecodes en 2FA-codes die al verlopen zijn (vergelijk de geldigheidsduur in de mail met de huidige tijd)

Laat deze twijfelgevallen WEL zien:
- Beveiligingsmeldingen (inlogpogingen, nog geldige codes, wachtwoordwijzigingen)
- Rekeningen en facturen
- Berichten van bank of cursusplatform

## Stap 3: prio bepalen

- **Hoog**: er wordt een actie of antwoord gevraagd, of er staat een deadline in.
- **Middel**: persoonlijk of relevant, maar zonder directe actie.
- **Laag**: informatief, kan wachten. Een beveiligingsmelding over iets wat de gebruiker zelf net heeft gedaan, is Laag.

## Stap 4: uitvoer belangrijke mails

Antwoord in het Nederlands. Toon een tabel, gesorteerd op prio (Hoog, dan Middel, dan Laag). Binnen dezelfde prio: nieuwste eerst.

| Prio | Afzender | Onderwerp | Samenvatting |
|---|---|---|---|

- Samenvatting: maximaal 1 a 2 korte zinnen. Noem een deadline of gevraagde actie expliciet.
- Rekeningen en facturen: open altijd de volledige mail en noem het bedrag en de uiterste betaaldatum. Staat er alleen een termijn (bijv. 30 dagen), reken dan de datum uit vanaf de rekeningdatum.
- Herhaal nooit verificatiecodes of wachtwoorden in de uitvoer.
- Noem onder de tabel in een regel welke mails zijn weggefilterd.
- Geen relevante mails? Geef alleen een korte melding, bijvoorbeeld: "Geen belangrijke ongelezen mails in de laatste 24 uur."
- Geen em dash gebruiken.

## Stap 5: vacatures

Vacaturemails zijn job alerts en vacaturemailings (LinkedIn, ICTerGezocht, Indeed, Nationale Vacaturebank en dergelijke) en berichten van recruiters.

- Open elke vacaturemail volledig en haal alle vacatures eruit, ook die onder kopjes als "gemist".
- Neem alleen IT- en netwerkfuncties op (bijv. netwerkbeheer, systeembeheer, servicedesk, helpdesk, IT-support, werkplekbeheer, cloud, security). Andere functies laat je weg.
- Een persoonlijk bericht van een recruiter komt ook in de tabel belangrijke mails, met prio Hoog.
- Beoordeel elke vacature tegen het profiel hieronder op: niveau, reisafstand, salaris en type werk.

Toon onder de tabel belangrijke mails een aparte tabel, gesorteerd op beoordeling (Past goed, dan Past deels, dan Past niet):

| Past? | Functie | Bedrijf | Plaats | Salaris | Waarom |
|---|---|---|---|---|---|

- **Past goed**: niveau, afstand en salaris passen.
- **Past deels**: een of twee punten passen niet of zijn onduidelijk.
- **Past niet**: duidelijk te ver, te senior of niet IT-gericht genoeg.
- Waarom: een korte zin met het belangrijkste argument.
- Reistijden en bruto-netto-omrekeningen zijn schattingen. Zeg dat erbij.
- Mist er informatie om een vacature goed te beoordelen? Stel onder de tabel korte, genummerde vragen. Stel geen vragen die het profiel al beantwoordt.
- Geen vacatures? Laat deze tabel weg.

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
