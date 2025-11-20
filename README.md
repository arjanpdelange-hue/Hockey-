
# 🏑 Hockey Arbitrage App

Dit is een zelfstandige, mobielvriendelijke webapplicatie ontworpen om scheidsrechters te helpen bij het bijhouden van de score, de wedstrijdklok, actieve strafkaarten en de tijdlijn van gebeurtenissen tijdens een veldhockeywedstrijd.

De applicatie is gebouwd met pure HTML, CSS (via de TailwindCSS CDN) en JavaScript, en heeft **geen** backend of build-stappen nodig.

## 🚀 Hoe te Gebruiken (GitHub Pages)

Omdat dit een enkel HTML-bestand is zonder afhankelijkheden, is het extreem eenvoudig om te hosten met GitHub Pages.

1.  **Maak een nieuwe Repository** aan op GitHub.
2.  **Upload** het bestand `index.html` naar de hoofdmap van de repository.
3.  Ga naar de **Instellingen** (Settings) van de repository.
4.  Kies **Pages** in het linkermenu.
5.  Onder 'Build and deployment', selecteer **Deploy from a branch** en kies de `main` (of `master`) branch en de `/ (root)` map.
6.  Sla de instellingen op. GitHub Pages zal de app binnen enkele minuten deployen op een URL zoals `https://[jouw-gebruikersnaam].github.io/[repository-naam]`.

**Direct Gebruik:** Je kunt ook gewoon het bestand `index.html` **downloaden** en met elke moderne webbrowser (Chrome, Safari, Firefox) lokaal openen!

## ✨ Belangrijkste Functies

* **Wedstrijdklok en Kwartteller:** Houd de speeltijd nauwkeurig bij.
* **Aanpasbare Instellingen:** Stel het aantal kwarten (1-4) en de duur per kwart in (standaard 17:30).
* **Scoretracking:** Snel doelpunten toekennen (veld, strafcorner, strafbal).
* **Kaart Timers:** Automatisch aftellende timers voor Groene (2 min) en Gele (5/10 min) kaarten. Rood (definitief) wordt ook gelogd.
* **Rugnummer Invoer:** Vraag om het rugnummer voor zowel kaarten als doelpunten.
* **Wedstrijd Tijdlijn:** Een gedetailleerde log van alle gebeurtenissen.
* **PDF Export:** Genereer een overzichtelijke PDF van de tijdlijn en eindscore.
* **Audio/Vibratie Signalen:** Duidelijke signalen voor het einde van het kwart en het aflopen van strafkaarten.

## ⚖️ Licentie

Dit project is beschikbaar onder de [MIT License](LICENSE).
