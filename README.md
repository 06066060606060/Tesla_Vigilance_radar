# Tesla_Vigilance_radar

Page web de consultation de points de contrôle fixes, avec estimation des distances routières via OSRM et géolocalisation du navigateur.

Le site est dans `docs/`. Servez ce dossier en HTTPS ou sur localhost : la géolocalisation nécessite un contexte sécurisé. Le calcul routier transmet la position au service public OSRM. Le cap GPS et la disponibilité du service influencent les résultats ; l'itinéraire exact et le sens contrôlé ne sont pas connus.

Les données `docs/radars.csv` proviennent du [Ministère de l’Intérieur sur data.gouv.fr](https://www.data.gouv.fr/datasets/liste-des-radars-fixes-en-france/), version du 30 décembre 2025, sous Licence Ouverte 2.0. Elles ne sont pas actualisées automatiquement et ne couvrent pas les contrôles mobiles.
