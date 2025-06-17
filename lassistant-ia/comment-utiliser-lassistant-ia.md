---
description: >-
  Nous détaillons ici quelques définitions et les bonnes pratiques à respecter
  pour utiliser l'Assistant conversationnel de l'État.
hidden: true
icon: message-question
coverY: 0
layout:
  cover:
    visible: true
    size: full
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Comment utiliser l'Assistant IA

Spécialement conçu pour les agents de la fonction publique d'État, &#x6C;**'**[**Assistant conversationnel**](https://albert.numerique.gouv.fr/) **comprend vos questions formulées en langage naturel, et vous assiste dans vos tâches du quotidien.**&#x20;



### Fonctionalités

Voici ce que permet aujourd’hui l'Assistant IA :

* Rédaction assistée (notes, mails, synthèses)
  * Demandez directement dans le chat en copiant-collant les éléments de contextes souhaités
* Résumé automatique de textes longs
  * Demandez directement dans le chat en copiant-collant les éléments de contextes souhaités
* Extraction d’informations depuis un document
  * Glissez déposé simplement un ou des documents dans le chat, ou clickez sur le + à gauche de la barre de chat pour ajouter des documents à votre conversation. NB: ceux cis ne seront pas accessibles via d'autres conversations.
* Recherche documentaire contextuelle (RAG)&#x20;
  * Pour voir les collections & documents disponibles, tapez # directement dans le chat
* Utiliser les ébauches de prompts pré-configurés:
  * En tapant / dans la. barre de chat, découvrez les prompts auxquels vous avez accès pour simplifier vos tâches répétitives
* Gestion des conversations
  * Dans la barre de gauche! Vous pouvez également crééer des dossiers de conversations pour mieux vous y retrouver
* Mémoire contextuelle partagée sur les conversations
  * En cliquant sur l'icône utilisateur, accédez aux paramètres, puis rendez-vous dans personnalisation, et enfin "Gérer" dans l'onglet "Mémoire". Ajoutez les informations que vous souhaiteriez que l'IA connaissent sur vous ou votre travail à travers les conversations.
*   **Fonctionalités avancées** : dans l'onglet "espace de travail". Cet onglet n'apparaît que si l'accès à au moins unez des fonctionnalité ci-dessous vous est autorisée. Pour en avoir plus sur les autorisations ou demander l'accès, rendez-vous sur le Canal Tchap

    * Création de collections (bases documentaires personnalisées)
    * Configuration de modèles personnalisés (agents)
    * Templates de prompts
    * Développement de fonctions Python (utilisateurs avancés uniquement)

    Plus de documentation sur ces fonctionnalités directement sur [docs.openwebui.com](https://docs.openwebui.com)

{% hint style="info" %}
Afin de bien comprendre comment utiliser un assistant conversationnel IA et en quoi il peut vous être utile, il est important de comprendre ce qu'est (et n'est pas) une telle interface.&#x20;

C'est pourquoi nous vous proposons dans la suite une brève explication de ces concepts.
{% endhint %}

### Qu'est-ce qu'un Assistant Conversationnel IA ?

Un assistant conversationnel IA est une interface conçu pour interagir avec les utilisateurs en langage naturel, en s'appuyant sur un LLM (modèle de language).

Les LLMs sont des modèles entrainés sur d'immenses corpus documentaire (≃tout internet) pour prévoir la suit d'une phrase ou dd'un bout de texte (le "prompt"). Les assistants conversationnels gèrent le fait d'envoyer tout l'historique d'une conversation et d'autres éléments contextuels (documents ajoutés, préférences utilisateurs) pour assurer la cohérence de l'intéraction et augmenter son utilité pour l'utilisateur, ainsi que de traiter le texte en sortie du LLM pour faciliter sa comprénsion (formattage de code, mise en gras ou en italique, censure d'éléments choquants...).&#x20;

Aujourd'hui, lcréer un LLM spécifique et adapté à nos cas d'usages est compliqué et coûteux, c'est pourquoi le choix est fait de s'appuyer sur des modèles open-source ou propriétaires mais respectant certains critères liés à la souveraineté.&#x20;

