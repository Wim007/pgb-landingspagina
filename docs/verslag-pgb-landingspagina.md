# Verslag wijzigingen PGB-landingspagina (SamenOntzorgen)

**Datum:** 20 juli 2026
**Pagina:** pgb-landings-pagina.up.railway.app (bestand `public/gevonden.html`)
**Doelgroep:** budgethouder (PGB-houder, Wlz), die een bericht heeft gekregen dat er een passende zorgverlener is gevonden.

---

## 1. Wat is er gedaan (samengevat)

De landingspagina is in vier stappen aangepast en verbeterd:

1. **Budgetclaim verwijderd.** De belofte over "geen marge op het zorgtarief, zo blijft er meer van uw budget over" is weggehaald, omdat die niet meer richting budgethouders gecommuniceerd mag worden.
2. **Formulier uitgebreid.** Er is een verplicht veld "Uw zorgvraag" toegevoegd, zodat de budgethouder de zorgvraag zelf invult. De mailkoppeling is meegepast.
3. **Storytelling toegevoegd (545-strategie).** De bovenkant van de pagina volgt nu de volgorde: pijn erkennen, pijn voelbaar maken, paradijs schetsen, en pas daarna wie we zijn en hoe het werkt. Toon: Everyman (gelijkwaardig, nuchter, warm).
4. **Controles en vertrouwen benoemd.** Wij controleren de zorgverlener vooraf (diploma's, identiteitsbewijs, VOG, KvK, klachtencommissie en, waar van toepassing, BIG-register), en dat kan de budgethouder ook zelf inzien.
5. **De drie stappen herschreven** naar de echte volgorde: formulier invullen, wij onderhandelen de prijs, na akkoord rechtstreeks contact met de zorgverlener.
6. **Teksten positief gemaakt.** Overal alleen communiceren wat we wél doen, niet wat we niet doen.
7. **Bedrijfsgegevens toegevoegd** in de footer: KvK, vestigingsnummer, adres en e-mailadres.

Schrijfregels die zijn aangehouden: u-vorm, geen em-, en- of losse verbindingsstreepjes, alleen benoemen wat we wél doen, en de app heet "de app van SamenOntzorgen".

---

## 2. De teksten die nu op de pagina staan

### Kop (hero)
**Voor u als budgethouder**
**Er is een zorgverlener gevonden.**

> Een zorgverlener vinden die echt bij u past, is vaak een lange en onzekere zoektocht. Voor u kan die nu voorbij zijn: er is een zelfstandige zorgverlener die past bij uw zorgvraag. Laat hieronder uw gegevens en uw zorgvraag achter, dan gaan wij voor u aan de slag.

### Verhaalblok (boven het formulier)
**U hoeft er niet alleen voor te staan**

> De juiste zorg regelen betekent vaak: zoeken naar iemand die past, en ondertussen worstelen met de administratie, de regels en de vraag of iemand wel te vertrouwen is. Dat is veel, en vaak staat u er alleen voor.
>
> Zo hoeft het niet. Een betrouwbare zorgverlener die bij u past, duidelijke afspraken en rust in de papieren. Zodat er weer tijd en aandacht overblijft voor wat echt telt.
>
> SamenOntzorgen is een coöperatie van en voor zorgprofessionals. Elke zorgverlener controleren wij vooraf: diploma's, identiteitsbewijs, VOG, KvK-inschrijving, aansluiting bij een klachtencommissie en, waar van toepassing, het BIG-register. Deze gegevens kunt u ook zelf inzien.
>
> Wij helpen u bij de afspraken over het uurtarief, zodat het binnen uw pgb past. Het contract en de facturen zetten wij voor u klaar, en met de app van SamenOntzorgen beheert u alles overzichtelijk op één plek. U houdt zelf de regie.
>
> Lees meer over pgb op de website van SamenOntzorgen. (link naar https://www.samenontzorgen.nl/pgb)

### Formulier
**Laat uw gegevens achter**
Vul uw gegevens en uw zorgvraag in. Een telefoonnummer of een e-mailadres is genoeg om u te bereiken.

Velden:
- Uw naam (verplicht)
- Telefoonnummer
- E-mailadres
- Uw zorgvraag (verplicht, tekstvak; hint: "Vertel kort welke zorg u zoekt, voor wie, en hoeveel uur per week ongeveer.")
- Knop: Verstuur

### Stappen (onderaan)
**Wat u kunt verwachten**
**U beslist zelf, elke stap**

1. **U vult het formulier in** — Met uw gegevens en uw zorgvraag. Zo weten wij wie u bent en welke zorg u zoekt.
2. **Wij onderhandelen de prijs** — Wij bespreken het uurtarief met de zorgverlener, zodat het binnen uw pgb past. U hoort van ons wat het wordt.
3. **Na uw akkoord brengen wij u in contact** — Gaat u akkoord met de prijs? Dan brengen wij u en de zorgverlener bij elkaar. Daarna bespreekt en regelt u de zorg rechtstreeks met elkaar.

### Footer
> Een coöperatie van en voor zorgprofessionals. Open kaart, alles helder op een rij.
>
> Coöperatie SamenOntzorgen U.A. · KvK: 96745886 · Vestigingsnummer: 000062049658
> Hoofdvestiging: Wijnstraat 75, 3311 BT Dordrecht
> Vragen vooraf? Mail gerust. info@samenontzorgen.nl
>
> © 2026 Coöperatie SamenOntzorgen U.A. · samenontzorgen.nl · Minder zorgen, meer zorg

---

## 3. Techniek (formulier en mail)

- Het formulier stuurt de gegevens naar het e-mailadres info@samenontzorgen.nl.
- De zorgvraag is verplicht (naast de naam en een telefoonnummer of e-mailadres) en komt in een eigen blok in de mail te staan.

---

## 4. Skill voor toekomstige teksten

Er is een herbruikbare skill vastgelegd in het project (`.claude/skills/samenontzorgen-pgb-landingspagina/`), zodat de strategie voortaan automatisch wordt toegepast bij nieuwe teksten voor deze pagina. Die skill bevat:
- de 545-strategie (pijn, pijn voelbaar, paradijs, dan hoe),
- het Everyman-archetype en de merkstem,
- de empathiemap van de PGB-houder,
- de schrijfregels.

---

## 5. Aandachtspunten

- **"Uurtarief binnen uw pgb":** dit is een belofte richting budgethouders. Zorg dat die waargemaakt kan worden.
- **De 545-strategie** is ingevuld zoals besproken (pijn, pijn voelbaar, paradijs, dan hoe). Is er een uitgebreider intern document, dan kan de skill daarop worden bijgewerkt.
- **Bredere flow** (het bericht op het platform, het APM-portaal, afhandeling via de app) valt buiten deze landingspagina en zit hier bewust niet in.
