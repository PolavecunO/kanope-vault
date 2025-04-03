# 🌡️ Confort thermique & ECS – ULIO

## 🎯 Objectifs

- Fournir un confort thermique complet toute l’année sans climatisation active
- Assurer une autonomie énergétique complète hors réseau
- Minimiser les consommations grâce à une enveloppe thermique continue, des systèmes passifs et des équipements pilotés
- Centraliser les fonctions électriques et thermiques dans un système sobre, intelligent, maintenable

---

## 🧱 Enveloppe thermique

- Isolation intérieure biosourcée : **5 cm**
- Isolation extérieure continue : **10–12 cm** (fibre de bois ou liège, biosourcés)
- Suppression des ponts thermiques inter-container
- Bardage végétalisé avec structure bois
- Toiture ventilée (lame d’air + végétalisation possible)
- Cache solaire manuel bois/tissu sur menuiseries (coulissant ou rabattable)
- Confort été sans climatisation, renforcé par l’inertie thermique
- Option : ventilateur basse conso (1/logement, ~700 € total)
- Domotique thermique centralisée (pilotage température, stores, VMC, ECS…)

---

## 🔥 Chauffage

- Convecteurs 1 kW/logement
- Régulation domotique : 17–20 °C jour / 15 °C nuit
- Coupure automatique si logement vide / fenêtre ouverte / batterie < seuil
- Chauffage maintenu individuel pour flexibilité et sobriété

> Le système de chauffage repose sur **des convecteurs électriques basse puissance (1 kW)**, un par logement. Ils sont pilotés via la domotique locale, permettant une régulation fine et programmable. Cette approche a été choisie pour sa simplicité, sa robustesse, sa facilité de remplacement et son excellent ratio coût/efficacité dans un espace bien isolé. Chaque convecteur est intégré discrètement et reste accessible pour intervention ou remplacement.

---

## 💧 Eau chaude sanitaire (ECS)

- Ballon 50 L/logement
- Chauffe **à la demande uniquement**, jamais en maintien constant
- Réglage via domotique centralisée + capteurs
- Coupure automatique si batterie faible
- ECS non mutualisée pour éviter pertes réseau

> Chaque logement dispose d’un **ballon de 50 L**, placé dans une zone technique isolée. Ce volume est suffisant pour un usage régulé (1 douche/jour + usages cuisine). Le système est conçu pour ne fonctionner **que sur demande**, évitant les pertes par maintien de température. La domotique centralisée intègre des capteurs de température et de niveau d’eau chaude pour éviter les activations inutiles.

---

## 🌬️ Ventilation & régulation été

- VMC double flux centralisée, intégrée à chaque colonne technique (3 pour ULIO)
- Intégration passive d’un **système de déshumidification** (échangeur + capteur)
- Ventilation traversante naturelle : toutes les unités disposent de fenêtres sur façades opposées
- Cache solaire manuel ou motorisé (option) : piloté automatiquement ou à l’usage
- Surchauffe estivale maîtrisée par orientation, végétalisation et ventilation nocturne
- Climatisation totalement supprimée

> Une **VMC double flux** dessert les modules via **trois colonnes techniques verticales**, intégrées au bardage extérieur. Elle est dimensionnée pour permettre une ventilation continue à bas débit, avec accélération ponctuelle selon la détection d’humidité ou de CO₂. La récupération de chaleur permet de maintenir un excellent confort thermique. Les conduits sont accessibles pour entretien et intègrent un filtre anti-poussière facilement remplaçable.

---

## ⚡ Système électrique – Production, Stockage et Réseau

### 🔋 Production

| Source           | Capacité       | Rendement annuel |
|------------------|----------------|-------------------|
| PV souple        | 42 m²          | ~3 650 kWh        |
| Éolienne verticale | 1 unité        | ~1 000 kWh        |
| **Total**        | –              | **~4 650 kWh/an** |

