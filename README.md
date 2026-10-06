# BTSSIO-Applications

Projet de développement d'applications pour l'oral BTS SIO (E6) — contexte **GSB (Galaxy Swiss Bourdin)**.

## Contenu du dépôt

| Dossier | Description |
|---|---|
| [`web/`](web/) | Application web — PHP natif (architecture MVC) + MySQL |
| [`mobile/`](mobile/) | Application mobile — technologie à définir |
| [`docs/`](docs/) | Documentation : contexte GSB, planning (Gantt), maquettes, MCD/MLD |

## Conventions

**Commits** — préfixer par le projet concerné :

- `[web] ajout de la page de connexion`
- `[mobile] écran liste des visites`
- `[docs] mise à jour du Gantt`
- `[global] ...` pour ce qui concerne tout le dépôt

**Branches** — une branche par fonctionnalité, préfixée par le projet :

- `web/authentification`, `mobile/liste-rapports`, `docs/mcd`
- Fusion dans `main` une fois la fonctionnalité terminée et testée.

**Tags** — un tag par version livrée : `web-v1.0`, `mobile-v1.0`.

## Voir l'historique d'un seul projet

```bash
git log --oneline -- web/
git log --oneline -- mobile/
```

## Auteur

Clothilde Leali — BTS SIO option SLAM
