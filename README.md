# Neuromente

Statische website voor Neuromente, gebouwd met Hugo en gepubliceerd via GitHub Pages.

## Lokaal bekijken

```sh
hugo server
```

Open daarna `http://localhost:1313`.

## Inhoud aanpassen

- Pagina-inhoud staat in `content/`.
- Contactgegevens en de Formdesk-URL staan centraal in `hugo.toml`.
- Vormgeving staat in `assets/css/main.css`.
- Een push naar `main` publiceert de website via GitHub Actions.

## Voor livegang

Vul en controleer minimaal:

- naam en registraties van de behandelaar;
- doelgroep, zorgaanbod en uitsluitingscriteria;
- adres, telefoonnummer en bereikbaarheid;
- wachttijden, tarieven, contracten en vergoedingen;
- privacyverklaring, klachtenregeling, betalingsvoorwaarden en kwaliteitsstatuut;
- de definitieve Formdesk-URL in `hugo.toml`;
- DNS-instellingen voor `neuromente.nl` en GitHub Pages-instellingen.