- PV installé en toiture/passages entre containers
- Production priorisée sur usage thermique et réseau essentiel

### 🔋 Stockage

- Batterie LiFePO₄ 100 kWh utiles
- Capacité tampon suffisante pour 2 jours d’autonomie hivernale
- Domotique de lissage intégrée : priorités, coupures douces, délestage conditionnel

> La combinaison **photovoltaïque souple (42 m²)** + **éolienne verticale** assure une production constante, avec des pics solaires en été et une couverture hivernale par le vent. Le **stockage est assuré par une batterie LiFePO₄ de 100 kWh utiles**, placée dans un caisson isolé sécurisé. La répartition entre usage essentiel et conditionné est gérée automatiquement par la domotique.

---

## ⚡ Réseau et distribution électrique

- 3 colonnes électriques verticales extérieures (intégrées au bardage)
- Traverse technique horizontale jusqu’à chaque container
- Réseau mixte DC/AC optimisé
- Tableau électrique local + sous-compteur intelligent par container
- Coupe-circuits et sécurité sur chaque ligne
- Alimentation spécifique pour :
  - Chauffage
  - ECS
  - Éclairage
  - VMC + déshumidification
  - Appareils domotiques
  - Prises résiduelles (pilotées)

> Chaque module est alimenté via une **traverse technique principale** alimentée depuis le local central. Les câbles (AC ou DC selon circuits) passent par les colonnes verticales, protégées, ventilées et accessibles. Un **sous-tableau électrique local** permet de gérer les priorités, les pannes et les coupures. Tous les circuits sont protégés, différenciés, et étiquetés pour une maintenance facilitée.

---

## 🔌 Usages essentiels & consommation (pilotés)

| Poste                        | Estimation conso annuelle |
|------------------------------|----------------------------|
| Chauffage (x10 logements)    | ~800 kWh                   |
| ECS                          | ~690 kWh                   |
| VMC + ventilation            | ~100 kWh                   |
| Éclairage LED                | ~150 kWh                   |
| Domotique + régulations      | ~50 kWh                    |
| **Total (essentiels)**       | **~1 790 kWh/an** ✅

### 🧠 Domotique

> Le système domotique est développé sur une base open source (type Arduino + RPi), hébergé dans le **noyau technique** situé dans l’espace commun. Il pilote tous les flux : ECS, chauffage, éclairage, bornes VE, VMC, état des batteries, etc. Il intègre un mode dégradé manuel pour chaque logement. Les interfaces résidents sont **simples, tactiles ou mobiles**, avec des seuils par défaut modifiables dans un cadre prédéfini.


#### 💡 Éclairage

> L’éclairage intérieur repose sur des **LED basse consommation (5–7 W/unité)**, associées à des **détecteurs de présence** dans les espaces communs et les sanitaires. Les logements peuvent être équipés d’un interrupteur à variateur et d’un capteur de luminosité, afin de limiter l’usage en journée. L’éclairage extérieur est assuré par des **unités LED autonomes solaires** fixées sur des supports végétalisés (poteaux ou murs).

---

## ⚙️ Usages conditionnés au surplus (optionnels)

| Poste                       | Estimation max | Condition d’activation              |
|-----------------------------|----------------|-------------------------------------|
| Buanderie partagée          | ~300 kWh       | Surplus disponible + temps restreint |
| Cuisson commune             | ~300 kWh       | Pilotage utilisateur + surplus      |
| Recharge VE (1 borne double)| ~600–800 kWh   | Si batterie > 60 % et conso basse   |
| Éclairage extérieur         | ~100–150 kWh   | LED basse conso, détection présence |
| Local vélo / recharge vélos | ~100 kWh       | Système intégré                     |
| Espace cowork / FabLab      | ~200 kWh       | Sur plage horaire définie           |
| **Total potentiel**         | ~1 600–1 800 kWh| **Piloté dynamiquement** ✅

