Ametra statisk nettside

Innhold:
- index.html
- assets/ametra-logo.svg
- robots.txt
- sitemap.xml
- staticwebapp.config.json

Publisering i Azure Static Web Apps:
1. Last opp hele innholdet i denne mappen, ikke bare index.html.
2. Sørg for at index.html ligger i rot.
3. Sett custom domain til https://ametra.no.
4. Etter publisering: test https://ametra.no/robots.txt og https://ametra.no/sitemap.xml.

Merk:
- Siden bruker eksterne Unsplash-bilder. Bytt gjerne til lokale bilder i /assets senere for enda bedre kontroll og hastighet.
- Canonical URL og sitemap er satt til https://ametra.no/.


Endringer i denne versjonen:
- Mørk logo i header, uten undertittel.
- Ny favicon: assets/symbol-favicon.png.
- Fjernet kortet “AI i produkter og operative systemer”.
- Oppdatert posisjoneringstekst og fjernet bransje-chips.
- Fjernet punktum etter hovedsetningen “Senior softwarekompetanse for tekniske systemer”.


Oppdatert versjon: erfaring-seksjonen er byttet til case-kort gruppert etter bransjeområde.


V4-endringer:
- Fjernet hero-kortet “Når systemene må virke”.
- Fjernet seksjonen “Senior / Teknisk / Tett på”.


STAGING NOTE:
This package is configured for the Azure staging URL:
https://calm-cliff-0f4ae4003.7.azurestaticapps.net/
Switch canonical/OG URLs back to https://ametra.no/ before production.


v29: Dark mode refined with premium contrast, layered surfaces, and dark positioning cards.


PRODUCTION NOTE:
This package is configured for https://ametra.no/
