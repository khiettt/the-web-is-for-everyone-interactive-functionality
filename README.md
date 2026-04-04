# Interactive Functionality

Milledoni helpt je in je zoektocht naar het perfecte cadeau. 



## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Gebruik](#gebruik)
  * [Kenmerken](#kenmerken)
  * [Installatie](#installatie)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
Als je opzoek bent naar een cadeau voor iemand, is milledoni de website voor je zoektocht. Ze hebben cadeautjes voor alle leeftijden en gelegenheden en je kan samen met de chatbox de juiste cadeau vinden. Voor deze sprint heb ik een lijst pagina gemaakt en kan je alle producten die je leuk vindt opslaan in je lijstje. Dit heb ik kunnen doen met de POST method. Ook heb ik mijn design veranderd en ervoor gezorgt dat mijn website responsive is. 

Bezoek [Milledoni.com](https://milledoni.com/gb/en) voor leuke cadeau ideeën.

## Gebruik
Als gebruiker wil je cadeaus kunnen opslaan en verwijderen uit een lijst

<img width="754" height="783" alt="Scherm­afbeelding 2026-04-03 om 12 17 28" src="https://github.com/user-attachments/assets/830cb979-2d24-43f9-a0ec-5e1387db8495" />

<!-- Bij Gebruik staat de user story, hoe het werkt en wat je er mee kan. -->

## Kenmerken
Om mijn ontwerpt tot leven te brengen heb ik gebruik gemaakt van HTML, CSS, JS, NodeJS, Express, JSON en Liquid.

**POST**

Voor het opslaan van cadeautjes heb ik eerst een [formulier](https://github.com/khiettt/the-web-is-for-everyone-interactive-functionality/blob/b2ce5abd0181eea005fd3f242c460e70d1478a16/views/index.liquid#L35-L39) gemaakt met de data van de prodcuten erin en een POST methode gebruikt. Het gebruiken van `<form>` is het meest betrouwbare element, omdat dit werkt in elke browser, op elk apparaat, overal, voor iedereen. Wanneer er op de knop klikt, wordt er een POST-verzoek gestuurd naar [server.js](https://github.com/khiettt/the-web-is-for-everyone-interactive-functionality/blob/b2ce5abd0181eea005fd3f242c460e70d1478a16/server.js#L70-L88) met het product-ID. De server ontvangt dit ID en stuurt het door naar een API om het product op te slaan in de lijst van de gebruiker. Daarna wordt de gebruiker teruggestuurd naar de homepage.

**POST=DELETE**

Na dat de data is opgeslagen 
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met JS gedaan en hoe? Misschien heb je iets met NodeJS gedaan, of heb je een framework of library gebruikt? -->

## Installatie
volg de volgende stappen m aan deze repository te werken:

Stap 1: instaleer de [NodeJS ontwikkelomgeving](https://nodejs.org/) en kies voor NodeJS 24.13.0 (LTS, long-term support), download het installatiebestand en doorloop het installatieproces.

Stap 2: fork deze repository en clone deze naar een code editor. 

Stap 3: Open de _Terminal_ in VSCodium door de toetscombinatie `` ^` `` (control + `) te gebruiken. Er opent een terminalscherm in de hoofdmap van jouw project. Voer in de terminal het commando npm install uit, door het in te typen en op enter te drukken. 

Stap 4: Na de installatie is de map `node_modules` aangemaakt, en gevuld met allerlei _packages_. Start de website door in de terminal het comando `npm start` uit te voeren. Als het goed is, komt hier een melding te staan over het opstarten van de server: Application started on http://localhost:8000 — Open deze URL in je browser
<!-- Bij Instalatie staat hoe een andere developer aan jouw repo kan werken -->


## Bronnen

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).

De instructie vind je in: [INSTRUCTIONS.md](https://github.com/fdnd-task/the-web-is-for-everyone-interactive-functionality/blob/main/docs/INSTRUCTIONS.md)
