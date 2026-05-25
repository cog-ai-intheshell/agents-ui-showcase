# Agent UI Mesh

Vitrine HTML autonome pour visualiser un graphe d'agents UI qui interagissent autour d'une tache complexe : survey, planning, orchestration, recherche, calcul, review, critique, adjudication et formatting.

Inspiration : Hugging Face `physics-intern`, notamment l'idee d'un agent scientifique autonome evalue par un benchmark de type CritPt.

Le graphe principal reprend le style visuel de la reference fournie : roles en capsules lumineuses, visage circulaire pour chaque agent et arcs fins entre agents, avec une grille de fond issue du design system.

## Lancer

```bash
cd /Users/augustinmorieux/Desktop/dum-e/agents-ui-showcase
python3 -m http.server 8770
```

Puis ouvrir :

```text
http://localhost:8770
```
