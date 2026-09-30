
### **Sommaire**

- [[#**BTS SIO 2026 - 2028**|BTS SIO 2026 - 2028]]
	- [[#**Veille Technologique**|Veille Technologique]]
	- [[#**Auto-Formation**|Auto-Formation]]

---
# **BTS SIO 2026 - 2028**

---

## **Veille Technologique**

Bienvenue sur ma veille technologique ! J'y traite actuellement les sujets suivants :

- [[#La cybersécurité orientée vers les solutions logicielles.]]
- [[#L'évolution de l'intelligence artificielle et son impact sur le développement d'applications.]]
- [[#Creative Coding et génération procédurale : l'algorithmique au service des visuels.]]

- [[#~En cours de traitement|Articles en cours de traitement.]]

---

## La cybersécurité orientée vers les solutions logicielles.

```dataview
TABLE date as "Date", source as "Source", url as "Lien"
FROM "Robin Arnace - Espace de travail/Veille Technologique"
WHERE theme = "Cybersec & Logiciels"
SORT date desc
```

---

## L'évolution de l'intelligence artificielle et son impact sur le développement d'applications.

```dataview
TABLE date as "Date", source as "Source", url as "Lien"
FROM "Robin Arnace - Espace de travail/Veille Technologique"
WHERE theme = "IA & Dev"
SORT date desc
```

---

## Creative Coding et génération procédurale : l'algorithmique au service des visuels.

```dataview
TABLE date as "Date", source as "Source", url as "Lien"
FROM "Robin Arnace - Espace de travail/Veille Technologique"
WHERE theme = "Creative Coding"
SORT date desc
```

---

## En cours de traitement.

```dataview
TABLE date as "Date", source as "Source", url as "Lien"
FROM "Robin Arnace - Espace de travail/Veille Technologique"
WHERE theme = "En cours de traitement"
SORT date desc
```

---
## **Auto-Formation**

Dans cette section, je consigne les formations que je repère en dehors du BTS, dans l’objectif d’obtenir de nouvelles compétences ou de consolider celles que j’ai déjà. Elles sont sélectionnées en partant du principe qu’elles peuvent m’aider dans ma carrière professionnelle, et qu’elles correspondent à ma spécialisation (développement d’applications).

- [[#Outils et Environnements]]
- [[#Langages]]
- [[#Workflow]]
- [[#Autre]]

---

### Outils et Environnements

```dataview
TABLE 
  statut as "Progression",
  join(competences, ", ") as "Compétences",
  validation as "Validation",
  url as "Lien"
FROM "Robin Arnace - Espace de travail/Auto-Formation"
WHERE categorie = "Outils et Environnements"
SORT statut asc
```

---

### Langages

```dataview
TABLE 
  statut as "Progression",
  join(competences, ", ") as "Compétences",
  validation as "Validation",
  url as "Lien"
FROM "Robin Arnace - Espace de travail/Auto-Formation"
WHERE categorie = "Langages"
SORT statut asc
```

---

### Workflow

```dataview
TABLE 
  statut as "Progression",
  join(competences, ", ") as "Compétences",
  validation as "Validation",
  url as "Lien"
FROM "Robin Arnace - Espace de travail/Auto-Formation"
WHERE categorie = "Workflow"
SORT statut asc
```

---

### Autre

```dataview
TABLE 
  statut as "Progression",
  join(competences, ", ") as "Compétences",
  validation as "Validation",
  url as "Lien"
FROM "Robin Arnace - Espace de travail/Auto-Formation"
WHERE categorie = "Autre"
SORT statut asc
```