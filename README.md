# Opsflow Analytics

> Plateforme data de bout en bout pour piloter **Alya Insurance Services**,
> prestataire B2B fictif de gestion de sinistres (~200 agents, 3 sites, 50k dossiers/mois).

## Pourquoi ce projet

Ce projet est le fil rouge technique de ma formation Analytics Engineer. Il reproduit
les problématiques d'une organisation de services que je connais bien (CAF, centres
de contacts) pour apprendre la stack AE moderne dans des conditions réalistes.

## Stack cible (à construire progressivement)

- **SQL** — langage principal de transformation
- **DuckDB** — base analytique locale de développement
- **BigQuery** — warehouse cloud de production
- **dbt Core** — orchestration des transformations
- **Dagster** — orchestration des pipelines
- **Power BI** — dashboards de pilotage
- **GitHub Actions** — CI/CD

## État actuel

🚧 Projet en construction — Mois 1 : génération des premières données.

## Arborescence prévue

opsflow-analytics/
├── data/            # datasets générés (gitignored partiellement)
├── generator/       # scripts Python de génération de données
├── sql/             # requêtes d'exploration
├── dbt/             # projet dbt (à venir)
├── dashboards/      # fichiers Power BI (à venir)
└── docs/            # documentation

## Progression

- [x] Setup repo et README
- [ ] Générateur Python de données fictives
- [ ] Premier dataset chargé dans DuckDB
- [ ] Modélisation dimensionnelle Kimball
- [ ] Projet dbt complet
- [ ] Dashboards Power BI

- [ ] ... (suite selon roadmap)