# Pagina's in Systeme.io: /start, /bedankt en /cursus

Eén trechter met drie stappen (het gratis plan staat 1 trechter met maximaal 10 stappen toe). Domein: **www.beleggenbeginthier.nl**. Links vanaf YouTube krijgen `?bron=yt-<naam>`; de pagina's moeten met en zonder die parameter werken.

Opmaak volgens het goedgekeurde ontwerp: achtergrond #F3F7F4, tekst #0F2A1F, koppen en kopbalk #1F6B4A, knoppen goud #F2C14E met donkere tekst #0F2A1F, vlakken #CFE9DC. Mascotte (`assets/mascotte.png`) op /start en /cursus.

## Stap 1: /start (opt-in)

**Kop:** Beleggen begint hier. Gratis.

**Subkop:** Download de Startchecklist en volg module 1 gratis. Zo weet je in een uur of beleggen iets voor jou is.

**Drie punten:**
- Wat beleggen is, in gewone taal
- Waarom vroeg beginnen zoveel scheelt
- Een checklist voor je eerste stap

**Formulier:** voornaam, e-mailadres, en een verplicht vinkje: "Ik wil de Startchecklist en mails van Beleggen Begint Hier ontvangen. Afmelden kan altijd."

**Knop:** Stuur mij de checklist

**Klein onderaan:** Beleggen Begint Hier geeft algemene uitleg en geen persoonlijk financieel advies. Beleggen brengt risico's met zich mee: je kunt (een deel van) je inleg verliezen.

**Automatisering (Automation rules op deze stap):** trigger "Funnel step form subscribed" →
1. Enroll in course: Beleggen Begint Hier, **Partial access**, alleen module 1.
2. Add tag: `gratis-module-1`.
3. Send email (zie hieronder).

## Stap 2: /bedankt

**Kop:** Gelukt! Je checklist staat klaar.

**Tekst:** Je krijgt ook een mail met je inloggegevens voor module 1. Kijk even in je spam als hij er over een paar minuten niet is.

**Knoppen:**
- Download de Startchecklist (PDF)
- Start met module 1 (link naar de inlogpagina van de cursus)

**Onder de knoppen:** Smaakt het naar meer? Bekijk wat je in de volledige cursus leert → link naar /cursus.

## Welkomstmail

**Onderwerp:** Je Startchecklist en module 1

Hoi {voornaam},

Fijn dat je erbij bent! Hier is je Startchecklist: [link naar de PDF].

Module 1 staat voor je klaar. In drie korte lessen leer je waarom beleggen slim is, wat inflatie met je spaargeld doet en hoe rente-op-rente werkt. Je inloggegevens krijg je in een aparte mail.

Veel plezier,
Beleggen Begint Hier

*Algemene uitleg, geen persoonlijk financieel advies.*

## Stap 3: /cursus (verkooppagina)

**Kopbalk:** logo Beleggen Begint Hier · Wat je leert · Prijs · Vragen · Inloggen

**Label:** Voor twintigers met een eerste baan

**Kop:** Van spaarrekening naar je eerste belegging. Stap voor stap.

**Tekst:** In 6 modules leer je waarom beleggen slim is, hoeveel jij kunt missen, welke broker bij je past en hoe je je eerste aankoop doet. Zonder jargon, met een plan dat je volhoudt.

**Knoppen:** Start de cursus · Probeer module 1 gratis (→ /start)

**Kleine regel:** 21 lessen · elke les een korte meerkeuzetest · invulbare werkbladen · 14 dagen geld terug

**Kaart rente-op-rente:** Lisa legde € 12.000 in, Tom € 36.000. Toch heeft Lisa op haar 65e meer. *Uit les 1.3 · gemiddeld 7% per jaar, geen garantie.*

**Drie blokken:**
- **€ 0** · Geen voorkennis nodig. We beginnen bij de vraag: waarom zou je überhaupt beleggen?
- **€ 25** · Per maand is genoeg. Je leert beleggen met kleine bedragen, zonder dat kosten alles opeten.
- **1 plan** · Dat je echt volhoudt. Met regels voor als de beurs daalt, zodat je niet in paniek verkoopt.

**Wat je leert: zes modules, van waarom naar je eerste aankoop**

| Module | Inhoud | |
| --- | --- | --- |
| 1 Waarom beleggen? | Sparen versus beleggen, inflatie en rente-op-rente | 3 lessen · gratis |
| 2 Is beleggen iets voor jou? | Buffer, maandbedrag, doelen en je risicoprofiel | 4 lessen · invulbaar werkblad |
| 3 De basis van beleggen | Aandelen, obligaties, ETF's, spreiding en kosten | 5 lessen |
| 4 Aan de slag | Broker kiezen, rekening openen en je eerste aankoop | 4 lessen · brokervergelijking |
| 5 Een plan maken en volhouden | Je beleggingsplan, emoties en herbalanceren | 3 lessen · invulbaar plan |
| 6 Belasting en regels | Box 3 en hoe je als belegger beschermd bent | 2 lessen |

**Je leert samen met Sam:** Sam is 23, heeft net een eerste baan en houdt € 300 per maand over. In elke les zie je hoe Sam het aanpakt: buffer, maandbedrag, broker, eerste aankoop. Zo zie je niet alleen de theorie, maar ook hoe het er in het echt uitziet.

**Prijs: minder dan een avondje uit**
- **Module 1 · Gratis.** 3 lessen over waarom beleggen slim is, plus de Startchecklist. Knop: Probeer gratis (→ /start)
- **Volledige cursus · Lanceringsprijs € 39** (doorgestreept € 69). Alle 6 modules, werkbladen, brokervergelijking en levenslang updates. Betalen met iDEAL. Knop: Start de cursus. 14 dagen geld-terug-garantie.

**Veelgestelde vragen**
- *Moet ik al iets van beleggen weten?* Nee. De cursus begint bij nul en legt elk begrip uit.
- *Krijg ik advies over wat ik moet kopen?* Nee. Je leert hoe je zelf kiest, met checklists en voorbeelden. Zo maak je je eigen keuze.
- *Hoeveel geld heb ik nodig?* Je kunt beginnen met een paar tientjes per maand. In module 2 reken je uit wat bij jou past.

**Voettekst:** Beleggen Begint Hier geeft algemene uitleg en geen persoonlijk financieel advies. Beleggen brengt risico's met zich mee: je kunt (een deel van) je inleg verliezen. Rendementen uit het verleden bieden geen garantie voor de toekomst.

**Zolang betalen nog niet is gekoppeld:** de knoppen "Start de cursus" wijzen naar /start, met onder de prijs de regel "De cursus is binnenkort te koop. Begin alvast gratis met module 1." Zodra Stripe (iDEAL) is gekoppeld, komt er een bestelformulier als extra stap en wijzen die knoppen daarnaar.
