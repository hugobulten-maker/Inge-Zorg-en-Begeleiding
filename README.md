# Inge Zorg en Begeleiding — statische website

Deze repository bevat een eenvoudige, toegankelijke statische website voor ingezorgenbegeleiding.nl.

Wat ik heb toegevoegd:
- index.html, about.html, diensten.html, contact.html
- styles.css
- CNAME -> ingezorgenbegeleiding.nl (voor GitHub Pages)

Publicatie (GitHub Pages):
- De site staat in de root van de `main` branch. Je kunt GitHub Pages inschakelen via Settings → Pages en de "source" op `main` branch (root) zetten.
- DNS: maak een A-record naar GitHub Pages IPs en (optioneel) een CNAME naar `ingezorgenbegeleiding.nl`. Raadpleeg de GitHub Pages docs voor exacte records.

Contactformulier:
- Het contactformulier in `contact.html` is een eenvoudige client-side implementatie die geen werkend endpoint bevat.
- Aanbevolen: maak een gratis Formspree-formulier (https://formspree.io) of gebruik Netlify Forms of een andere provider. Vul dan de `formAction` variabele in `contact.html` met je endpoint.

Assets en content:
- De site bevat nu voorbeeldtekst en een eenvoudig design. Vervang teksten, telefoonnummers en voeg logo/afbeeldingen toe in de `assets/` map.

Claude-artifact:
- Je had een Claude-artifact genoemd. Als je wilt, voeg ik teksten en afbeeldingen uit dat artifact toe: stuur de inhoud (tekstbestanden of afbeeldingen) of geef toestemming dat ik de URL download en verwerk.

Volgende stappen die ik kan uitvoeren (kies of geef opdracht):
- Vervangen van voorbeeldteksten met de teksten uit het Claude-artifact.
- Logo en afbeeldingen toevoegen in `assets/` (upload of geef URL's).
- Formular integratie met Formspree (ik voeg het endpoint toe als je je Formspree-id geeft).
- Een eenvoudige GitHub Actions workflow toevoegen om de site te valideren of automatisch te deployen.