---

## 🔌 Mesures d’optimisation intégrées de base

| Mesure                              | Statut        |
|-------------------------------------|----------------|
| Isolation biosourcée standard       | ✅ intégrée    |
| Cache solaire manuel                | ✅ intégrée    |
| Domotique open source + locale      | ✅ intégrée    |
| VMC double flux + déshumidification | ✅ intégrée    |
| Suppression climatisation           | ✅ actée       |
| LED + détection de présence         | ✅ intégrée    |
| Multi-prises à coupure automatique  | ✅ intégrée    |
| Mutualisation buanderie/cuisine     | ✅ intégrée    |
| Recharge VE conditionnée            | ✅ intégrée    |
| Portail remplacé par plots          | ✅ intégrée    |

---

## 💰 Chiffrage résumé – version optimisée

| Élément                         | Coût estimé (auto) |
|----------------------------------|---------------------|
| Isolation thermique complète     | ~11 000 €           |
| Convecteurs + ECS (réemploi)     | ~1 800 €            |
| VMC + déshumidification          | ~3 000 €            |
| Domotique + capteurs             | ~500 €              |
| Cache solaire bois/tissu         | ~200–400 €          |
| PV souple (42 m²)                | ~2 100 €            |
| Éolienne verticale               | ~3 500 €            |
| Batterie LiFePO₄ (100 kWh)       | ~10 000 €           |
| Éclairage + gestion veilles      | ~200 €              |
| **Total système électrique + thermique** | **~32 000–34 000 €** ✅

---

## ✅ Conclusion

- ULIO repose sur un système **autonome, piloté, sobre et modulaire**
- Toutes les fonctions essentielles sont assurées sans dépendance au réseau
- Les optimisations sont **fiables**, basées sur des matériaux accessibles ou fabriqués localement
- Le système électrique centralise tous les usages avec **hiérarchisation intelligente**
- Une stratégie complète alliant **confort, robustesse et sobriété**

---

## ✅ **Optimisations possibles intégrables (réalistes et utiles)**

### 1. **Pré-câblage réseau modulaire**

- **Principe** : chaque container ULIO pourrait être précâblé en atelier avec des gaines et connecteurs standardisés pour le réseau électrique et domotique.
    
- **Avantages** :
    
    - Réduction du temps de pose et d’erreurs sur chantier
        
    - Réplication simplifiée sur les autres sites
        
    - Maintenance facilitée (connecteurs repérables)
        
- **Gain estimé** : ~15 % du coût d’installation du réseau interne
    

---

### 2. **Fixation extérieure des tableaux**

- **Principe** : placer les petits tableaux électriques à l’extérieur de l’unité (dans le bardage technique ventilé).
    
- **Avantages** :
    
    - Évite de percer l’isolation intérieure
        
    - Plus simple à maintenir (accès sans entrer dans le logement)
        
- **Limites** :
    
    - Doit être bien protégé de l’humidité et accessible uniquement via badge ou clé
        
- **Gain estimé** : ~5–10 % en temps de pose et en accessibilité
    

---

### 3. **Éclairage extérieur solaire autonome**

- **Principe** : lampes LED sur poteaux végétalisés ou murs, avec panneau solaire intégré
    
- **Avantages** :
    
    - Pas de câblage à tirer
        
    - Autonomie > 3 jours sans soleil
        
    - Design low tech + économique
        
- **Gain** :
    
    - ~100–150 kWh/an économisés sur le réseau
        
    - ~200 € en câblage et consommation
        

---

### 4. **Batteries d’occasion reconditionnées**

- **Principe** : récupération de batteries LiFePO₄ industrielles en fin de première vie (véhicules, sites de secours)
    
- **Avantages** :
    
    - Divise le coût par 1,5 à 2
        
    - Réduit la demande d’extraction de lithium neuf
        
