# 📊 Analyse de la performance d’un e-commerce avec Power BI

## Aperçu du projet

Ce projet présente une **analyse décisionnelle de la performance commerciale d’un e-commerce de mode** à partir du dataset **The Look E-commerce**.

L’objectif n’était pas seulement de “faire un dashboard”, mais de **répondre à une problématique métier concrète** :

> **Quelles catégories de produits faut-il prioriser pour améliorer la performance commerciale ?**

Pour y répondre, l’analyse croise plusieurs dimensions utiles à la décision :

- **chiffre d’affaires**
- **rentabilité**
- **croissance**
- **taux de retour**
- **niveau de concentration des ventes**

### 🎯 Ce que ce projet démontre

Ce projet met en avant ma capacité à :

- structurer une analyse à partir d’un **besoin métier flou**
- sélectionner des **KPI réellement utiles à la décision**
- construire un **dashboard lisible et orienté business**
- transformer des constats en **recommandations actionnables**

👉 **Livrable final : un dashboard Power BI conçu pour aider à prioriser les catégories et orienter les décisions commerciales / produit.**

---

## Contexte métier

Dans un contexte e-commerce, la performance ne se résume pas au chiffre d’affaires.

Une catégorie peut :
- bien vendre mais être moins rentable
- croître rapidement mais rester secondaire aujourd’hui
- générer du revenu tout en créant plus de retours
- être portée par quelques produits seulement, ce qui crée une dépendance

L’enjeu de cette analyse est donc de répondre à une question centrale :

> **où concentrer les efforts business pour soutenir une croissance plus saine et plus rentable ?**

---

## Utilisateurs cibles du dashboard

Ce dashboard peut être utile à différents profils métier :

- **Responsable e-commerce**
- **Category Manager**
- **Équipe commerciale**
- **Équipe produit / merchandising**

Il a été pensé comme un **outil d’aide à la décision**, pas comme une simple visualisation descriptive.

---

## Questions d’analyse

L’analyse a été construite autour de 5 questions principales :

1. **Quelles catégories génèrent le plus de chiffre d’affaires ?**
2. **Quelles catégories sont les plus rentables ?**
3. **Quelles catégories affichent la plus forte dynamique de croissance ?**
4. **Le taux de retour révèle-t-il un risque opérationnel particulier ?**
5. **La performance est-elle répartie de manière équilibrée ou concentrée sur quelques catégories / produits ?**

---

## KPI suivis

Les indicateurs principaux utilisés dans le dashboard sont :

- **Chiffre d’affaires**
- **Profit**
- **Taux de marge**
- **Prix moyen**
- **Volume vendu**
- **Chiffre d’affaires année N**
- **Chiffre d’affaires année N-1**
- **Taux de croissance du chiffre d’affaires**
- **Taux de retour par catégorie**

---

## Insights clés

### 1) La performance est concentrée sur un nombre limité de catégories
Le chiffre d’affaires est fortement porté par quelques catégories majeures, notamment **Outerwear & Coats** et **Jeans**.

**Implication :**  
la performance globale dépend fortement d’un petit nombre de catégories.

**Action possible :**  
sécuriser ces catégories clés tout en identifiant des relais de croissance plus équilibrés.

---

### 2) La croissance n’est pas toujours là où le volume est déjà le plus fort
Certaines catégories se distinguent par une **dynamique de croissance plus élevée**, même lorsqu’elles ne font pas partie des plus grosses contributrices actuelles.

**Implication :**  
les catégories à fort potentiel ne sont pas toujours les plus visibles dans une lecture purement “volume”.

**Action possible :**  
mieux prioriser les investissements commerciaux et marketing.

---

### 3) Le taux de retour reste globalement stable, mais apporte un angle qualité utile
Le **taux de retour varie peu entre les catégories**, avec des écarts limités.

**Implication :**  
il ne s’agit pas ici d’un signal d’alerte majeur, mais d’un indicateur complémentaire pertinent.

**Action possible :**  
surveiller les catégories légèrement au-dessus de la moyenne pour affiner les décisions produit / qualité / merchandising.

---

