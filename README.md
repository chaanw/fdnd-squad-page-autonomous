> Fork deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Vaporwave Squad Page

## Description

<!-- Voeg een link toe naar Github Pages 🌐-->

https://vaporwave.student.fdnd.nl/

<!-- Voeg een mooie poster visual toe 📸 -->

![team-vaporwave](https://media.discordapp.net/attachments/437951219705577472/890164713768517632/MicrosoftTeams-image.png)

The Vaporwave website is made with HTML, CSS & JS (also in JSON).
In this website we will show all the students in Front-end Development & Design.

The team consists of 5 developers/designers:

- Chaan Soekana
- Shauri Maigua
- Abdurabi Abukar
- Nandita Badeloe
- Justin Lung

## Table of contents

- [Description](#description)
- [Analyse](#analyse)
- [Design](#design)
- [Build](#build)
- [Integrate](#integrate)
- [Test](#test)
- [Liscence](#liscence)

## Analyse

As a team, we discussed which theme we should choose for our project.
In this process we decided to go with the Vaporwave theme.

For our first sprint, we had 2 weeks to integrate the developer life cycle.
This life cycle consists of:

- Analyse
- Design
- Build
- Integrate
- Test

## Design

As a team we made a few desgins. Each team member made a sketch of the website.

This sketch was made by Justin. This was a design for the smaller screens like mobile, tablet or laptop.
![vaporwave-sketch-justin](https://media.discordapp.net/attachments/437951219705577472/890170354004295690/Screenshot_2021-09-22_at_11.39.06.png)

This sketch was made by Abdurabi. This was one of the first sketches to showcase our project, but this was a part of the development life cycle.

![vaporwave-sketch-abdurabi](https://media.discordapp.net/attachments/437951219705577472/890170750856757328/Screenshot_2021-09-22_at_11.40.20.png)

This sketch was made by Shauri. This was one of the first sketches to showcase our project, but this was a part of the development life cycle.

![vaporwave-sketch-shauri](https://media.discordapp.net/attachments/871761581590052925/890171458989477918/Screenshot_2021-09-22_at_11.43.25.png)

This sketch was made by Chaan. This sketch was made of the content of the website.

![vaporwave-sketch-chaan](https://media.discordapp.net/attachments/871761581590052925/890171925295398932/Screenshot_2021-09-22_at_11.45.20.png?width=790&height=1138)

We came to a conclusion, to make a vaporwave themed website where we present our website. We will make this in HTML, CSS & JS

![vaporwave-final-sketch](https://media.discordapp.net/attachments/437951219705577472/890169012892344340/Screenshot_2021-09-22_at_11.33.45.png?width=784&height=1139)

## Build

First we made our HTML file. This file contains our sections for our website.

```
   <main>
        <section id="home">
            <div class="overlay"></div>
            <div class="stars"></div>
            <div class="background-80s animated-clouds stars" style="--background-height:100vh"></div>
            <img src="assets/fdnd-vaporwave-logo.svg" alt="logo" class="logo" />
            <h1>【 w e l c o m e &nbsp; t o &nbsp; o u r &nbsp; s q u a d p a g e 】</h1>
            <div class="grid-container">
                <div class="grid" style="--grid-color:rgba(255, 255, 255, 0.5);--grid-size:30px;--grid-blur:1px;"></div>
            </div>
            <button class="navBtn"><a href="#about">Scroll Down</a></button>
        </section>

        <section id="about">
            <h2>[ a b o u t &nbsp; u s ]</h2>
            <p>
                Bij de Ad Frontend Design & Development doe je alles met code: met
                code los je een parkeerprobleem op voor de Gemeente Amsterdam, ontwerp
                je voor het systeem van de Openbare Bibliotheek een betere
                zoekfunctie, en help je samen met de verpleegkundigen van het
                Amsterdam UMC de zorg te verbeteren. Je richt je tijdens deze
                tweejarige studie op webdesign, visual interface design en frontend
                development. Vanaf het begin van de opleiding werk je aan actuele
                opdrachten van échte opdrachtgevers, en leer je samenwerken in
                multidisciplinaire teams.
            </p>

            <div class="windows-logo-container">
                <img src="assets/windows95-vaporwave-icoon.svg" alt="windows-logo" class="windows-logo-left">
                <img src="assets/windows95-vaporwave-icoon-mirrored.svg" alt="windows-logo-mirrored"
                    class="windows-logo-right">
            </div>
        </section>

        <section id="squad">
            <h2>[ m e e t &nbsp; t h e &nbsp; s q u a d ]</h2>
            <div class="squad-container"></div>
        </section>
    </main>
```

## Integrate

## Test

## Liscence

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).