- **Limites** :
    
    - Besoin d’une filière fiable
        
    - Cycle de vie souvent réduit (~5–7 ans)
        
- **Gain estimé** : –30 % sur le coût de stockage (jusqu’à 3 000 €)
    

---

### 5. **Pilotage thermique prédictif météo**

- **Principe** : relier la domotique aux données météo locales pour anticiper
    
- **Avantages** :
    
    - Pré-chauffage ou pré-refroidissement intelligent
        
    - Meilleur confort et moindre sollicitation des équipements
        
- **Techniquement simple** avec domotique open source + API météo
    
- **Gain estimé** : 5 à 10 % sur le chauffage et ECS
    

---

### 6. **Débit VMC modulé selon CO₂/humidité**

- **Principe** : capteurs dans chaque pièce ou container, ajustant le débit moteur
    
- **Avantages** :
    
    - Moins de bruit, moins d’énergie
        
    - Qualité d’air optimisée
        
- **Gain estimé** : ~30–50 kWh/an et meilleur confort
    

---

---

## ⚠️ **Faiblesses ou limites du système actuel (avec pistes de réponse)**

### 1. **Dépendance à l’éolienne**

- **Problème** : production incertaine → vent irrégulier en plaine ou été calme
    
- **Risques** :
    
    - Conso > prod sur plusieurs jours en hiver
        
- **Solutions** :
    
    - Surdimensionner légèrement le PV (ex : 48 m²)
        
    - Mutualisation d’une éolienne entre 2 ULIO
        
    - Batterie tampon suffisante (déjà 100 kWh)
        

---

### 2. **Stockage centralisé**

- **Problème** : un unique point de stockage → panne critique possible
    
- **Risques** :
    
    - Perte totale d’autonomie si batterie HS
        
- **Solutions** :
    
    - Découper le stockage (2 × 50 kWh par zone)
        
    - Ajouter un micro-stockage par container (1–2 kWh)
        
    - Prédire la panne grâce à la domotique et alerter
        

---

### 3. **Complexité domotique**

- **Problème** : usage avancé = risque d’incompréhension ou rejet
    
- **Solutions** :
    
    - Interface minimaliste (3–4 réglages par logement)
        
    - Mode manuel toujours disponible
        
    - Formation des habitants + mode “auto total”
        

---

### 4. **Sous-utilisation estivale de l’énergie**

- **Problème** : surplus important non valorisé en été
    
- **Pistes de valorisation** :
    
    - ECS stockée à 70 °C → ballon bien isolé
        
    - Serres urbaines ou plantations
        
    - Partage local (ULI voisin, espace public, recharge vélo)
        

---

### 5. **Maintenance des filtres VMC**

- **Problème** : filtre sale = perte d’efficacité et surconsommation
    
- **Solutions** :
    
    - Filtres standardisés, clipsables
        
    - Alerte domotique tous les X mois
        
    - Responsable maintenance résident (auto-gestion)

---

## ⚡ Valorisation du surplus énergétique

Le système ULIO produit un excédent énergétique annuel estimé à **~2 000 à 2 300 kWh**, principalement au printemps et en été. Ce surplus est piloté par la domotique afin de maximiser son utilité sans affecter l’autonomie générale.

### 🔁 Principes de gestion
- Activation automatique **par ordre de priorité**
- Fonctionnement conditionné à un **niveau de batterie > 60 %**
- Coupure automatique en cas de baisse ou de pic de consommation essentiel
- **Pas de pilotage individuel**, tous les usages sont mutualisés ou partagés

---

### 🧩 Légende – Utilité

| Code  | Signification                                 |
|-------|-----------------------------------------------|
| 🟢     | Utile mais secondaire ou ponctuel            |
| 🟢🟢   | Utile en continu ou apportant du confort      |
| 🟢🟢🟢 | Prioritaire, renforce la résilience ou la vie collective |

---

### ✅ Usages intégrés (par défaut)

