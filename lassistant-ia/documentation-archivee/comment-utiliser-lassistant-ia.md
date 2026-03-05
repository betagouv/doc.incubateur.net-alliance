---
description: >-
  Nous détaillons ici quelques définitions et les bonnes pratiques à respecter
  pour utiliser l'assistant conversationnel de l'État.
icon: message-question
coverY: 0
---

# Comment utiliser l'Assistant IA

Spécialement conçu pour les agents de la fonction publique d'État, &#x6C;**'**[**Assistant conversationnel**](https://albert.numerique.gouv.fr/) **comprend vos questions formulées en langage naturel, et vous assiste dans vos tâches du quotidien.**&#x20;

### Fonctionnalités

Voici ce que permet aujourd’hui l’Assistant IA :

**✍️ Rédaction assistée (notes, mails, synthèses)**

> Demandez directement dans le chat en copiant-collant les éléments de contexte souhaités.

**📄 Résumé automatique de textes longs**

> Demandez directement dans le chat en copiant-collant les éléments de contexte souhaités.

**🔍 Extraction d’informations depuis un document**

> Glissez-déposez un ou plusieurs documents dans le chat, ou cliquez sur le **+** à gauche de la barre de chat pour les ajouter à la conversation.\
> **NB** : ces documents ne seront pas accessibles depuis d’autres conversations.

**📚 Recherche documentaire contextuelle (RAG)**

> Pour voir les collections et documents disponibles, tapez **#** directement dans le chat.

**⚙️ Utiliser les ébauches de prompts préconfigurés**

> En tapant **/** dans la barre de chat, découvrez les prompts disponibles pour simplifier vos tâches répétitives.

**💬 Gestion des conversations**

> Dans la barre de gauche ! Vous pouvez également créer des dossiers de conversations pour mieux vous y retrouver.

**🧠 Mémoire contextuelle partagée entre conversations**

> En cliquant sur l’icône utilisateur, accédez aux paramètres, puis à l’onglet **Personnalisation**, et enfin à **Gérer** dans la section **Mémoire**.\
> Ajoutez les informations que vous souhaitez que l’IA connaisse sur vous ou votre travail à travers les conversations.

### Fonctionnalités avancées (dans l’onglet **Espace de travail**)

Cet onglet n’apparaît que si vous avez accès à au moins une des fonctionnalités ci-dessous. Pour plus d’informations ou pour demander un accès, rendez-vous sur le **canal Tchap**.

* Création de collections (bases documentaires personnalisées)
* Configuration de modèles personnalisés (agents)
* Templates de prompts
* Développement de fonctions Python (utilisateurs avancés uniquement)

> Plus de documentation sur ces fonctionnalités directement sur [docs.openwebui.com](https://docs.openwebui.com)

{% hint style="success" %}
**Afin de bien comprendre comment utiliser un assistant conversationnel IA et en quoi il peut vous être utile, il est important de comprendre ce qu’est (et ce que n’est pas) une telle interface.**
{% endhint %}

<details>

<summary>Qu'est-ce qu'un Assistant Conversationnel IA ?</summary>

**Un assistant conversationnel IA est une interface conçue pour interagir avec les utilisateurs en langage naturel, en s’appuyant sur un LLM (modèle de langage).**\
Les **LLM** sont des modèles entraînés sur d’immenses corpus documentaires (≃ tout Internet) pour prévoir la suite d’une phrase ou d’un extrait de texte (le « prompt »).

Les assistants conversationnels gèrent l’envoi de l’historique complet d’une conversation, ainsi que d’autres éléments contextuels (documents ajoutés, préférences utilisateurs), afin d’assurer la cohérence de l’interaction et d’augmenter son utilité pour l’utilisateur.&#x20;

Ils traitent également le texte généré par le LLM pour en faciliter la compréhension (mise en forme du code, utilisation du gras ou de l’italique, censure de contenus sensibles, etc.).

Aujourd’hui, créer un LLM spécifique et adapté à nos cas d’usage est complexe et coûteux. C’est pourquoi le choix a été fait de s’appuyer sur des modèles open source ou propriétaires, à condition qu’ils respectent certains critères de souveraineté.

Si une partie de la performance de cette interface dépend des modèles sous-jacents sélectionnés, d’importantes améliorations sont également possibles en travaillant sur l’intégration des données externes, des données utilisateur ainsi que sur les options de configuration.

</details>

<details>

<summary>En quoi peut vous aider l'Assistant IA ? </summary>

**L'Assistant IA peut vous aider de multiples façons, selon vos besoins professionnels.**\
Voici les principaux bénéfices et usages de l'Assistant IA :

* **✍️ Rédaction et reformulation** : création, adaptation et amélioration de contenus textuels variés, notamment pour pallier le syndrome de la page blanche.
* **🧠 Prise de décision** : analyse de problèmes et propositions de solutions ou recommandations pour élargir votre champ des possibles.
* **🔎 Recherche et synthèse d’informations** : accès à une base de connaissances pour obtenir des informations précises et à jour, afin de travailler sereinement avec des sources fiables.
* **📄 Analyse et synthèse de documents** : lecture de vos documents de travail pour en extraire l’information plus rapidement.

</details>

<details>

<summary>Quelles bonnes pratiques appliquées pour optimiser l'usage de l'Assistant IA ? </summary>

L'Assistant IA comprend le langage naturel. Toutefois, pour en tirer le meilleur parti et obtenir des résultats optimaux, nous vous recommandons les pratiques suivantes :&#x20;

* **Formulez des requêtes précises et contextualisées** : soyez le plus précis possible dans vos questions afin d’obtenir des réponses pertinentes et adaptées à vos besoins. N’hésitez pas à donner du contexte, surtout si vous travaillez sur un projet particulier, et à indiquer le format de réponse souhaité, que ce soit une liste, un texte synthétique ou un tableau. Mentionnez également votre niveau de connaissance sur le sujet pour recevoir des explications appropriées.
* **Reformulez lorsque la réponse ne correspond pas à vos attentes** : afin de rendre vos échanges plus efficaces, il est conseillé d’avancer par étapes, surtout pour les sujets complexes. Commencez par une question générale, puis affinez progressivement avec des questions complémentaires. Si la réponse ne correspond pas à vos attentes, reformulez votre demande ou donnez un exemple concret pour illustrer ce que vous recherchez. N’hésitez pas à faire part de vos préférences à l’assistant pour qu’il puisse mieux s’adapter à vos besoins.
* **Gardez un regard critique quant aux réponses fournies**  :  il est important de garder un esprit critique lors de l’utilisation de l’assistant IA. Même s’il est performant, il peut arriver qu’il se trompe ou fournisse des informations inexactes. Prenez l’habitude de vérifier les données importantes auprès d’autres sources fiables et relisez toujours les textes générés avant de les utiliser. Si vous identifiez une erreur, signalez-la afin de contribuer à l’amélioration du service.
* **Considérez votre assistant comme un assistant qui amplifie vos capacités, et non comme un substitut à votre expertise ou à votre jugement** : gardez à l’esprit que la protection de vos données personnelles est primordiale. Evitez de partager des informations sensibles. Rappelez-vous que l’assistant est un outil destiné à vous aider dans vos tâches, mais les décisions finales vous appartiennent. Il peut parfois manquer de nuance sur certains sujets complexes ou culturels, c’est pourquoi il doit être vu comme un soutien qui complète vos compétences, et non comme un remplaçant.

</details>





<details>

<summary>Quels modèles sont proposés dans l'Assistant conversationnel ? </summary>

Les modèles actuellement proposés dans l'Assistant conversationnel s'appuie sur les modèles généralistes proposés par Albert-API dont l'apprentissage prend fin&#x20;

* au 4ème trimestre 2023 pour Albert-tâches simples&#x20;
* au 4ème trimestre 2024 pour Albert-tâches complexes &#x20;

[En savoir plus sur Albert-api](../../albert-api-linfrastructure-ia-souveraine-de-letat.md)&#x20;

</details>





