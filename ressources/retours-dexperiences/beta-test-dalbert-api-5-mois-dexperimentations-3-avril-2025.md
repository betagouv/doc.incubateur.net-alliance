---
description: >-
  En marge du forum beta, les startups d'État font leurs retours d'expérience
  sur quelques mois d'expérimentation libre sur Albert-api.
icon: sparkles
---

# Beta-test d'Albert-Api, 5 mois d'expérimentations｜3 avril 2025



{% hint style="info" %}
**Date** : 03/04/2025\
**Animé par** : Elsa Le Duigou et Jules Pondard\
**Les participants** : services numériques de l’État de la communauté beta.gouv\
**L'objectif** : faire le bilan, à 5 mois, de l’expérimentation sur l’Albert API
{% endhint %}

{% embed url="https://docs.google.com/presentation/d/1lKdhyEs8O1QkE8_voDrdFigt55vGJi3twxWDXzUDdjk/edit#slide=id.g3429ea5c187_0_501" %}



### Présentation d'Albert API

Albert API est une **boîte à outils d’IA souveraine** conçue pour faciliter l’intégration de l’IA générative dans les services publics. Elle vise à fournir :

* Des briques prêtes à l’emploi (LLM, OCR, RAG, etc.)
* Une infrastructure mutualisée
* Une interface unifiée via une API Gateway
* Des usages sécurisés et peu coûteux

#### Ses caractéristiques

| **Avantages clés**         | Souveraineté, sécurité, puissance, faible coût                           |
| -------------------------- | ------------------------------------------------------------------------ |
| **Profils ciblés**         | Explorateurs (analystes), constructeurs (développeurs), opérateurs       |
| **Services disponibles**   | LLM, speech-to-text, RAG sur fichiers PDF                                |
| **À venir**                | OCR amélioré, deepsearch, suivi précis par utilisateur                   |
| **Chiffres clefs d’usage** | 50k requêtes/semaines, 62 produits utilisateurs, 1/2 de part d’embedding |



## Les cas d'usage expérimentés par les services numérique de la communauté

<details>

<summary>Coop de la médiation numérique</summary>

* **Finalité** : Assistant conversationnel à destination des médiateurs numériques.
* **Fonctionnalités** : Recherche documentaire et web (filtrée via Brave), réponse aux questions des usagers.
* **Albert utilisé pour** : Embedding des contenus.
* **Limites identifiées** :
  * Performance aléatoire sur l’infrastructure Scaleway.
  * Impossibilité de spécifier une whitelist de domaines pour la recherche.

</details>

<details>

<summary>Conseil de l’évaluation de l’École (CEE)</summary>

* **Finalité** : Analyse des rapports d’évaluation produits chaque année par le conseil d'évaluation de l'école (env. 12 000/an, 60 000 en base).

- **Objectif** : Identifier des tendances et générer des synthèses pour orienter les politiques publiques.

* **Albert utilisé pour** : Embedding + RAG sur corpus documentaire.

- **Défis** :
  * Format des documents très hétérogène (PDF image, tableaux complexes…).
  * Taux d’erreur de \~20% sur certaines extractions (numéros de page notamment).
  * Produit encore en phase de test.

</details>

<details>

<summary>SignalConso</summary>

* **Finalité** : Optimiser le traitement automatisé des signalements citoyens.

- **Fonctionnalités IA** :
  * Résumé automatique avec détection d’insultes
  * Vérification de la compétence DGCCRF via le Code conso (RAG)
  * Identification de l’entreprise à partir du signalement

* **Albert utilisé pour** : RAG juridique + résumés

- **Points de vigilance** :
  * Hallucinations lors de l’analyse juridique
  * Difficultés à harmoniser les libellés pour les statistiques
  * Distinction délicate entre insultes directes et rapportées

</details>

<details>

<summary>Mon Devis Sans Oubli</summary>

* **Finalité** : Analyse automatique de devis dans le cadre de rénovations énergétiques.

- **Pipeline technique** :
  * Extraction de données personnelles via Albert (PDF → texte)
  * Reconnaissance des gestes de travaux via Mistral

* **Volumétrie** : 1300 devis pour 1000 utilisateurs

- **Albert utilisé pour** : Traitement structuré initial avant anonymisation

* **Défis** :
  * Problèmes d’OCR sur les scans
  * Limites du traitement synchrone (réponse attendue < 5 min)
  * Possibilité de recentrer l’ensemble du traitement dans Albert à terme

</details>

<details>

<summary>Barnabé</summary>

* **Finalité** : Synthèse thématique de lots de documents (ex. Contrats de Ville, Quartiers 2030)

- **Albert utilisé pour** :
  * Embedding
  * OCR
  * Traitement batch (asynchrone)

* **Technos associées** : LlamaParse

- **Limites** :
  * Taille de fenêtre de contexte trop restreinte pour certains cas d’analyse
  * Usage uniquement batch à ce stade, mais bonne complémentarité avec les objectifs d’Albert

</details>



## :sparkles: Conclusions et perspectives

#### Forces identifiées

* Mutualisation des outils IA entre administrations
* Large panel d’usages déjà opérationnels
* Flexibilité dans les architectures déployées (embedding, RAG, OCR, etc.)
* Coût d’usage maîtrisé

#### Axes d’amélioration

* Stabilisation des performances sur l'infra
* Amélioration de l’OCR sur documents complexes
* Meilleure adaptation aux spécificités des langages administratifs et juridiques
* Extension de l’API aux cas d’usage batch (type Barnabé)



### Contact

{% hint style="success" %}
**📅 Pour prendre rendez-vous avec l’équipe Albert :**\
👉 [albertapi.youcanbook.me](http://albertapi.youcanbook.me)

📧 Pour toute question produit, contacter l’équipe via vos canaux habituels sur [beta.gouv.fr](http://beta.gouv.fr)
{% endhint %}

###