| Usage                      | Conso estimée | Coût d’équipement | Facilité | Utilité |
|----------------------------|---------------|-------------------|----------|---------|
| **Laverie partagée**       | ~300 kWh/an   | ~1 200 €          | ✅ Facile | 🟢🟢🟢 |
| **Cuisson commune**        | ~250 kWh/an   | ~300 €            | ✅ Très facile | 🟢🟢🟢 |
| **ECS surchauffée (ballons)** | ~200 kWh/an | 0 € (pilotage inclus) | ✅ Automatique | 🟢🟢🟢 |
| **Local vélo (lumière + recharge)** | ~100 kWh/an | ~300 €  | ✅ Facile | 🟢🟢 |
| **Éclairage extérieur solaire autonome** | – | ~300 € | ✅ Très facile | 🟢🟢 |

---

### ⚠️ Usages secondaires (optionnels ou selon site)

| Usage                      | Conso max | Coût estimé | Facilité | Utilité |
|----------------------------|-----------|-------------|----------|---------|
| **Borne VE (1 double)**    | ~600–800 kWh | ~2 000 € | 🟡 Moyenne | 🟢🟢 |
| **Mini-serre ou serre légère** | ~150 kWh | ~500–700 € | 🟡 Moyenne | 🟢 |
| **Atelier léger / FabLab** | ~200 kWh | ~1 000 € | 🟡 Moyenne | 🟢🟢 |
| **Prises communautaires smart** | ~200–300 kWh | ~200 € | 🟢 Facile | 🟢 |
| **Stockage thermique passif** | ~100–200 kWh | ~300–600 € | ⚠️ Technique | 🟢 |

---

### 🧠 Recommandation de configuration

1. **Intégrer par défaut** : laverie, cuisson, ECS haute température, local vélo, éclairage autonome
2. **Ajouter selon contexte** : borne VE si zone périurbaine / sans transports
3. **Laisser la domotique piloter** la priorité des usages
4. Prévoir un ou deux **points d’usage opportunistes** en zone commune (prises smart, mini-atelier)

---

## 🧩 Points à considérer ensuite

|Thème|Pourquoi intéressant ?|Statut actuel|
|---|---|---|
|**Sécurité électrique et incendie**|Normes NFC15-100, coupe-circuit par fonction, détection fumée/poussière|à développer|
|**Protection contre surtensions / surtensions climatiques**|Parafoudre, protection pluie/vent sur PV, éolienne, armoire batteries|à détailler|
|**Logique de maintenance préventive**|Filtres VMC, batteries, capteurs domotiques|brièvement abordé|
|**Stockage thermique passif en été (serre, tampon eau)**|Pour valoriser l’excédent et lisser l’inertie thermique|optionnel|
|**Système de charge adaptative VE / vélo**|Algorithmes simples pour moduler charge = stabilité|à détailler si VE intégré|
|**Gestion des pics de consommation soudains (ex : hiver extrême)**|Appuis manuels, alertes, délestage programmé|en cours via domotique|
|**Évolutivité inter-ULI ou inter-BLOK**|Mutualisation entre voisins, liens électriques, couplage local|à développer si Kanopôle relancé|
|**Expérience utilisateur simplifiée**|Interface, notifications, tutoriels, profils d’usage|esquissé|
|**Normes & certifications**|RE2020, QAI, autonomie RE, labels d'urbanisme ou d'habitat|à documenter|

---

## 🔍 Petit bonus d’anticipation

- 🌡️ **Fiche sécurité / maintenance / normes** : ce qu’un installateur ou assureur attend
    
- 📱 **Fiche “interface habitant”** : usage simple et régulé du système par les résident·es
    
- 🔄 **Fiche “résilience avancée”** : quoi faire si panne, coupure, maintenance longue
    
- 🔌 **Fiche “réplicabilité énergétique”** : pour un ULIFO, ULINO, BLOK, ou futur Kanopôle