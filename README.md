# homeassistant

Il s'agit de mon implémentation du chauffage par fil pilote sur home assistant.

Très fortement inspiré du travail de @mycanaletto https://github.com/mycanaletto/hass-mondon.

Utilisation de schedy pour la planification

Je dispose d'un module téléinfo qui me permet de remonter la puissance souscrite et la puissance active courante.

Cela me permet de faire un délestage dynamique des radiateurs si besoin

Les cards lovelace utilise les composants:
- custom:stack-in-card
- custom:simple-thermostat
- custom:fold-entity-row
- custom:multiple-entity-row