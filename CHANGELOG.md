# Historique des mises à jour — Melissa Lefèvre Planning & Clients

Ce fichier liste toutes les améliorations apportées à l'application depuis la mise en place du numéro de version (visible tout en bas de chaque onglet de l'app). Les versions sont classées de la plus récente à la plus ancienne.

---

## v1.7.0 — 21 août 2026

- **Créneaux personnels indisponibles** : nouveau bouton « 🚫 Bloquer un créneau » à côté de « + Nouveau rendez-vous ». Permet de réserver une plage horaire (ex : 10/08/2026 de 8h00 à 12h00) sans rendez-vous client — apparaît grisée sur le planning, modifiable et supprimable en la touchant.
- **Impossible de réserver sur un créneau bloqué** : la prise de rendez-vous refuse désormais tout chevauchement avec un créneau personnel, exactement comme pour un double rendez-vous.
- **Plages disponibles visibles** : dès qu'une date est choisie dans le formulaire de rendez-vous, les créneaux libres de la journée s'affichent directement (rendez-vous existants et créneaux bloqués déjà exclus).
- **Suggestion automatique d'horaire** : une fois la cliente sélectionnée (et la date connue), le prochain horaire disponible pour la durée de la prestation est proposé avec un bouton « Utiliser ce créneau » — jamais rempli automatiquement, toujours modifiable.

## v1.6.0 — 21 août 2026

- **Adresse personnelle et kilométrage quotidien** : nouvel écran « 🏠 Mon adresse » (menu ⋯) pour renseigner l'adresse de départ, modifiable en cas de déménagement. Le planning affiche désormais le nombre de kilomètres réalisés chaque jour (domicile → chaque rendez-vous dans l'ordre → retour domicile).
- **Kilométrage dans les rapports Excel** : les exports semaine/mois incluent une section « 🚗 Kilométrage professionnel » avec le détail jour par jour et un total.

## v1.5.0 — 21 août 2026

- **Nouvel onglet « Manuel »** : guide d'utilisation complet directement dans l'app, accessible à tout moment (même hors ligne), pas besoin de le chercher ailleurs.
- **Suivi de version** : mise en place de ce fichier de changelog et du numéro de version visible en bas de chaque onglet de l'app.

## v1.4.0 — 20 août 2026

- **Formule de coloration** : nouveau champ qui apparaît automatiquement quand la prestation choisie est « Coloration ». La dernière formule utilisée pour une cliente est suggérée automatiquement avec un bouton « Réutiliser » — pratique pour les clientes fidèles à une même teinte.
- **Historique cliquable** : dans la fiche d'une cliente, chaque ligne de l'historique des rendez-vous est désormais tactile et ouvre le détail complet du rendez-vous correspondant (y compris la formule de coloration utilisée ce jour-là).
- **Archivage par mois** : nouvelle section dans Sauvegarde permettant de choisir un mois passé, d'en exporter automatiquement les rendez-vous en Excel, puis de les supprimer pour garder l'application légère sur la durée (les fiches clientes ne sont jamais concernées).
- **Bandeau de connexion fiable** : refonte de l'indicateur de synchronisation, désormais basé directement sur l'état réel de connexion de l'appareil plutôt que sur la réponse de Firebase (qui pouvait rester silencieuse indéfiniment hors ligne). Un bandeau bien visible en haut de l'écran apparaît dès que la connexion est perdue ou qu'une synchronisation est en attente, et disparaît de lui-même une fois tout à jour.
- **Protection contre la perte de saisie** : si l'app se ferme ou se recharge avant l'enregistrement d'une fiche ou d'un rendez-vous en cours de saisie, un message propose de récupérer automatiquement la saisie non enregistrée à la prochaine ouverture.
- **Correction de l'affichage sur iPhone** : le bouton de menu en haut à droite n'est plus caché derrière l'horloge/l'encoche en mode application installée (écran d'accueil).
- **Icône d'application** : ajout d'une icône personnalisée (monogramme « ML » doré) et d'un fichier `manifest.json`, pour une installation propre sur l'écran d'accueil iPhone et Android.

---

*Versions antérieures à la mise en place de ce suivi (mise en ligne initiale, connexion Firebase, synchronisation multi-appareils, sauvegarde automatique, export Excel, fiche technique capillaire, etc.) : non détaillées ici, l'application étant alors en cours de mise au point avant la remise à Melissa.*
