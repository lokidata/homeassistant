# homeassistant

Il s'agit de mon implémentation du chauffage par fil pilote sur home assistant.

Très fortement inspiré du travail de @mycanaletto https://github.com/mycanaletto/hass-mondon.

Utilisation de schedy pour la planification.

Je dispose d'un module téléinfo qui me permet de remonter la puissance souscrite et la puissance active courante.

Cela me permet de faire un délestage dynamique des radiateurs si besoin.

Les cards lovelace utilisent les composants:
- custom:stack-in-card
- custom:simple-thermostat
- custom:fold-entity-row
- custom:multiple-entity-row

![lovelace](https://github.com/lokidata/homeassistant/blob/23089727f569a4ffb0ece4a9bd2f61f72b69178c/lovelace/heating_card_example.png)