### 4) Certaines catégories combinent volume, rentabilité et potentiel
La lecture croisée du **chiffre d’affaires**, du **taux de marge** et de la **croissance** permet de distinguer plusieurs profils de catégories :
- catégories “pilier”
- catégories à optimiser
- catégories à fort potentiel
- catégories secondaires

**Implication :**  
toutes les catégories ne doivent pas être pilotées de la même manière.

**Action possible :**  
adapter les priorités selon le profil business de chaque catégorie.

---

### 5) La performance produit est elle aussi concentrée
Le zoom sur **Outerwear & Coats** montre que le chiffre d’affaires repose sur un **nombre limité de références**, avec une **longue traîne de produits à faible contribution**.

**Implication :**  
la performance catégorie peut masquer une forte concentration au niveau produit.

**Action possible :**  
travailler le mix produit, la profondeur de catalogue et la logique de mise en avant.

---

## Recommandations business

À partir de cette analyse, plusieurs pistes d’action peuvent être envisagées :

- **Prioriser les catégories combinant croissance et rentabilité**
- **Optimiser la rentabilité des catégories à fort volume**
- **Surveiller les catégories à faible contribution ou à retour légèrement plus élevé**
- **Ajuster les stratégies de prix et de coûts**
- **Développer le cross-selling autour des catégories performantes**
- **Soutenir commercialement les catégories en croissance**

> **Idée directrice :**
> une lecture croisée du volume, de la rentabilité, de la croissance et de la qualité opérationnelle permet de mieux orienter les décisions commerciales et produit.

---

## Dashboard

### Structure du dashboard

Le dashboard est organisé autour de 6 vues :

1. **Vue d’ensemble de la performance**
2. **Analyse de la performance par catégorie**
3. **Analyse de la croissance des ventes**
4. **Taux de retour par catégorie**
5. **Priorisation des catégories selon performance et rentabilité**
6. **Zoom produit : Outerwear & Coats**

### Exemples de visualisations utilisées

- KPI cards
- bar charts
- scatter plot
- comparaison année N vs N-1
- drill-down catégorie → produit


---

## Outils utilisés

- **Power BI**
- **Power Query**
- **DAX**

### Compétences mobilisées

- sélection et hiérarchisation de KPI
- modélisation simple pour l’analyse
- création de mesures DAX
- construction d’un dashboard décisionnel
- data storytelling
- traduction des résultats en recommandations métier

---

## Données utilisées

### Dataset
- **Source** : The Look E-commerce Dataset
- **Type** : dataset simulé e-commerce mode
- **Granularité** : commandes / produits / catégories

### Préparation des données
Le projet a été réalisé principalement dans **Power BI**, avec :
- import des tables utiles
- jointure complémentaire pour intégrer les informations de retour
- création de mesures DAX pour les indicateurs métier

---

## Limites du projet

Comme tout projet analytique, cette analyse comporte plusieurs limites :

- dataset simulé, et non données réelles d’entreprise
- absence d’informations marketing ou acquisition
- pas de segmentation client approfondie
- taux de retour utile mais peu discriminant dans ce cas précis
- analyse principalement centrée sur les catégories et produits

---

## Ce que j’aurais pu approfondir

Si ce projet était poursuivi dans un contexte plus complet, plusieurs extensions seraient intéressantes :

- analyse par **client / segment**
- analyse par **canal d’acquisition**
- analyse plus fine de la **récurrence d’achat**
- focus sur les **produits à faible rotation**
- enrichissement avec des dimensions marketing / opérationnelles

---

## Ce que ce projet montre

Au-delà de l’outil, ce projet montre surtout ma capacité à :

- partir d’un dataset brut
- structurer une réflexion métier
- sélectionner les bons indicateurs
- produire un livrable orienté décision

C’est exactement le type d’analyse que je souhaite développer dans un contexte professionnel :
**des projets utiles, lisibles et réellement exploitables côté business.**

---

## Fichiers du dépôt

- `dashboard/` → captures ou export du dashboard
- `README.md` → présentation du projet

---

## Contact

Si vous souhaitez échanger sur ce projet ou sur mon profil :

- [Linkedin](https://www.linkedin.com/in/amelie-n-lk/)
- [GitHub / portfolio](https://github.com/AmelielN)