Si une partie de la performance des cette intrface est donc due aux modèles sous-jacents selectionnés, d'importantes améliorations sont possibles en travaillant sur l'intégration des données externes, de celles de l'utilisateur ainsi que de ses choix de configuration.

### En quoi peut vous aider Albert conversation ?&#x20;

Albert conversation peut vous aider de multiples façons, selon vos besoins professionnels. Voici les principaux bénéfices et usages d'Albert conversation :&#x20;

* **La rédaction et la reformulation** : création, adaptation et amélioration de contenus textuels variés pour pallier au syndrome de la feuille blanche notamment.
* **La prise de décision** : analyse de problèmes et proposition de solutions ou recommandations pour élargir votre champ des possibles.
* **La recherche et synthèse d'informations** : accès à une base de connaissances pour fournir des informations précises et à jour pour toujours travailler sur des informations fiables sereinement.&#x20;
* **L'analyse et la synthèse de documents** : analyse de vos documents de travail pour en extraire l'information plus rapidement.&#x20;



### Quelles bonnes pratiques appliquées pour optimiser l'usage d'Albert conversation ?&#x20;

Albert conversation comprend le langage naturel. Toutefois, pour en tirer le meilleur parti et obtenir des résultats optimaux, nous vous recommandons les pratiques suivantes :&#x20;

* **Formulez des requêtes précises et contextualisées** : soyez le plus précis possible dans vos questions afin d’obtenir des réponses pertinentes et adaptées à vos besoins. N’hésitez pas à donner du contexte, surtout si vous travaillez sur un projet particulier, et à indiquer le format de réponse souhaité, que ce soit une liste, un texte synthétique ou un tableau. Mentionnez également votre niveau de connaissance sur le sujet pour recevoir des explications appropriées.
* **Reformulez lorsque la réponse ne correspond pas à vos attentes** : afin de rendre vos échanges plus efficaces, il est conseillé d’avancer par étapes, surtout pour les sujets complexes. Commencez par une question générale, puis affinez progressivement avec des questions complémentaires. Si la réponse ne correspond pas à vos attentes, reformulez votre demande ou donnez un exemple concret pour illustrer ce que vous recherchez. N’hésitez pas à faire part de vos préférences à l’assistant pour qu’il puisse mieux s’adapter à vos besoins.
* **Gardez un regard critique quant aux réponses fournies**  :  il est important de garder un esprit critique lors de l’utilisation de l’assistant IA. Même s’il est performant, il peut arriver qu’il se trompe ou fournisse des informations inexactes. Prenez l’habitude de vérifier les données importantes auprès d’autres sources fiables et relisez toujours les textes générés avant de les utiliser. Si vous identifiez une erreur, signalez-la afin de contribuer à l’amélioration du service.
* **Considérez votre assistant comme un assistant qui amplifie vos capacités, et non comme un substitut à votre expertise ou à votre jugement** : gardez à l’esprit que la protection de vos données personnelles est primordiale. Evitez de partager des informations sensibles. Rappelez-vous que l’assistant est un outil destiné à vous aider dans vos tâches, mais les décisions finales vous appartiennent. Il peut parfois manquer de nuance sur certains sujets complexes ou culturels, c’est pourquoi il doit être vu comme un soutien qui complète vos compétences, et non comme un remplaçant.



### Quels modèles sont proposés dans l'Assistant conversationnel ?&#x20;

Les modèles actuellement proposés dans l'Assistant conversationnel s'appuie sur les modèles généralistes proposés par Albert-API dont l'apprentissage prend fin&#x20;

* au 4ème trimestre 2023 pour Albert-tâches simples&#x20;
* au 4ème trimestre 2024 pour Albert-tâches complexes &#x20;

[En savoir plus sur Albert-api](../faire-des-services-ia-au-sein-de-letat/albert-api-linfra-ia-souveraine-de-letat.md)&#x20;



