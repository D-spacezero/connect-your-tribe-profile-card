> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Visite kaart met Node / API

## Inhoudsopgave

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
Tijdens dit project gaan we even terug in de tijd. We pakken ons aller eerste project erbij. Namelijk het maken van een persoonlijk visite kaart. Met html en css. 

Echter gaan we deze kwa functionaliteit in een nieuw jasje steken. Namelijk door de data die weergegeven word niet "hard" erin te coderen. Maar deze op te halen uit een database.

<img width="1680" alt="Screenshot 2023-04-05 at 08 52 02" src="https://user-images.githubusercontent.com/112856412/230005420-571ce4f6-53fa-483d-97b7-f1404ba645d0.png">

Link naar live server: https://real-tan-hatchling-tie.cyclic.app

## Kenmerken
Om dit project mogelijk te maken en de data op te halen haal ik binnnen de index.ejs met ESJ de data op. Dit ziet er zo uit:

```html:
<div style="background-color:white !important;">
      <img class="liquid" src="./media/liquid-gradient.jpg" alt="liquid">
      <h2 class="vertical-text">SWIPE >>>>>></h2>
      <!--- Haal de "name" en "surname" op uit de database --->
      <h1 class="name-box"><%= member.name %> <br> <%= member.surname %> </h1>
    </div>
  
    <div class="quality-box quality-box-transition">
      <div class="fade fade-trasistion">
        <h1 class="qualities">Qualities</h1>
        <ul class="list">
          <li>Creative</li>
          <li>Resolving</li>
          <li>Innovative</li>
          <li>Prepared</li>
        </ul>
      <h2 class="aboutme">About me</h2>
        <!--- Haal de "bio" op uit de database --->
        <p><%= member.bio.html %></p>
      </div>
    </div>
```



<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->

## Bronnen

Workshop van Justus

Oude visite kaartje: https://github.com/D-spacezero/your-tribe-css-basics

## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
