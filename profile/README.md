# Table des matières

1. [Remerciements](#1-remerciements)
2. [Introduction](#2-introduction)
3. [Notre solution](#3-notre-solution)
   - 3.1. [Email phishing](#31-email-phishing)
       - 3.1.1. [Implementation](#311-implementation)
   - 3.2. [URL phishing](#32-url-phishing)
       - 3.2.1. [Deep Neural Network](#321-deep-neural-network)
       - 3.2.2. [Viching](#322-viching)
4. [Conclusion](#4-conclusion)

---

## 1. Remerciements

Nous tenons à exprimer notre profonde gratitude à toutes les personnes qui ont contribué à la réalisation de ce projet. Tout d’abord, nous remercions l’ENSET de Mohammedia pour l’organisation de ce hackathon et pour nous avoir donné l’opportunité de travailler sur un sujet aussi pertinent et d’actualité. Nos remerciements vont également à tous les mentors et les membres du jury pour leurs conseils précieux et leurs évaluations constructives. Nous remercions également les membres de notre équipe pour leur dévouement, leur créativité et leur esprit d’innovation. Chacun a apporté ses compétences uniques et son enthousiasme, ce qui a été essentiel pour mener ce projet à bien. Enfin, nous exprimons notre gratitude aux développeurs et aux contributeurs des outils et des bibliothèques open-source que nous avons utilisés, ainsi qu’aux plateformes de données publiques qui ont été essentielles pour l’entraînement de notre modèle.

## 2. Introduction

Le hackathon ENSET 2024 s’est concentré sur l’utilisation de l’intelligence artificielle pour renforcer la cybersécurité, spécifiquement dans la détection des tentatives de phishing. Face à la montée des cyber-menaces, la nécessité de solutions proactives et efficaces est plus pressante que jamais. Notre projet propose une solution innovante pour identifier et neutraliser les attaques de phishing en temps réel, en utilisant des techniques avancées de machine learning.

## 3. Notre solution

### 3.1. Email phishing

Le phishing par email est l’une des méthodes les plus couramment utilisées par les cybercriminels pour tromper les utilisateurs et obtenir des informations sensibles telles que des identifiants de connexion, des informations financières ou des données personnelles. Cette technique consiste généralement à envoyer des emails frauduleux qui semblent provenir d’entités légitimes telles que des institutions financières, des services en ligne ou des entreprises renommées. Ces emails contiennent souvent des liens malveillants ou des pièces jointes infectées qui dirigent les utilisateurs vers des sites web falsifiés ou qui installent des logiciels malveillants sur leur système.

Le phishing par email peut prendre différentes formes, telles que :
- Phishing de hameçonnage (spear phishing) : Des emails ciblés sont envoyés à des individus ou à des organisations spécifiques, souvent en se faisant passer pour des collègues, des supérieurs hiérarchiques ou des contacts de confiance.
- Phishing de masse (mass phishing) : Des emails génériques sont envoyés à une large audience dans l’espoir d’obtenir des informations sensibles d’un grand nombre de personnes.
- Phishing d’urgence (urgent phishing) : Des emails prétendent présenter une urgence ou une situation critique, incitant ainsi les destinataires à agir rapidement sans réfléchir.

Pour contrer ces attaques, notre solution utilise des algorithmes d’intelligence artificielle pour analyser le contenu des emails entrants et identifier les signaux de phishing, tels que les liens suspects, les pièces jointes malveillantes et le texte trompeur. En détectant ces tentatives de phishing en temps réel, notre solution aide à protéger les utilisateurs contre les cyber-menaces et à garantir la sécurité de leurs informations personnelles et professionnelles.

#### 3.1.1. Implementation

Dans notre implémentation, nous avons utilisé la bibliothèque scikit-learn en Python pour entraîner notre modèle de détection de phishing. Nous avons exploré trois algorithmes de classification Naive Bayes : Gaussian Naive Bayes, Multinomial Naive Bayes et Bernoulli Naive Bayes. Ces algorithmes sont bien adaptés aux données de texte et ont montré des performances prometteuses dans la détection de phishing. Nous avons utilisé un ensemble de données provenant de Kaggle, comprenant des exemples d’e-mails légitimes et frauduleux, pour entraîner et évaluer nos modèles.

 
 
 
 