---
description: Introduction
icon: torii-gate
---

# Le socle interministériel d'intelligence artificielle générative

### Pourquoi un socle mutualisé ?

Depuis 2023, l'ensemble des ministères s'est engagé dans le déploiement de l'intelligence artificielle générative. Si quelques projets ont atteint une maturité opérationnelle, la grande majorité demeure au stade expérimental. Ce constat révèle une difficulté récurrente : chaque administration consacre l'essentiel de ses ressources à reconstruire les mêmes briques techniques de base plutôt qu'à développer ses applications métiers spécifiques.

Cette dispersion des efforts produit trois effets indésirables :

* **Un gaspillage de ressources publiques** : duplication des investissements en infrastructure, en compétences techniques et en solutions logicielles similaires d'un ministère à l'autre ;
* **Une lenteur de déploiement** : les équipes métiers passent plus de temps à résoudre des problèmes techniques communs qu'à concevoir leurs cas d'usage spécifiques ;
* **Un impact limité** : peu de projets sont passés à l'échelle pour produire des gains tangibles pour les agents ou les usagers \[1].

**La phase d'expérimentation est achevée. L'État entre désormais dans une phase d'industrialisation de l'intelligence artificielle générative.** Cette transition exige une stratégie technique structurée, qui tire les enseignements des deux années écoulées pour permettre un déploiement à grande échelle, efficace et maîtrisé.

### Le socle

Face à ce constat et à cette nécessité, la Direction Interministérielle du Numérique (DINUM) se dote d'une stratégie technique 2026 fondée sur une répartition claire des rôles entre niveau interministériel et niveau ministériel :

**La DINUM conçoit, opère et met à disposition un Socle Interministériel d'Intelligence Artificielle Générative** comprenant :

* L'infrastructure technique commune (puissance de calcul, modèles, sécurité) et l'accompagnement à son utilisation par les ministères ;
* Une boîte à outils transverses (transcription, traduction, interrogation documentaire) ;
* Une plateforme de données partagées ;
* Des applicatifs génériques de base (chatbot, transcription, etc).

**Les ministères conservent l'entière responsabilité de leurs applications métiers** :

* Conception des cas d'usage adaptés à leurs politiques publiques ;
* Acquisition (ou développement) de solutions spécifiques à leurs besoins ;
* Gestion de leurs données sensibles et de leurs processus métiers.

**Des ministères peuvent devenir chefs de file sur des briques à vocation interministérielle** :

* En développant des composants réutilisables qui enrichissent le Socle (instanciés et opérés par la DINUM) ;
* En opérant directement pour l'interministériel des services d'intérêt commun qu'ils hébergent et maintiennent ;
* En partageant leur expertise et leurs solutions avec l'ensemble de l'administration.

Cette permet aux administrations de se concentrer sur leur cœur de mission – concevoir et déployer des services publics augmentés par l'IA – tout en s'appuyant sur une infrastructure commune robuste, sécurisée et souveraine. Elle valorise également les développements ministériels d'intérêt général en les rendant accessibles à toute l'administration.

**Le présent document constitue la stratégie technique qui guidera cette industrialisation en 2026.** Il détaille l'architecture du Socle Interministériel d'Intelligence Artificielle Générative, ses principes de gouvernance et ses modalités de mise en œuvre pour permettre le passage à l'échelle des projets d'IA dans l'administration.

### Principes directeurs

**Mutualiser, sans centraliser**

L'idée centrale de ce socle est de proposer des sources de mutualisation sur des briques de fondation, ainsi qu'un accompagnement au déploiement et à l'accélération de projets IA. Les ministères gardent une totale autonomie pour acheter les solutions métiers ou les développer, préservant ainsi la richesse de leurs cas d'usages.



**Autonomie technologie et subsidiarité**

Le Socle développe et privilégie systématiquement des solutions dont le code source est ouvert, auditables et dont l'État peut assurer l'opération et la maintenance à long terme.

Chaque composant du Socle, qu'il soit développé par la DINUM ou par une entreprise, doit pouvoir être remplacé indépendamment sans affecter le reste du système

Chaque application s'appuyant sur le Socle doit pouvoir substituer des outils du Socle par des outils du marché, et vice versa.

Les interfaces entre couches respectent des standards ouverts et largement adoptés dans l'industrie, (ex : le standard OpenAI pour les API d'inférence).

La DINUM et les ministères gardent, autant que possible, la maîtrise technologie des outils IA déployés.



**Sécurité « by-design »**

La sécurité, aussi bien d'un point de vue cyber, que de sécurité de systèmes IA, n'est pas une couche ajoutée mais un principe intégré à chaque niveau de l'architecture.

Les systèmes proposés dans le Socle sont, autant que possible, compatible avec l'usage de données sensibles, et font l'objet d'homologation de sécurité.

L'hébergement doit être effectué sur des infrastructures certifiées SecNumCloud, et proposer un silotage des données dès que possible.



**Observabilité**

Toutes les opérations effectuées sur le socle sont tracées, mesurées et analysables.

Les métriques de performance, coût, qualité et usage sont collectées en temps réel et mises à disposition des équipes techniques et des instances de gouvernance. Cette transparence (qui peut parfois être limitée au regard des besoins de sécurité) permet l'amélioration continue et le respect des obligations de redevabilité démocratique.



**Privilégier la qualité à la quantité**

Le Socle s'inscrit dans une logique de concentration des efforts sur l'essentiel. Les ressources publiques sont allouées de manière ciblée sur les briques techniques à plus forte valeur ajoutée pour l'ensemble de l'administration, tout en préservant la capacité d'innovation des ministères pour explorer des cas d'usage et des solutions adaptées à leurs besoins spécifiques. Le Socle adopte donc une philosophie fondée sur la qualité plutôt que la quantité : proposer un nombre limité de fonctionnalités fondamentales, mais garantir l'excellence dans la qualité des services et leur fiabilité.
