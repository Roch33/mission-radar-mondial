# MISSION RADAR MONDIAL - PAQUET DE TRANSFERT CHATGPT

- **mission_id** : MR-20260921-GLOBAL-001
- **created_at** : 2026-09-21T19:41:41
- **date du cycle** : 2026-09-21
- **statut** : TERMINEE
- **missions transmises** : 24
- **missions ≥ 50/100** : 24
- **missions solo** : 17
- **missions récurrentes** : 17
- **missions à contacter maintenant** : 7
- **niches détectées** : 7

> Aucune prise de contact n'a été effectuée. Ce paquet contient uniquement de l'information préparatoire : toute action externe exige une validation L5. Aucun secret, aucun identifiant, aucune donnée personnelle non publique.

> **Mode de transmission** : Ce paquet est destiné à être transmis à ChatGPT par dépôt de fichier ou copier-coller. Un accès HTTP anonyme depuis l'extérieur peut être refusé par la couche d'accès du bac à sable (jeton d'accès trafic) : dans ce cas, utiliser le fichier téléchargé ou le contenu collé, et non l'URL, pour alimenter la conversation.

> **Grille de référence des honoraires** : Références utilisées (indicatives) : mission courte de conseil indépendant senior 900–1 500 € par jour ; mandat récurrent de direction financière fractionnaire 1 500–6 000 € par mois selon 1–3 jours par mois ; mandat DAO/Web3 souvent sous forme de forfait voté en gouvernance (3–15 k€) ; missions de bailleurs selon grilles propres à chaque institution. Toute estimation doit être validée avant proposition.

## 1. INDEX COMPACT DES MISSIONS

Format de référence (une ligne par mission) :

```
OPP-03 | Moonwell | 82.2 | Audit cible du processus de modification des paramètres d'oracle et de collatéraux (double validation, revu... | OUI | 3-5 | Responsable risque / fondation Moonwell ; multisig de gouvernance
OPP-15 | Entités financières UE de taille intermédiaire et prestataires de services sur crypto-actifs (DORA art. 28-30) | 81.9 | Revue d'écart DORA troisième et quatrième partie : qualité du registre des accords TIC, examen des contrats... | OUI | 5-10 | Directeur conformité, DAF, responsable des risques, comité d'audit
OPP-01 | Kelp DAO | 81.1 | Revue post-incident, 8 jours maximum, de la couche contrôle interne: inventaire des modules et autorisation... | OUI | 5-8 | Fondation/core team Kelp DAO, responsable sécurité ou opérations, comité multisig de trésorerie
OPP-07 | Population cible : 24 DAO détenant des Safe avec modules actifs (trésorerie > 20 M$) | 80.5 | Offre productisée : « Inventaire et révocation des modules Safe » - recensement des modules et automatisati... | OUI | 2-4 par organisation | Multisig signataires, comité de trésorerie, responsable sécurité, cercles de délégués
OPP-02 | Nostra Finance | 80.0 | Refonte du dispositif de contrôle des paramètres de marché et des oracles : politique d'activation des coll... | OUI | 4-6 | équipe fondatrice / responsable risque du protocole ; conseil de gouvernance
OPP-14 | Directions financières de sociétés détenant de la trésorerie crypto (sociétés de trésorerie d'actifs numériques, fintechs, e-money) | 77.4 | Revue de préparation à l'audit de la trésorerie crypto : chaîne d'approbation, séparation des rôles, invent... | OUI | 5-8 | DAF, contrôleur de gestion, comité d'audit, expert-comptable
OPP-16 | Cabinets d'expertise comptable et de paie de taille intermédiaire (Royaume-Uni, France, Benelux) | 77.0 | Revue des contrôles anti-fraude du cabinet et de ses clients : contrôle des changements de coordonnées banc... | OUI | 3-5 | Associé gérant, responsable qualité et risque, responsable informatique
OPP-10 | DAO de taille intermédiaire (trésorerie 10-50 M$) sans fonction finance structurée | 76.7 | Pack mensuel de reporting et de contrôle pour trésorerie DAO : états de trésorerie mensuels, réconciliation... | OUI | 5 jours de mise en place puis 0,5-1 jour par mois | trésorier, multisig signataires, cercle de délégués, fondation
OPP-13 | Fintech / edtech (recrutement publié, mandat d'approche par cabinet) | 73.2 | Direction financière fractionnaire : pilotage de la trésorerie, prévisionnel, reporting investisseurs, mise... | OUI | récurrent : 6-8 heures par semaine | Fondateur/CEO, CFO, responsable recrutement du cabinet mandataire
OPP-09 | DAO utilisant les modules de gouvernance Zodiac / Reality (SafeSnap) | 71.8 | Runbook d'exécution de gouvernance : inventaire des chemins d'exécution (votes, modules, automatisations), ... | OUI | 4-6 | comité de sécurité de la DAO, signataires, administrateurs du module
OPP-06 | Unlock DAO | 70.2 | Revue indépendante du dispositif de quorum et de délégation : analyse des conséquences (sécurité, légitimit... | OUI | 5-8 | Stewards, contributeurs actifs, délégués (leaderboard de participation)
OPP-19 | Fintechs, prestataires de paiement et assureurs de taille intermédiaire | 70.2 | Co-sourcing de la fonction d'audit interne : plan d'audit fondé sur les risques, 2 à 4 missions par an (con... | OUI (1 à 2 missions en parallèle maximum) | récurrent : 2 à 4 missions de 3-5 jours par an | Président du comité d'audit, DAF, directeur conformité
OPP-12 | Venues de prêt et protocoles acceptant des actifs pontés (Euler, Silo, Fluid, Morpho, Venus) | 68.5 | Registre des dépendances d'actifs admis : fiche de dépendance par actif (pont, vérificateur, oracle, émissi... | PARTIEL | 5-8 | Fournisseur de risque, comité de marché, équipe protocole
OPP-05 | Arbitrum DAO (Treasury Management Committee) | 67.8 | Conception d'un cadre d'assurance et de reporting pour mandats de gestion de trésorerie DAO : indicateurs d... | PARTIEL | 7-10 | Treasury Management Committee, Entropy Advisors, délégués majeurs
OPP-08 | Aave (et marchés de prêt acceptant des LST pontés) | 67.6 | Revue du cadre d'admission des collatéraux : cartographie des dépendances (pont, vérificateur, oracle, émis... | PARTIEL | 6-10 | Risk Council / service providers de risque du protocole, équipe croissance
OPP-04 | Drift Protocol | 67.1 | Cartographie des autorités administratives et de leurs modes d'approbation (qui peut faire quoi, avec quel ... | PARTIEL | 8-12 | Security Council, fondation Drift, responsable sécurité
OPP-17 | Entreprises de taille moyenne à forte intensité de paiements (immobilier, construction, santé, industrie) | 65.6 | Revue du processus de paiement et anti-usurpation : vérification des changements de coordonnées, autorisati... | OUI | 4-6 | DAF, responsable comptabilité, directeur des systèmes d'information
OPP-22 | UNFPA - roster de consultants finance (branche finance du siège) | 65.4 | Consultances courtes : opérations financières IPSAS, reporting bailleurs, comptabilité et contrôle des stoc... | OUI | Affectations courtes répétées | Chef d'unite de la branche finance, chef comptes, chef de la branche finance
OPP-18 | Prestataires de services sur crypto-actifs et fintechs en cours d'agrément (MiCA, DORA) | 63.8 | Appui conformité et contrôle interne à temps partagé : cartographie des risques, procédures, plan de contrô... | OUI | récurrent : 1-3 jours par mois | Dirigeant, responsable conformité, conseil d'administration
OPP-21 | Banque africaine de développement (BAD) - consultant individuel via DACON et avis à manifestation d'intérêt | 62.5 | Missions d'assistance technique et de contrôle financier : appui au suivi financier de projets, revue des d... | OUI | Missions de 6 à 12 semaines | Départements sectoriels de la BAD, comité de recrutement et de supervision des consultants, unités d'exécution des projets emprunteurs
OPP-24 | Organisations non gouvernementales mettant en œuvre des programmes financés par l'Union européenne et des bailleurs bilatéraux | 61.8 | Diagnostic flash du dispositif de contrôle interne d'un projet finance : cartographie des risques de non-co... | OUI | 5-8 | Directeur pays, responsable financier ou administratif, responsable des programmes
OPP-11 | DAO en cours de structuration juridique (DUNA Wyoming, Harmony Framework) | 60.2 | Mise en place de la fonction finance et gouvernance post-structuration : plan de comptes, calendrier de rep... | PARTIEL | 6-10 | Fondation, conseil d'administration de l'entité, conseil juridique
OPP-20 | CTR / C2D2 (projets financés par l'AFD en République démocratique du Congo) | 59.1 | Audit financier et comptable pluriannuel des projets. Réserve : le dossier exige un cabinet d'audit et d'ex... | NON | Mission pluriannuelle (3 exercices) | Cellule de passation des marchés du CTR, coordination des projets
OPP-23 | UN Women - consultance finance et programme à distance (Kenya, financement Union européenne) | 57.4 | Appui financier de programme : revue de conformité des transactions, suivi budgétaire, appui au reporting, ... | OUI | 6 mois à temps plein (modèle) | spécialiste de la gestion des programmes (superviseur), coordinateur régional
```

| ID | Organisation | Score | Mission | Solo | Durée | Contact cible |
|---|---|---|---|---|---|---|
| OPP-03 | Moonwell | 82.2 | Audit cible du processus de modification des paramètres d'oracle et de collatéraux (double validation, revue croisée, tests de non-régression sur les feeds, plafonds dynamiques, alertes) et mise en place d'un registre des changements. | OUI | 3-5 | Responsable risque / fondation Moonwell ; multisig de gouvernance |
| OPP-15 | Entités financières UE de taille intermédiaire et prestataires de services sur crypto-actifs (DORA art. 28-30) | 81.9 | Revue d'écart DORA troisième et quatrième partie : qualité du registre des accords TIC, examen des contrats critiques, cartographie des chaînes de sous-traitance, analyse de concentration, plans de sortie, gouvernance et reporting annuel. | OUI | 5-10 | Directeur conformité, DAF, responsable des risques, comité d'audit |
| OPP-01 | Kelp DAO | 81.1 | Revue post-incident, 8 jours maximum, de la couche contrôle interne: inventaire des modules et autorisations actives, politique de révocation, règle de confirmation multi-signataires pour l'installation de modules, revue du modèle de confiance du pont (vérificateur unique) et plan de remédiation priorise. | OUI | 5-8 | Fondation/core team Kelp DAO, responsable sécurité ou opérations, comité multisig de trésorerie |
| OPP-07 | Population cible : 24 DAO détenant des Safe avec modules actifs (trésorerie > 20 M$) | 80.5 | Offre productisée : « Inventaire et révocation des modules Safe » - recensement des modules et automatisations attachés aux Safe de trésorerie, analyse du périmètre d'autorisation de chacun, identification des modules dormants ou non revus, recommandations de révocation et politique d'installation (qui approuve, quel délai, quelle revue). | OUI | 2-4 par organisation | Multisig signataires, comité de trésorerie, responsable sécurité, cercles de délégués |
| OPP-02 | Nostra Finance | 80.0 | Refonte du dispositif de contrôle des paramètres de marché et des oracles : politique d'activation des collatéraux, plafonds, oracle de repli, seuils d'alerte, revue croisée avant tout changement de paramètre, journal des changements, tests de liquidation. | OUI | 4-6 | équipe fondatrice / responsable risque du protocole ; conseil de gouvernance |
| OPP-14 | Directions financières de sociétés détenant de la trésorerie crypto (sociétés de trésorerie d'actifs numériques, fintechs, e-money) | 77.4 | Revue de préparation à l'audit de la trésorerie crypto : chaîne d'approbation, séparation des rôles, inventaire des portefeuilles et seuils, rapprochement des écritures, preuves horodatées, dossier de justification pour l'auditeur et le conseil d'administration. | OUI | 5-8 | DAF, contrôleur de gestion, comité d'audit, expert-comptable |
| OPP-16 | Cabinets d'expertise comptable et de paie de taille intermédiaire (Royaume-Uni, France, Benelux) | 77.0 | Revue des contrôles anti-fraude du cabinet et de ses clients : contrôle des changements de coordonnées bancaires, vérification par canal indépendant, double approbation, surveillance des boites mail, procédure d'incident et de déclaration, formation des équipes. | OUI | 3-5 | Associé gérant, responsable qualité et risque, responsable informatique |
| OPP-10 | DAO de taille intermédiaire (trésorerie 10-50 M$) sans fonction finance structurée | 76.7 | Pack mensuel de reporting et de contrôle pour trésorerie DAO : états de trésorerie mensuels, réconciliation on-chain, journal des décisions de gouvernance rattachees aux mouvements, indicateurs de risque (concentration, liquidité, runway en stablecoins), seuils d'approbation par taille de transaction. | OUI | 5 jours de mise en place puis 0,5-1 jour par mois | trésorier, multisig signataires, cercle de délégués, fondation |
| OPP-13 | Fintech / edtech (recrutement publié, mandat d'approche par cabinet) | 73.2 | Direction financière fractionnaire : pilotage de la trésorerie, prévisionnel, reporting investisseurs, mise en place de contrôles, due diligence finance. | OUI | récurrent : 6-8 heures par semaine | Fondateur/CEO, CFO, responsable recrutement du cabinet mandataire |
| OPP-09 | DAO utilisant les modules de gouvernance Zodiac / Reality (SafeSnap) | 71.8 | Runbook d'exécution de gouvernance : inventaire des chemins d'exécution (votes, modules, automatisations), qui doit surveiller quoi et quand, fenêtres de veto, astreinte et escalade, tests trimestriels d'un scénario d'attaque, journal des exécutions. | OUI | 4-6 | comité de sécurité de la DAO, signataires, administrateurs du module |
| OPP-06 | Unlock DAO | 70.2 | Revue indépendante du dispositif de quorum et de délégation : analyse des conséquences (sécurité, légitimité, risque de capture), cadre de délégation depuis la trésorerie, garde-fous d'exécution, politique de quorum cible et mécanisme de délégation dynamique. | OUI | 5-8 | Stewards, contributeurs actifs, délégués (leaderboard de participation) |
| OPP-19 | Fintechs, prestataires de paiement et assureurs de taille intermédiaire | 70.2 | Co-sourcing de la fonction d'audit interne : plan d'audit fondé sur les risques, 2 à 4 missions par an (contrôles de trésorerie, processus de paiement, sous-traitance, accès), suivi des recommandations. | OUI (1 à 2 missions en parallèle maximum) | récurrent : 2 à 4 missions de 3-5 jours par an | Président du comité d'audit, DAF, directeur conformité |
| OPP-12 | Venues de prêt et protocoles acceptant des actifs pontés (Euler, Silo, Fluid, Morpho, Venus) | 68.5 | Registre des dépendances d'actifs admis : fiche de dépendance par actif (pont, vérificateur, oracle, émissions, sous-traitants), analyse de concentration par fournisseur, seuils d'alerte et plan de sortie documenté. | PARTIEL | 5-8 | Fournisseur de risque, comité de marché, équipe protocole |
| OPP-05 | Arbitrum DAO (Treasury Management Committee) | 67.8 | Conception d'un cadre d'assurance et de reporting pour mandats de gestion de trésorerie DAO : indicateurs de conformité au mandat, seuils d'alerte, revue trimestrielle indépendante, format de reporting aux délégués. | PARTIEL | 7-10 | Treasury Management Committee, Entropy Advisors, délégués majeurs |
| OPP-08 | Aave (et marchés de prêt acceptant des LST pontés) | 67.6 | Revue du cadre d'admission des collatéraux : cartographie des dépendances (pont, vérificateur, oracle, émission), analyse de concentration, scénario de défaillance en cascade, limites d'exposition et plan de réduction progressive. | PARTIEL | 6-10 | Risk Council / service providers de risque du protocole, équipe croissance |
| OPP-04 | Drift Protocol | 67.1 | Cartographie des autorités administratives et de leurs modes d'approbation (qui peut faire quoi, avec quel délai), revue des autorisations pré-signées et des nonces durables, politique de clé, procédure de revue des collatéraux, plan de sortie de la dépendance à une entité de sécurité unique. | PARTIEL | 8-12 | Security Council, fondation Drift, responsable sécurité |
| OPP-17 | Entreprises de taille moyenne à forte intensité de paiements (immobilier, construction, santé, industrie) | 65.6 | Revue du processus de paiement et anti-usurpation : vérification des changements de coordonnées, autorisations, seuils, gestion des fournisseurs, détection des règles de transfert automatique, plan de reaction et récupération des fonds, formation des équipes comptables. | OUI | 4-6 | DAF, responsable comptabilité, directeur des systèmes d'information |
| OPP-22 | UNFPA - roster de consultants finance (branche finance du siège) | 65.4 | Consultances courtes : opérations financières IPSAS, reporting bailleurs, comptabilité et contrôle des stocks, transferts de fonds et réconciliation des avances aux partenaires de mise en œuvre. | OUI | Affectations courtes répétées | Chef d'unite de la branche finance, chef comptes, chef de la branche finance |
| OPP-18 | Prestataires de services sur crypto-actifs et fintechs en cours d'agrément (MiCA, DORA) | 63.8 | Appui conformité et contrôle interne à temps partagé : cartographie des risques, procédures, plan de contrôle annuel, préparation des revues du superviseur. | OUI | récurrent : 1-3 jours par mois | Dirigeant, responsable conformité, conseil d'administration |
| OPP-21 | Banque africaine de développement (BAD) - consultant individuel via DACON et avis à manifestation d'intérêt | 62.5 | Missions d'assistance technique et de contrôle financier : appui au suivi financier de projets, revue des dispositifs de contrôle interne, rapports financiers, appui à la mise en place de procédures. | OUI | Missions de 6 à 12 semaines | Départements sectoriels de la BAD, comité de recrutement et de supervision des consultants, unités d'exécution des projets emprunteurs |
| OPP-24 | Organisations non gouvernementales mettant en œuvre des programmes financés par l'Union européenne et des bailleurs bilatéraux | 61.8 | Diagnostic flash du dispositif de contrôle interne d'un projet finance : cartographie des risques de non-conformite, revue des pièces justificatives, procédés d'engagement, suivi des recom- mandations d'audit, plan d'action à 90 jours. | OUI | 5-8 | Directeur pays, responsable financier ou administratif, responsable des programmes |
| OPP-11 | DAO en cours de structuration juridique (DUNA Wyoming, Harmony Framework) | 60.2 | Mise en place de la fonction finance et gouvernance post-structuration : plan de comptes, calendrier de reporting, contrôles minimaux, articulation entre entité juridique et exécution on-chain. | PARTIEL | 6-10 | Fondation, conseil d'administration de l'entité, conseil juridique |
| OPP-20 | CTR / C2D2 (projets financés par l'AFD en République démocratique du Congo) | 59.1 | Audit financier et comptable pluriannuel des projets. Réserve : le dossier exige un cabinet d'audit et d'expertise comptable de réputation internationale, membre de l'ordre national congolais, dix ans d'expérience, références supérieures ou égales à 200 000 EUR par an et expérience en RDC ou en Afrique centrale. | NON | Mission pluriannuelle (3 exercices) | Cellule de passation des marchés du CTR, coordination des projets |
| OPP-23 | UN Women - consultance finance et programme à distance (Kenya, financement Union européenne) | 57.4 | Appui financier de programme : revue de conformité des transactions, suivi budgétaire, appui au reporting, suivi des recommandations d'audit. | OUI | 6 mois à temps plein (modèle) | spécialiste de la gestion des programmes (superviseur), coordinateur régional |

## 2. FICHES DÉTAILLÉES DES MISSIONS (toutes les opportunités ≥ 50/100)

### OPP-03 — Moonwell

- **ID de l'opportunité** : OPP-03
- **Organisation / projet** : Moonwell
- **Pays ou zone** : Base / Moonbeam (mondial) - inconnu
- **Secteur** : DeFi - lending
- **Score opportunité** : 82.2/100
- **Score DARKINT** : 91.0/100
- **Priorité** : PRIORITÉ IMMÉDIATE
- **Problème détecté** : Deuxième défaillance oracle en 6 mois. 15/02/2026 : erreur de configuration (taux cbETH/ETH non multiplié par ETH/USD) ayant entraîné 1,8 M$ de bad debt et des liquidations à un prix plusieurs milliers de fois trop bas. 27/08/2026 : manipulation du prix MAMO (~9 M$). Cause récurrente : contrôle des changements de configuration insuffisant, pas de revue croisée.
- **Éléments factuels ayant conduit à identifier le besoin** :
  - 15/02/2026 : erreur de configuration d'oracle (taux cbETH/ETH non multiplié par ETH/USD), entraînant environ 1,8 M$ de bad debt et des liquidations à un prix plusieurs milliers de fois trop bas (source S04, 19/05/2026).
  - 27/08/2026 : manipulation du prix MAMO provoquant environ 9 M$ de pertes sur Base (source S05, 05/09/2026).
  - Dans les deux cas, la faille se situe dans la configuration et le processus de changement, non dans le code des contrats (source S04, source S05).
  - Même cause observée chez Silo (03/04/2026, 392 k$) et Venus (3,7 M$) sur la même période (source S04).
- **Niveau de confirmation de la source** : CONFIRMÉ (rapports publics, post-mortem de l'équipe)
- **Source(s) avec URL** :
  - S04 — Biggest DeFi Hacks and Exploits of 2026: $1 Billion+ Lost and Counting (ccn.com, 2026-05-19) : https://www.ccn.com/education/crypto/defi-hacks-exploits-causes-crypto-stolen-2026/
  - S05 — DeFi has lost $1.3 billion to hacks in 2026 and the same attack keeps working (cryptonews.net, 2026-09-05) : https://cryptonews.net/news/security/33396919/
- **Date des sources** : 2026-08-27
- **Mission précise que Roch pourrait proposer** : Audit cible du processus de modification des paramètres d'oracle et de collatéraux (double validation, revue croisée, tests de non-régression sur les feeds, plafonds dynamiques, alertes) et mise en place d'un registre des changements.
- **Livrable proposé** : Rapport d'audit cible (8-12 pages) + registre des changements + matrice de validation des paramètres + 5 contrôles clés opérationnels.
- **Intervention solo** : OUI
- **Durée estimée** : 3-5
- **Charge estimée (heures / jours)** : 20–35 heures (3–5 jours)
- **Travail à distance** : OUI
- **Niveau de difficulté** : Faible à moyenne (contrôles de processus et configuration)
- **Compétences nécessaires** : Contrôle interne, Audit ciblé de processus, Configuration d'oracles et de collatéraux, Tests de non-régression, Rédaction d'une matrice de validation
- **Besoin éventuel d'un partenaire** : NON
- **Personne ou fonction à contacter** : Responsable risque / fondation Moonwell ; multisig de gouvernance
- **Nom du contact publiquement identifié** : Fonction : responsable risque/fondation et multisig de gouvernance. Nom non publié dans ce rapport.
- **Canal de contact public disponible** : Forum de gouvernance du protocole ; Canaux officiels (X et Discord)
- **Raison pour laquelle cette organisation est une cible** : Deux incidents sur le même processus en six mois : le coût des pertes dépasse largement le coût d'un contrôle trimestriel, argument économique immédiat et vérifiable.
- **Besoin** : EXPLICITEMENT EXPRIMÉ (deux incidents reconnus et documentés publiquement en six mois)
- **Potentiel** : récurrent : revue trimestrielle de la configuration oracle et des changements
- **Ordre de grandeur d'honoraires envisageable** : Forfait 4–7 k€ pour 3–5 jours — estimation indicative ; prestation récurrente trimestrielle envisageable
- **Prochaine action recommandée** : Envoyer une note courte chiffrant le coût des deux incidents face au coût d'un contrôle trimestriel. Validation L5 avant envoi.
- **Statut commercial actuel** : NON CONTACTÉ — validation L5 requise

### OPP-15 — Entités financières UE de taille intermédiaire et prestataires de services sur crypto-actifs (DORA art. 28-30)

- **ID de l'opportunité** : OPP-15
- **Organisation / projet** : Entités financières UE de taille intermédiaire et prestataires de services sur crypto-actifs (DORA art. 28-30)
- **Pays ou zone** : Union européenne - France, UE
- **Secteur** : Finance réglementée - risque tiers TIC
- **Score opportunité** : 81.9/100
- **Score DARKINT** : 86.0/100
- **Priorité** : PRIORITÉ IMMÉDIATE
- **Problème détecté** : DORA s'applique depuis le 17/01/2025 : registre des accords contractuels TIC, évaluation avant conclusion, analyse de concentration, cartographie des sous-traitants en chaîne (4e partie), clauses minimales et étendues, plan de sortie documenté, reporting annuel. Les entités de taille intermédiaire (sociétés de gestion, prestataires de paiement, e-money, prestataires crypto) ont souvent un dispositif incomplet et la responsabilité reste entièrement la leur, y compris quand le prestataire est conforme.
- **Éléments factuels ayant conduit à identifier le besoin** :
  - Le règlement européen sur la résilience opérationnelle s'applique depuis le 17 janvier 2025 : registre des accords TIC, évaluation avant conclusion, analyse de concentration, clauses minimales et étendues (sources S16 et S17).
  - Les obligations descendent jusqu'aux sous-traitants de rang 2 et 3 dès lors qu'ils soutiennent une fonction critique (sources S16 et S17).
  - La responsabilité reste entièrement celle de l'entité financière, y compris lorsque le prestataire est conforme (source S17).
  - Les entités de taille intermédiaire disposent rarement d'une fonction conformité à temps plein ; le reporting annuel impose une mise à jour continue du registre (source S17).
- **Niveau de confirmation de la source** : CONFIRMÉ (obligation réglementaire) - besoin résolu ou non selon l'entité = probable
- **Source(s) avec URL** :
  - S16 — How Does DORA Address Third-Party ICT Risk? (Art. 28-30, registre d'informations, sous-traitance en chaîne, concentration) (thingsrecon.com, 2026-09-02) : https://www.thingsrecon.com/blog/how-does-dora-address-third-party-ict-risk
  - S17 — DORA Third-Party ICT Risk: Articles 28-30 Guide for 2026 (obligations, reporting annuel, plan de sortie) (cyadviso.com, 2026-06-01) : https://www.cyadviso.com/dora-third-party-ict-risk
- **Date des sources** : 2026-09-02
- **Mission précise que Roch pourrait proposer** : Revue d'écart DORA troisième et quatrième partie : qualité du registre des accords TIC, examen des contrats critiques, cartographie des chaînes de sous-traitance, analyse de concentration, plans de sortie, gouvernance et reporting annuel.
- **Livrable proposé** : Registre des informations fiabilisé + rapport d'écart + clauses contractuelles manquantes + plan de sortie type + dossier de gouvernance.
- **Intervention solo** : OUI
- **Durée estimée** : 5-10
- **Charge estimée (heures / jours)** : 40–75 heures (5–10 jours)
- **Travail à distance** : OUI
- **Niveau de difficulté** : Moyenne
- **Compétences nécessaires** : Réglementation européenne sur la résilience numérique, Gestion des tiers et des contrats, Registre des accords et cartographie des sous-traitants, Analyse de concentration, Rédaction de plans de sortie
- **Besoin éventuel d'un partenaire** : NON
- **Personne ou fonction à contacter** : Directeur conformité, DAF, responsable des risques, comité d'audit
- **Nom du contact publiquement identifié** : Fonction : directeur conformité, directeur administratif et financier, responsable des risques, comité d'audit. Nom non publié dans ce rapport.
- **Canal de contact public disponible** : Réseaux professionnels conformité et risques ; Associations professionnelles de la place ; Introductions par cabinets
- **Raison pour laquelle cette organisation est une cible** : Obligation légale avec échéance annuelle, budget existant, et un livrable parfaitement standardisable (registre + écarts + clauses manquantes). C'est la niche la plus industrialisable du registre, en français comme en anglais.
- **Besoin** : OBSERVÉ (obligation réglementaire opposable, sans expression publique de besoin par les entités concernées)
- **Potentiel** : récurrent (mise à jour du registre, reporting annuel, revue des contrats)
- **Ordre de grandeur d'honoraires envisageable** : Forfait 8–14 k€ pour 5–10 jours — estimation indicative ; mise à jour annuelle du registre récurrente (3–5 k€)
- **Prochaine action recommandée** : Préparer une offre cadrée « registre des accords TIC et chaînes de sous-traitance » de 5 jours, en français et en anglais. Validation L5 avant démarchage.
- **Statut commercial actuel** : NON CONTACTÉ — validation L5 requise avant démarche

### OPP-01 — Kelp DAO

- **ID de l'opportunité** : OPP-01
- **Organisation / projet** : Kelp DAO
- **Pays ou zone** : Mondial / Web3 (non localise) - inconnu (entité DAO)
- **Secteur** : DeFi - restaking / LST (rsETH)
- **Score opportunité** : 81.1/100
- **Score DARKINT** : 94.5/100
- **Priorité** : PRIORITÉ IMMÉDIATE
- **Problème détecté** : Exploitation le 15/09/2026 d'un module personnalisé autorisé par l'utilisateur sur un Safe (poste rsETH/aEthrsETH, hook Uniswap v4) après le drain de 292 M$ du bridge rsETH en avril 2026. Le composant tiers autorisé élargit la frontière de confiance du wallet ; aucun inventaire ni révocation systématique des modules n'existe.
- **Éléments factuels ayant conduit à identifier le besoin** :
  - Quatre sociétés de sécurité (Blockaid, BlockSec, SlowMist, AstraSec) attribuent la perte de 7,8 M$ à un module personnalisé autorisé par l'utilisateur sur un portefeuille Safe adossé à un poste rsETH/aEthrsETH (source S01, 19/09/2026).
  - Le pont rsETH avait déjà été drainé de 292 M$ en avril 2026, avec environ 196 M$ de bad debt concentré sur une seule paire (source S02, 22/04/2026).
  - Kelp DAO déclare que ses contrats principaux et le rsETH ne sont pas atteints et annonce un post-mortem détaillé ; la question de la maîtrise des autorisations données à des composants tiers reste ouverte (source S03, 18/09/2026).
  - Antécédent de même nature : SuDAO (2022), où un module Safe avait permis de vider la trésorerie sans signature des propriétaires (source S33).
- **Niveau de confirmation de la source** : CONFIRMÉ (faits publics, attribués par 4 sociétés de sécurité)
- **Source(s) avec URL** :
  - S01 — MEV Bot Yoink Beats Hacker to $7.8M rsETH Haul (shattered.io, 2026-09-19) : https://shattered.io/yoink-mev-bot-beats-hacker-rseth-2026/
  - S02 — DeFi's $606M April: Kelp DAO bridge drain, Drift Protocol oracle+key compromise, Resolv AWS heist (bex.co, 2026-04-22) : https://bex.co/blog/2026/04/22/april-606m-hack-spree-defi-protocol-upgrade-vulnerabilities-kelp-drift-resolv
- **Date des sources** : 2026-09-15
- **Mission précise que Roch pourrait proposer** : Revue post-incident, 8 jours maximum, de la couche contrôle interne: inventaire des modules et autorisations actives, politique de révocation, règle de confirmation multi-signataires pour l'installation de modules, revue du modèle de confiance du pont (vérificateur unique) et plan de remédiation priorise.
- **Livrable proposé** : Rapport de revue de contrôle interne (15-25 pages) + inventaire des autorisations + politique d'installation/révocation des modules + plan de remédiation 30/60/90 jours + note de synthèse pour la gouvernance.
- **Intervention solo** : OUI
- **Durée estimée** : 5-8
- **Charge estimée (heures / jours)** : 40–60 heures (5–8 jours)
- **Travail à distance** : OUI
- **Niveau de difficulté** : Moyenne (gouvernance et contrôles ; vérification technique du code du module en appui ponctuel)
- **Compétences nécessaires** : Contrôle interne, Gouvernance des portefeuilles multi-signatures, Revue des modules et autorisations, Rédaction de politique de signature, Compréhension DeFi et ponts
- **Besoin éventuel d'un partenaire** : NON (recommande sans obligation : expert Solidity 1-2 jours pour revue du module) (Audit de code Solidity/Uniswap v4)
- **Personne ou fonction à contacter** : Fondation/core team Kelp DAO, responsable sécurité ou opérations, comité multisig de trésorerie
- **Nom du contact publiquement identifié** : Fonction : équipe sécurité/opérations de la fondation Kelp DAO et signataires du multisig de trésorerie. Nom non publié dans ce rapport.
- **Canal de contact public disponible** : Post-mortem et communiqué publics du protocole (source S01) ; Canaux officiels du projet (X et Discord) référencés dans sa documentation publique ; Forum de gouvernance du protocole, s'il en dispose
- **Raison pour laquelle cette organisation est une cible** : Incident public très récent touchant directement la couche autorisation : la fenêtre d'approche est ouverte 30 à 60 jours, et la direction doit pouvoir documenter ses contrôles d'autorisation auprès de sa communauté, de ses intégrateurs et des venues qui acceptent ses actifs.
- **Besoin** : EXPLICITEMENT EXPRIMÉ (incident public du 15/09/2026, post-mortem et mesures annoncés)
- **Potentiel** : Ponctuel puis revue trimestrielle des autorisations
- **Ordre de grandeur d'honoraires envisageable** : Forfait 7–12 k€ pour 5–8 jours — estimation indicative, à valider
- **Prochaine action recommandée** : Préparer une note d'approche de 1 page (angle: contrôles de la couche autorisation, pas d'audit de code) et demander un échange de 30 minutes. Validation L5 avant envoi.
- **Statut commercial actuel** : NON CONTACTÉ — validation L5 requise

### OPP-07 — Population cible : 24 DAO détenant des Safe avec modules actifs (trésorerie > 20 M$)

- **ID de l'opportunité** : OPP-07
- **Organisation / projet** : Population cible : 24 DAO détenant des Safe avec modules actifs (trésorerie > 20 M$)
- **Pays ou zone** : Mondial / Web3 - sans localisation
- **Secteur** : trésorerie DAO (multi-protocoles)
- **Score opportunité** : 80.5/100
- **Score DARKINT** : 87.5/100
- **Priorité** : PRIORITÉ IMMÉDIATE
- **Problème détecté** : Problème structurel : tout module attaché à un Safe peut exécuter des transactions sans confirmation des propriétaires. Aucune des DAO ciblées ne publie d'inventaire de ses modules ni de politique de révocation. L'incident rsETH du 15/09/2026 et le cas SuDAO (2022) démontrent le même mode de défaillance à 4 ans d'intervalle.
- **Éléments factuels ayant conduit à identifier le besoin** :
  - Tout module attaché à un portefeuille Safe peut exécuter des transactions sans confirmation des propriétaires : les modules sont plus puissants que les propriétaires eux-mêmes (source S33, post-mortem de 2022 ; source S01, 2026).
  - Le portefeuille multi-signatures reste le standard dominant des trésoreries de DAO (sources S09 et S11).
  - Aucune des organisations ciblées ne publie d'inventaire de ses modules, ni de politique de révocation, ni de calendrier de revue (constat par recherche ouverte, à confirmer organisation par organisation).
  - Même mode de défaillance reproduit à quatre ans d'intervalle (2022 et 2026) avec des pertes de 56 k$ puis 7,8 M$ (sources S33 et S01).
- **Niveau de confirmation de la source** : OBSERVÉ (faits confirmés ; absence d'inventaire = constat, non besoin exprimé)
- **Source(s) avec URL** :
  - S01 — MEV Bot Yoink Beats Hacker to $7.8M rsETH Haul (shattered.io, 2026-09-19) : https://shattered.io/yoink-mev-bot-beats-hacker-rseth-2026/
  - S33 — A Technical Post Mortem of SuperUMAn DAO (SuDAO) Hack - Flaws In Existing Governance Tools (module Safe/Zodiac Reality, surveillance 24/7) (publish0x / medium-coinmonks, 2022-11-24) : https://www.publish0x.com/everythingblockchain/a-technical-post-mortem-of-superuman-dao-sudao-hack-flaws-in-xozrzmj
  - S09 — DAO Treasury Management: Onchain Governance & Spend (seuils, signataires, prestataires: Steakhouse, Karpatkey, Block Analitica, Coinshift, Den) (eco.com, 2026-05-26) : https://eco.com/support/en/articles/14799687-dao-treasury-management-onchain-governance-spend
- **Date des sources** : 2026-09-19
- **Mission précise que Roch pourrait proposer** : Offre productisée : « Inventaire et révocation des modules Safe » - recensement des modules et automatisations attachés aux Safe de trésorerie, analyse du périmètre d'autorisation de chacun, identification des modules dormants ou non revus, recommandations de révocation et politique d'installation (qui approuve, quel délai, quelle revue).
- **Livrable proposé** : Inventaire des modules + fiche d'autorisation par module + recommandations de révocation + politique d'installation et de revue + déclaration d'intégrité pour la gouvernance.
- **Intervention solo** : OUI
- **Durée estimée** : 2-4 par organisation
- **Charge estimée (heures / jours)** : 16–32 heures par organisation (2–4 jours)
- **Travail à distance** : OUI
- **Niveau de difficulté** : Faible
- **Compétences nécessaires** : Inventaire des modules et autorisations, Revue de politique de signature, Contrôle interne, Pédagogie des signataires, Connaissance Safe et des modules de gouvernance
- **Besoin éventuel d'un partenaire** : NON
- **Personne ou fonction à contacter** : Multisig signataires, comité de trésorerie, responsable sécurité, cercles de délégués
- **Nom du contact publiquement identifié** : Fonction : signataires du multisig, comité de trésorerie, responsable sécurité, cercles de délégués. Aucun nom publié dans ce rapport.
- **Canal de contact public disponible** : Forums de gouvernance des DAO ciblées ; Canaux Discord publics de contributeurs ; Documentation publique des trésoreries
- **Raison pour laquelle cette organisation est une cible** : Problème systémique documenté à quatre reprises, offre standardisable en 2 à 4 jours par organisation, décision prise directement par les signataires : un seul modèle de prestation peut être vendu à une cohorte de DAO.
- **Besoin** : PROBABLE (problème structurel confirmé ; aucune des organisations ciblées n'a exprimé le besoin)
- **Potentiel** : récurrent : revue trimestrielle ou semestrielle des autorisations
- **Ordre de grandeur d'honoraires envisageable** : Forfait 3–5 k€ par DAO pour 2–4 jours — estimation indicative ; revue récurrente trimestrielle ou semestrielle facturable séparément
- **Prochaine action recommandée** : Constituer la liste des 24 cibles avec le Safe concerne et le contact de gouvernance, puis campagne d'approche par cohorte. Validation L5 avant tout envoi.
- **Statut commercial actuel** : NON CONTACTÉ — liste de 24 cibles à confirmer par analyse on-chain avant toute approche (validation L5)

### OPP-02 — Nostra Finance

- **ID de l'opportunité** : OPP-02
- **Organisation / projet** : Nostra Finance
- **Pays ou zone** : Starknet (mondial) - inconnu (équipe distribuée)
- **Secteur** : DeFi - marché monétaire / lending
- **Score opportunité** : 80.0/100
- **Score DARKINT** : 90.0/100
- **Priorité** : PRIORITÉ IMMÉDIATE
- **Problème détecté** : Second incident oracle en 18 mois. Le 17/09/2026 un prix NSTR manipulé à permis à un seul compte d'emprunter ~3,5 M$ contre un collatéraux surévalué (5x la capitalisation du token). Marché en pause, réconciliation par pool en cours, aucun oracle de secours disponible pour ces actifs.
- **Éléments factuels ayant conduit à identifier le besoin** :
  - Le 17/09/2026, un prix NSTR manipulé a permis à un seul compte d'emprunter environ 3,5 M$ contre un collatéral surévalué, soit plus de cinq fois la capitalisation du jeton (source S03, 18/09/2026).
  - Le marché monétaire est mis en pause pour réconciliation pool par pool ; aucun oracle de secours n'était disponible pour ces actifs (source S03).
  - Antécédent : erreur de flux oracle sur les jetons xSTRK/sSTRK en mars 2025 risquant des liquidations erronées (source S03).
  - Famille d'incidents fréquente : Rhea (7,6 M$), Silo (392 k$), Moonwell, Venus, YieldBlox, sur la même période 2025-2026 (source S04, 19/05/2026).
- **Niveau de confirmation de la source** : CONFIRMÉ (communication officielle de l'équipe, alertes CertiK, classification DefiLlama)
- **Source(s) avec URL** :
  - S03 — Nostra Halts Its Starknet Money Market After a $3.5M NSTR Oracle Exploit (cryptotimes.io, 2026-09-18) : https://www.cryptotimes.io/2026/09/18/nostra-halts-starknet-money-market-after-3-5m-nstr-oracle-exploit/
  - S04 — Biggest DeFi Hacks and Exploits of 2026: $1 Billion+ Lost and Counting (ccn.com, 2026-05-19) : https://www.ccn.com/education/crypto/defi-hacks-exploits-causes-crypto-stolen-2026/
- **Date des sources** : 2026-09-17
- **Mission précise que Roch pourrait proposer** : Refonte du dispositif de contrôle des paramètres de marché et des oracles : politique d'activation des collatéraux, plafonds, oracle de repli, seuils d'alerte, revue croisée avant tout changement de paramètre, journal des changements, tests de liquidation.
- **Livrable proposé** : Cadre de contrôle oracle et collatéraux (framework) + checklist de change control + tableau de bord de suivi + note de gouvernance pour validation DAO.
- **Intervention solo** : OUI
- **Durée estimée** : 4-6
- **Charge estimée (heures / jours)** : 30–45 heures (4–6 jours)
- **Travail à distance** : OUI
- **Niveau de difficulté** : Moyenne
- **Compétences nécessaires** : Contrôle interne, Gestion des risques de marché, Conception de contrôles sur les paramètres (change control), Politique d'oracles et de secours, Rédaction de procédures
- **Besoin éventuel d'un partenaire** : NON
- **Personne ou fonction à contacter** : équipe fondatrice / responsable risque du protocole ; conseil de gouvernance
- **Nom du contact publiquement identifié** : Fonction : équipe fondatrice, responsable risque du protocole, conseil de gouvernance. Nom non publié dans ce rapport.
- **Canal de contact public disponible** : Communiqué officiel publié le 17/09/2026 (source S03) ; Canaux officiels du protocole (X et Discord)
- **Raison pour laquelle cette organisation est une cible** : Deuxième incident oracle en dix-huit mois : le besoin de contrôle des paramètres de marché et des feeds est démontré, et la direction vient de perdre la confiance d'une partie de ses utilisateurs. La remédiation documentée devient un enjeu de survie du marché.
- **Besoin** : EXPLICITEMENT EXPRIMÉ (second incident oracle reconnu, marché mis en pause, post-mortem annoncé)
- **Potentiel** : Ponctuel + revue mensuelle des paramètres
- **Ordre de grandeur d'honoraires envisageable** : Forfait 5–9 k€ pour 4–6 jours — estimation indicative, à valider
- **Prochaine action recommandée** : Proposer un diagnostic flash de 3 jours sur le change control oracle, à prix forfaitaire, livrable en 10 jours. Validation L5 avant envoi.
- **Statut commercial actuel** : NON CONTACTÉ — validation L5 requise

### OPP-14 — Directions financières de sociétés détenant de la trésorerie crypto (sociétés de trésorerie d'actifs numériques, fintechs, e-money)

- **ID de l'opportunité** : OPP-14
- **Organisation / projet** : Directions financières de sociétés détenant de la trésorerie crypto (sociétés de trésorerie d'actifs numériques, fintechs, e-money)
- **Pays ou zone** : Europe / International - France, UE, international
- **Secteur** : Finance d'entreprise - trésorerie crypto
- **Score opportunité** : 77.4/100
- **Score DARKINT** : 75.5/100
- **Priorité** : FORTE OPPORTUNITÉ
- **Problème détecté** : 42% des directeurs financiers citent la complexité comptable et de contrôle comme frein à l'adoption crypto (Deloitte Q2 2025). Les normes de trésorerie exigent identité, preuve, horodatage et chaîne d'approbation ; les explorateurs de blocs ne fournissent rien de tout cela. S'ajoutent les attestations mensuelles, la segregation des portefeuilles et les preuves de réserves sous MiCA, et des pistes d'audit exportables limitées chez plusieurs plateformes de custody.
- **Éléments factuels ayant conduit à identifier le besoin** :
  - 42 % des directeurs financiers citent la complexité comptable et de contrôle comme frein principal à l'adoption des actifs numériques (source S14, 2026).
  - Les normes de trésorerie exigent identité, preuve, horodatage et alignement de politique ; les explorateurs de blocs ne fournissent que des hachages (source S14).
  - Les obligations d'attestations mensuelles, de ségrégation des portefeuilles et de preuve de réserves se renforcent sous le cadre européen (source S15, 21/07/2026).
  - L'export des journaux d'audit reste limité chez plusieurs plateformes de conservation d'actifs (source S30, 16/05/2026).
- **Niveau de confirmation de la source** : OBSERVÉ (besoin documenté par plusieurs études ; applicabilité client par client probable)
- **Source(s) avec URL** :
  - S14 — Crypto Treasury Management: The 2026 Institutional Playbook (42% des CFO citent la complexité comptable et de contrôle; fragmentation des pistes d'audit) (coinsdo.com, 2026-06-15) : https://www.coinsdo.com/en/crypto-treasury
  - S15 — Digital Asset Policy Changes in 2025 and 2026 (attestations mensuelles, portefeuilles ségréguées, proof-of-reserves, MiCA) (bitgo.com, 2026-07-21) : https://www.bitgo.com/resources/blog/digital-asset-policy-changes-2026/
  - S30 — Digital Asset Security Platforms Compared: DFNS vs Fireblocks vs Anchorage (limites des pistes d'audit exportables, custody qualifiée) (ridgewayfs.com, 2026-05-16) : https://www.ridgewayfs.com/digital-asset-security-platforms/
  - S32 — MPC Wallets Aren't Enough for Institutional Custody (politique, moteur de règles, journal d'audit inviolable) (chainup.com, 2026-08-18) : https://chainup.com/blog/mpc-wallets-arent-enough-for-instutional-custody
- **Date des sources** : 2026-07-21
- **Mission précise que Roch pourrait proposer** : Revue de préparation à l'audit de la trésorerie crypto : chaîne d'approbation, séparation des rôles, inventaire des portefeuilles et seuils, rapprochement des écritures, preuves horodatées, dossier de justification pour l'auditeur et le conseil d'administration.
- **Livrable proposé** : Diagnostic de préparation à l'audit + matrice de contrôles + dossier de preuves type + plan de remédiation.
- **Intervention solo** : OUI
- **Durée estimée** : 5-8
- **Charge estimée (heures / jours)** : 40–60 heures (5–8 jours)
- **Travail à distance** : OUI
- **Niveau de difficulté** : Moyenne
- **Compétences nécessaires** : Audit interne, Contrôles de trésorerie, Comptabilité des actifs numériques, Documentation de preuves, Anglais professionnel
- **Besoin éventuel d'un partenaire** : NON (appui ponctuel cabinet comptable possible) (Expert-comptable pour validation des écritures)
- **Personne ou fonction à contacter** : DAF, contrôleur de gestion, comité d'audit, expert-comptable
- **Nom du contact publiquement identifié** : Fonction : directeur administratif et financier, contrôleur de gestion, comité d'audit, expert-comptable. Nom non publié dans ce rapport.
- **Canal de contact public disponible** : Réseaux de directeurs financiers indépendants ; Cabinets comptables partenaires ; Réseaux professionnels en ligne
- **Raison pour laquelle cette organisation est une cible** : Population solvable et sous-servie : la jonction entre processus de trésorerie et preuve d'audit on-chain n'est traitée ni par les cabinets comptables ni par les plateformes techniques. Mission courte, récurrente et à forte valeur pour un directeur financier.
- **Besoin** : PROBABLE (friction documentée par les études sectorielles ; besoin non exprimé par une organisation identifiée)
- **Potentiel** : récurrent mensuel ou trimestriel
- **Ordre de grandeur d'honoraires envisageable** : Forfait 7–12 k€ pour 5–8 jours — estimation indicative ; rapprochement mensuel récurrent facturable
- **Prochaine action recommandée** : Constituer la liste de 15 sociétés européennes détenant du bitcoin ou des stablecoins en trésorerie et proposer un diagnostic de 5 jours. Validation L5 avant envoi.
- **Statut commercial actuel** : NON CONTACTÉ — liste de 15 sociétés européennes à constituer (validation L5)

### OPP-16 — Cabinets d'expertise comptable et de paie de taille intermédiaire (Royaume-Uni, France, Benelux)

- **ID de l'opportunité** : OPP-16
- **Organisation / projet** : Cabinets d'expertise comptable et de paie de taille intermédiaire (Royaume-Uni, France, Benelux)
- **Pays ou zone** : Europe - Royaume-Uni, France, Benelux
- **Secteur** : Cabinets comptables - contrôle des flux et fonds clients
- **Score opportunité** : 77.0/100
- **Score DARKINT** : 81.5/100
- **Priorité** : FORTE OPPORTUNITÉ
- **Problème détecté** : La fraude à la facture touché les cabinets par quatre canaux internes : redirection des notes d'honoraires, changement de coordonnées bancaires chez le client, détournement de paie au niveau du bureau de paie, remboursements et fonds clients. Un cabinet de 25 personnes sort du dispositif de remboursement obligatoire. L'autorite britannique à sanctionné un cabinet 60 000 livres pour un compte administrateur sans authentification multifacteur.
- **Éléments factuels ayant conduit à identifier le besoin** :
  - Quatre schémas de fraude à la facture spécifiques aux cabinets sont documentés : redirection des notes d'honoraires, changement de coordonnées chez le client, détournement de paie, remboursements et fonds clients (source S19, 19/08/2026).
  - Un cabinet de 25 personnes sort du dispositif de remboursement obligatoire, ce qui en fait un risque supporté en propre (source S19).
  - L'autorité britannique de protection des données a sanctionné un cabinet de 60 000 livres après une intrusion via un compte administrateur sans authentification multifacteur (source S19).
  - Au niveau macroéconomique, 24 768 plaintes et 3,05 milliards de dollars de pertes déclarées en 2025 (+10 % sur un an) et 74 % des organisations touchées par la fraude au président (source S18, 24/08/2026).
- **Niveau de confirmation de la source** : CONFIRMÉ (données sectorielles et cas de sanction) - besoin par cabinet = probable
- **Source(s) avec URL** :
  - S19 — Business Email Compromise in Accountancy Firms: 4 patterns de fraude facture; hors dispositif de remboursement; sanction ICO DPP Law (progressiverobot.com, 2026-08-19) : https://www.progressiverobot.com/2026/08/19/invoice-fraud-accountancy-firms-business-email-compromise/
  - S18 — Business Email Compromise Statistics 2026 (FBI 2025: 24 768 plaintes, 3,05 Md$; VEC ~61% du BEC; AFP: 74% des organisations touchées) (deepstrike.io, 2026-08-24) : https://deepstrike.io/blog/business-email-compromise-statistics
- **Date des sources** : 2026-08-19
- **Mission précise que Roch pourrait proposer** : Revue des contrôles anti-fraude du cabinet et de ses clients : contrôle des changements de coordonnées bancaires, vérification par canal indépendant, double approbation, surveillance des boites mail, procédure d'incident et de déclaration, formation des équipes.
- **Livrable proposé** : Rapport de revue des contrôles + procédure de changement de coordonnées bancaires + politique de vérification par canal indépendant + session de formation (2 h) + scénario de test.
- **Intervention solo** : OUI
- **Durée estimée** : 3-5
- **Charge estimée (heures / jours)** : 20–35 heures (3–5 jours)
- **Travail à distance** : PARTIEL (revue documentaire et entretiens à distance ; formation à distance)
- **Niveau de difficulté** : Faible
- **Compétences nécessaires** : Contrôle interne des processus de paiement, Fraude et fausse facture, Séparation des fonctions, Formation des équipes, Procédures de vérification par canal indépendant
- **Besoin éventuel d'un partenaire** : NON (appui ponctuel prestataire informatique si durcissement technique) (Prestataire Microsoft 365 / messagerie)
- **Personne ou fonction à contacter** : Associé gérant, responsable qualité et risque, responsable informatique
- **Nom du contact publiquement identifié** : Fonction : associé gérant, responsable qualité et risque, responsable informatique. Nom non publié dans ce rapport.
- **Canal de contact public disponible** : Ordres professionnels et associations de cabinets ; Réseaux de dirigeants ; Démarche directe auprès des associés
- **Raison pour laquelle cette organisation est une cible** : Population très large (des dizaines de milliers de cabinets en Europe), cycle de vente court, décision par l'associé gérant, prestation de 3 à 5 jours répétable à l'identique : idéal pour un volume de petites missions.
- **Besoin** : PROBABLE (données sectorielles confirmées ; besoin non exprimé par un cabinet identifié)
- **Potentiel** : récurrent : test trimestriel et formation annuelle
- **Ordre de grandeur d'honoraires envisageable** : Forfait 3,5–6 k€ pour 3–5 jours — estimation indicative ; exercice de test et formation annuels récurrents (1–2 k€)
- **Prochaine action recommandée** : Constituer une liste de 30 cabinets cibles au Royaume-Uni et en France, proposer un diagnostic de 3 jours. Validation L5 avant envoi.
- **Statut commercial actuel** : NON CONTACTÉ — liste de 30 cabinets cibles à constituer (validation L5)

### OPP-10 — DAO de taille intermédiaire (trésorerie 10-50 M$) sans fonction finance structurée

- **ID de l'opportunité** : OPP-10
- **Organisation / projet** : DAO de taille intermédiaire (trésorerie 10-50 M$) sans fonction finance structurée
- **Pays ou zone** : Mondial / Web3 - sans localisation
- **Secteur** : trésorerie et reporting DAO
- **Score opportunité** : 76.7/100
- **Score DARKINT** : 76.0/100
- **Priorité** : FORTE OPPORTUNITÉ
- **Problème détecté** : Les grandes DAO emploient des prestataires de trésorerie (Steakhouse Financial, Karpatkey, Block Analitica) sous mandat avec reporting mensuel. Les DAO intermédiaires n'ont ni mandat, ni reporting standardisé, ni piste d'audit : les transactions multisig sont visibles mais non documentées (vote d'autorisation, objet economique, signataires, valeur de marché à la date).
- **Éléments factuels ayant conduit à identifier le besoin** :
  - Les grandes DAO emploient des mandataires de trésorerie avec reporting mensuel et mandat voté (source S09, 26/05/2026).
  - Les transactions multi-signatures sont visibles on-chain mais non documentées : il manque le vote d'autorisation, l'objet économique, les signataires et la valeur de marché à la date d'exécution (source S10, 08/04/2026).
  - Les matrices d'approbation, la rotation des clés et la séparation des fonctions ne sont pas systématiquement définies (source S11, 02/01/2026).
  - La jonction entre processus de trésorerie classique et preuve on-chain est identifiée comme la principale friction d'audit (sources S14 et S30).
- **Niveau de confirmation de la source** : OBSERVÉ (gap documenté par plusieurs guides sectoriels ; besoin probable)
- **Source(s) avec URL** :
  - S09 — DAO Treasury Management: Onchain Governance & Spend (seuils, signataires, prestataires: Steakhouse, Karpatkey, Block Analitica, Coinshift, Den) (eco.com, 2026-05-26) : https://eco.com/support/en/articles/14799687-dao-treasury-management-onchain-governance-spend
  - S10 — DAO Accounting: A Practical Guide for Finance Leads and Accountants (audit trail gap) (breezing.io, 2026-04-08) : https://breezing.io/blog/dao-accounting-guide/
  - S11 — DAO Treasury Management: Accounting and Financial Reporting Guide (matrices d'approbation, rotation des clés, séparation des fonctions) (fortress-accounting.com, 2026-01-02) : https://fortress-accounting.com/dao-treasury-management-accounting-financial-reporting/
- **Date des sources** : 2026-05-26
- **Mission précise que Roch pourrait proposer** : Pack mensuel de reporting et de contrôle pour trésorerie DAO : états de trésorerie mensuels, réconciliation on-chain, journal des décisions de gouvernance rattachees aux mouvements, indicateurs de risque (concentration, liquidité, runway en stablecoins), seuils d'approbation par taille de transaction.
- **Livrable proposé** : Pack de reporting mensuel (modèle + 3 mois de production) + politique de seuils et de séparation des rôles + registre des décisions.
- **Intervention solo** : OUI
- **Durée estimée** : 5 jours de mise en place puis 0,5-1 jour par mois
- **Charge estimée (heures / jours)** : 35 heures de mise en place (5 jours) puis 4–8 heures par mois
- **Travail à distance** : OUI
- **Niveau de difficulté** : Moyenne
- **Compétences nécessaires** : Comptabilité et reporting de trésorerie, Réconciliation on-chain, Séparation des fonctions, Construction de tableaux de bord, Anglais professionnel
- **Besoin éventuel d'un partenaire** : NON
- **Personne ou fonction à contacter** : trésorier, multisig signataires, cercle de délégués, fondation
- **Nom du contact publiquement identifié** : Fonction : trésorier, signataires du multisig, cercle de délégués, fondation. Nom non publié dans ce rapport.
- **Canal de contact public disponible** : Forums de gouvernance ; Appels communautaires publics ; Recommandations entre DAO
- **Raison pour laquelle cette organisation est une cible** : Segment large, peu servi : les DAO intermédiaires n'ont ni mandataire ni reporting standardisé. Une prestation mensuelle reproductible (0,5 à 1 jour par mois) crée un revenu récurrent à faible coût d'acquisition une fois le modèle écrit.
- **Besoin** : PROBABLE (écart documenté par les guides sectoriels ; besoin non exprimé par les organisations concernées)
- **Potentiel** : récurrent mensuel (modèle abonnement)
- **Ordre de grandeur d'honoraires envisageable** : 1,5–3 k€ de mise en place puis 800–1 800 € par mois — estimation indicative ; modèle d'abonnement recommandé
- **Prochaine action recommandée** : Constituer une liste de 20 DAO cibles avec trésorerie dans la fourchette et absence de prestataire de reporting ; proposer un mois pilote. Validation L5 avant envoi.
- **Statut commercial actuel** : NON CONTACTÉ — liste de 20 DAO cibles à constituer (validation L5)

### OPP-13 — Fintech / edtech (recrutement publié, mandat d'approche par cabinet)

- **ID de l'opportunité** : OPP-13
- **Organisation / projet** : Fintech / edtech (recrutement publié, mandat d'approche par cabinet)
- **Pays ou zone** : International (rôle à distance, éligibilité à vérifier) - États-Unis / Royaume-Uni (à confirmer)
- **Secteur** : Finance - direction financière fractionnaire
- **Score opportunité** : 73.2/100
- **Score DARKINT** : 61.5/100
- **Priorité** : FORTE OPPORTUNITÉ
- **Problème détecté** : Besoin exprimé publiquement : DAF fractionnaire 6 à 8 heures par semaine en remote pour une fintech (Rosie's People), contrôleur fractionnaire 50-100 $/heure en remote, DAF intérimaire 130-175 $/heure en remote. Le marché du DAF fractionnaire est actif et les clients acceptent l'intervention à distance sur quelques heures par mois.
- **Éléments factuels ayant conduit à identifier le besoin** :
  - Annonce de direction financière fractionnaire de 6 à 8 heures par semaine pour une fintech, en télétravail (source S28, 30/08/2026).
  - Annonces de contrôleur fractionnaire à 50–100 $ de l'heure et de direction financière intérimaire à 130–175 $ de l'heure, en télétravail (source S28).
  - Le marché accepte explicitement des interventions de quelques heures par mois (source S28).
  - Les postes listés sont majoritairement localisés aux États-Unis et au Royaume-Uni, avec des exigences locales à vérifier (source S28).
- **Niveau de confirmation de la source** : EXPRIMÉ (annonces publiées)
- **Source(s) avec URL** :
  - S28 — Fractional CFO (6-8 heures/semaine) - Fintech / Remote; Fractional Controller 50-100$/h remote; Interim CFO 130-175$/h remote (fractionalpulse.com, 2026-08-30) : https://fractionalpulse.com/jobs/
- **Date des sources** : 2026-08-30
- **Mission précise que Roch pourrait proposer** : Direction financière fractionnaire : pilotage de la trésorerie, prévisionnel, reporting investisseurs, mise en place de contrôles, due diligence finance.
- **Livrable proposé** : Tableau de bord mensuel + prévisionnel glissant 12 mois + revue de contrôles + dossier de reporting investisseurs.
- **Intervention solo** : OUI
- **Durée estimée** : récurrent : 6-8 heures par semaine
- **Charge estimée (heures / jours)** : 25–35 heures par mois (6–8 heures par semaine)
- **Travail à distance** : OUI
- **Niveau de difficulté** : Moyenne
- **Compétences nécessaires** : Direction financière, Prévisionnel et pilotage de trésorerie, Reporting investisseurs, Contrôles internes, Anglais professionnel courant
- **Besoin éventuel d'un partenaire** : NON
- **Personne ou fonction à contacter** : Fondateur/CEO, CFO, responsable recrutement du cabinet mandataire
- **Nom du contact publiquement identifié** : Fonction : fondateur ou direction générale, responsable recrutement du cabinet mandataire ; interlocuteurs publiés dans les annonces.
- **Canal de contact public disponible** : Plateforme de recrutement fractionnaire (source S28) ; Plateformes généralistes de recrutement avec annonces en télétravail
- **Raison pour laquelle cette organisation est une cible** : Besoin exprimé, format immédiatement compatible avec une intervention solo à distance, et rémunération horaire publiée : c'est le point d'entrée le plus rapide du registre, sous réserve d'éligibilité contractuelle.
- **Besoin** : EXPLICITEMENT EXPRIMÉ (annonces publiques de recrutement publiées)
- **Potentiel** : récurrent hebdomadaire
- **Ordre de grandeur d'honoraires envisageable** : 60–150 € de l'heure selon le mandat, soit 1 500–4 500 € par mois — références de marché relevées dans les annonces (source S28)
- **Prochaine action recommandée** : Vérifier l'éligibilité (statut de travail, monnaie, contrat international) avant dépôt ; visée en priorité des mandats UE/UK. Validation L5 avant candidature.
- **Statut commercial actuel** : NON CONTACTÉ — vérification d'éligibilité (statut de travail, devise, contrat international) requise avant candidature (validation L5)

### OPP-09 — DAO utilisant les modules de gouvernance Zodiac / Reality (SafeSnap)

- **ID de l'opportunité** : OPP-09
- **Organisation / projet** : DAO utilisant les modules de gouvernance Zodiac / Reality (SafeSnap)
- **Pays ou zone** : Mondial / Web3 - sans localisation
- **Secteur** : Gouvernance on-chain
- **Score opportunité** : 71.8/100
- **Score DARKINT** : 80.0/100
- **Priorité** : FORTE OPPORTUNITÉ
- **Problème détecté** : Le module d'exécution de gouvernance exige une surveillance humaine permanente : toute personne peut poser une question à l'oracle, l'absence d'arbitre ou un arbitre mal configuré conduit à l'acceptation de la réponse la mieux garantie, et le veto doit intervenir dans une fenêtre de grâce. Une DAO dont l'équipe n'est pas joignable en continu est exposée malgré un Safe correctement configuré.
- **Éléments factuels ayant conduit à identifier le besoin** :
  - Un module d'exécution de gouvernance peut exécuter des transactions sans confirmation des propriétaires (source S33, 24/11/2022).
  - Toute personne peut poser une question à l'oracle de gouvernance ; en l'absence d'arbitre, la réponse la mieux garantie est acceptée, et le veto doit intervenir dans une fenêtre de grâce (source S33).
  - Le dispositif exige une surveillance humaine permanente : toute équipe non joignable en continu est exposée malgré un portefeuille correctement configuré (source S33).
  - Le risque de signature à l'aveugle a été illustré à grande échelle en 2025 par un détournement de 1,4 Md$ via une interface falsifiée (source S34, 26/02/2025).
- **Niveau de confirmation de la source** : CONFIRMÉ (post-mortem détaillé) - problème toujours présent chez les utilisateurs actuels = PROBABLE
- **Source(s) avec URL** :
  - S33 — A Technical Post Mortem of SuperUMAn DAO (SuDAO) Hack - Flaws In Existing Governance Tools (module Safe/Zodiac Reality, surveillance 24/7) (publish0x / medium-coinmonks, 2022-11-24) : https://www.publish0x.com/everythingblockchain/a-technical-post-mortem-of-superuman-dao-sudao-hack-flaws-in-xozrzmj
  - S34 — Bybit Hack Post-Mortem identifiés Safe Infrastructure as Exploit Point (frontend falsifié, blind signing) (bankless.com, 2025-02-26) : https://www.bankless.com/read/bybit-hack-post-mortem-identifies-safe-infrastructure-as-exploit-point
- **Date des sources** : 2022-11-24
- **Mission précise que Roch pourrait proposer** : Runbook d'exécution de gouvernance : inventaire des chemins d'exécution (votes, modules, automatisations), qui doit surveiller quoi et quand, fenêtres de veto, astreinte et escalade, tests trimestriels d'un scénario d'attaque, journal des exécutions.
- **Livrable proposé** : Runbook de surveillance et d'escalade + matrice des fenêtres de veto + procédure de test trimestriel + journal d'exécution.
- **Intervention solo** : OUI
- **Durée estimée** : 4-6
- **Charge estimée (heures / jours)** : 30–45 heures (4–6 jours)
- **Travail à distance** : OUI
- **Niveau de difficulté** : Moyenne
- **Compétences nécessaires** : Analyse de scénarios d'attaque, Rédaction de runbook et d'astreinte, Gouvernance, Contrôle interne, Formation des signataires
- **Besoin éventuel d'un partenaire** : NON
- **Personne ou fonction à contacter** : comité de sécurité de la DAO, signataires, administrateurs du module
- **Nom du contact publiquement identifié** : Fonction : comité de sécurité de la DAO, signataires, administrateurs du module ; éditeurs des modules (canal de distribution). Nom non publié dans ce rapport.
- **Canal de contact public disponible** : Documentation publique des modules de gouvernance ; Forums de gouvernance des DAO équipées ; Éditeurs des modules (partenariat de distribution possible)
- **Raison pour laquelle cette organisation est une cible** : Population identifiable et solvable (DAO équipées de ces modules), besoin de documentation opérationnelle non couvert par les auditeurs de code, et livrable léger : le runbook de surveillance est une porte d'entrée peu concurrentielle.
- **Besoin** : PROBABLE (mode de défaillance confirmé par post-mortem ; besoin non exprimé par les utilisateurs actuels des modules)
- **Potentiel** : récurrent (test trimestriel)
- **Ordre de grandeur d'honoraires envisageable** : Forfait 4–8 k€ pour 4–6 jours — estimation indicative ; test trimestriel récurrent facturable
- **Prochaine action recommandée** : Écrire un guide public court (« ce que votre module de gouvernance peut faire sans vous ») et le diffuser comme outil d'entree. Validation L5 avant publication.
- **Statut commercial actuel** : NON CONTACTÉ — validation L5 requise

### OPP-06 — Unlock DAO

- **ID de l'opportunité** : OPP-06
- **Organisation / projet** : Unlock DAO
- **Pays ou zone** : Mondial / Web3 - inconnu
- **Secteur** : Infrastructure Web3 (protocole d'accès)
- **Score opportunité** : 70.2/100
- **Score DARKINT** : 78.0/100
- **Priorité** : FORTE OPPORTUNITÉ
- **Problème détecté** : Problème de quorum reconnu publiquement en février 2026 : un nombre important de tokens délégués à des portefeuilles inactifs, budget Q1/Q2 2026 rejeté faute de quorum malgré une participation record. Solutions court terme en cours (délégation multiple depuis la trésorerie, abstention de la trésorerie) presentant des risques de sécurité à l'exécution. Un affaiblissement du seuil de quorum reste à l'étude.
- **Éléments factuels ayant conduit à identifier le besoin** :
  - La DAO publie en février 2026 que le seuil de quorum de 3 millions de jetons n'est plus atteint en raison de délégations vers des portefeuilles inactifs (source S06, 12/02/2026).
  - La proposition budgétaire du premier semestre 2026 a enregistré une participation record sans atteindre le quorum (source S06).
  - Deux solutions de court terme sont à l'étude : délégation multiple depuis la trésorerie et abstention de la trésorerie ; la seconde est présentée comme porteuse de risques de sécurité à l'exécution (source S06).
  - Contexte sectoriel : participation inférieure à 10 % et concentration du pouvoir de vote sur les plus gros porteurs (sources S12 et S13).
- **Niveau de confirmation de la source** : EXPRIMÉ (besoin reconnu explicitement par la DAO dans ses publications et appels)
- **Source(s) avec URL** :
  - S06 — Unlock DAO Newsletter février 2026 - The Quest for Quorum (paragraph.com / Unlock Protocol, 2026-02-12) : https://paragraph.com/@unlockprotocol/unlock-dao-newsletter-or-february-2026
  - S12 — How DAOs Failed to Deliver on Their Original Promise (participation <10%, top 10% détient 76,2% du pouvoir de vote, Compound 2024) (medium / lopetaku, 2026-03-12) : https://lopetaku.medium.com/dao-governance-failures-whales-low-turnout-attacks-d1375c556384
- **Date des sources** : 2026-02-12
- **Mission précise que Roch pourrait proposer** : Revue indépendante du dispositif de quorum et de délégation : analyse des conséquences (sécurité, légitimité, risque de capture), cadre de délégation depuis la trésorerie, garde-fous d'exécution, politique de quorum cible et mécanisme de délégation dynamique.
- **Livrable proposé** : Note d'analyse des options de quorum (avantages/risques par option) + politique de délégation + garde-fous d'exécution + indicateur de santé de gouvernance.
- **Intervention solo** : OUI
- **Durée estimée** : 5-8
- **Charge estimée (heures / jours)** : 35–55 heures (5–8 jours)
- **Travail à distance** : OUI
- **Niveau de difficulté** : Moyenne
- **Compétences nécessaires** : Conception de mécanismes de gouvernance, Analyse du pouvoir de vote et des délégations, Gestion des risques d'exécution, Rédaction de politique, Vulgarisation pour la communauté
- **Besoin éventuel d'un partenaire** : NON
- **Personne ou fonction à contacter** : Stewards, contributeurs actifs, délégués (leaderboard de participation)
- **Nom du contact publiquement identifié** : Fonction : stewards, contributeurs actifs et délégués de la DAO (un classement public de participation existe). Nom de personne non publié dans ce rapport.
- **Canal de contact public disponible** : Forum de gouvernance de la DAO ; Lettre d'information officielle du protocole (source S06)
- **Raison pour laquelle cette organisation est une cible** : Besoin reconnu publiquement, options déjà ouvertes et non tranchées : la DAO cherche activement un cadre d'analyse indépendant, et la décision bloquée (budget) crée une urgence réelle.
- **Besoin** : EXPLICITEMENT EXPRIMÉ (problème de quorum reconnu dans les publications officielles de la DAO)
- **Potentiel** : Ponctuel
- **Ordre de grandeur d'honoraires envisageable** : Forfait 5–10 k€ pour 5–8 jours — estimation indicative ; budget de gouvernance généralement limité, valeur d'entrée de relation élevée
- **Prochaine action recommandée** : Répondre au fil de discussion ouvert en proposant une analyse structurée des options et une offre de revue de 5 jours. Validation L5 avant envoi.
- **Statut commercial actuel** : NON CONTACTÉ — validation L5 requise

### OPP-19 — Fintechs, prestataires de paiement et assureurs de taille intermédiaire

- **ID de l'opportunité** : OPP-19
- **Organisation / projet** : Fintechs, prestataires de paiement et assureurs de taille intermédiaire
- **Pays ou zone** : Europe - France, UE
- **Secteur** : Audit interne externalisé (co-sourcing)
- **Score opportunité** : 70.2/100
- **Score DARKINT** : 73.0/100
- **Priorité** : FORTE OPPORTUNITÉ
- **Problème détecté** : Les entités réglementées de taille intermédiaire doivent disposer d'une fonction d'audit interne ou en confier l'exercice à un tiers, avec un plan annuel et des missions documentées. Elles n'ont souvent ni les volumes ni les budgets pour une équipe interne complète.
- **Éléments factuels ayant conduit à identifier le besoin** :
  - Les entités financières de taille intermédiaire doivent disposer d'une fonction d'audit interne ou en confier l'exercice à un tiers, avec plan annuel et missions documentées (sources S15 et S17).
  - Les budgets ne permettent pas une équipe interne complète ; le marché du co-sourcing est actif (source S28, annonces d'audit interne et de contrôle).
  - Les thèmes récurrents sont les contrôles de trésorerie, les processus de paiement, la sous-traitance et la gestion des accès (sources S16 et S17).
  - Les comités d'audit de taille intermédiaire cherchent des prestataires capables de produire des rapports exploitables, pas seulement des constats.
- **Niveau de confirmation de la source** : PROBABLE (obligation de place, besoin exprimé de manière fragmentaire)
- **Source(s) avec URL** :
  - S15 — Digital Asset Policy Changes in 2025 and 2026 (attestations mensuelles, portefeuilles ségréguées, proof-of-reserves, MiCA) (bitgo.com, 2026-07-21) : https://www.bitgo.com/resources/blog/digital-asset-policy-changes-2026/
  - S17 — DORA Third-Party ICT Risk: Articles 28-30 Guide for 2026 (obligations, reporting annuel, plan de sortie) (cyadviso.com, 2026-06-01) : https://www.cyadviso.com/dora-third-party-ict-risk
- **Date des sources** : 2026-06-01
- **Mission précise que Roch pourrait proposer** : Co-sourcing de la fonction d'audit interne : plan d'audit fondé sur les risques, 2 à 4 missions par an (contrôles de trésorerie, processus de paiement, sous-traitance, accès), suivi des recommandations.
- **Livrable proposé** : Plan d'audit annuel + rapports de mission + tableau de suivi des recommandations + note au comité d'audit.
- **Intervention solo** : OUI (1 à 2 missions en parallèle maximum)
- **Durée estimée** : récurrent : 2 à 4 missions de 3-5 jours par an
- **Charge estimée (heures / jours)** : 24–40 heures par mission de 3 à 5 jours, 2 à 4 missions par an
- **Travail à distance** : OUI
- **Niveau de difficulté** : Moyenne
- **Compétences nécessaires** : Audit interne, Plan d'audit fondé sur les risques, Contrôles de trésorerie et de paiement, Suivi des recommandations, Rédaction de rapports au comité d'audit
- **Besoin éventuel d'un partenaire** : NON
- **Personne ou fonction à contacter** : Président du comité d'audit, DAF, directeur conformité
- **Nom du contact publiquement identifié** : Fonction : président du comité d'audit, directeur administratif et financier, directeur conformité. Nom non publié dans ce rapport.
- **Canal de contact public disponible** : Réseaux d'administrateurs ; Associations de directeurs financiers et de risque ; Cabinets d'expertise comptable
- **Raison pour laquelle cette organisation est une cible** : Mandat annuel renouvelable (2 à 4 missions de 3 à 5 jours), décision prise par le comité d'audit, concurrence des grands cabinets moins agressive sur ce format.
- **Besoin** : PROBABLE (obligation de place, demandes fragmentaires)
- **Potentiel** : récurrent annuel
- **Ordre de grandeur d'honoraires envisageable** : 3–6 k€ par mission, soit 8–20 k€ par an — estimation indicative
- **Prochaine action recommandée** : Préparer un plan d'audit type présentable en 2 pages et le proposer à 10 entités cibles. Validation L5 avant envoi.
- **Statut commercial actuel** : NON CONTACTÉ — plan d'audit type à préparer (validation L5)

### OPP-12 — Venues de prêt et protocoles acceptant des actifs pontés (Euler, Silo, Fluid, Morpho, Venus)

- **ID de l'opportunité** : OPP-12
- **Organisation / projet** : Venues de prêt et protocoles acceptant des actifs pontés (Euler, Silo, Fluid, Morpho, Venus)
- **Pays ou zone** : Mondial / Web3 - sans localisation
- **Secteur** : DeFi - lending
- **Score opportunité** : 68.5/100
- **Score DARKINT** : 77.5/100
- **Priorité** : FORTE OPPORTUNITÉ
- **Problème détecté** : Même cause structurelle que OPP-08 mais population plus large : les venues intermédiaires admettent des actifs pontés ou tokenisés sans registre de leurs dépendances (vérificateur, sous-traitants, oracle, émission) ni analyse de concentration. La contagion d'avril 2026 à montre que la défaillance d'un seul vérificateur devient une exposition commune.
- **Éléments factuels ayant conduit à identifier le besoin** :
  - La contagion d'avril 2026 a montré qu'une défaillance unique de vérificateur devient une exposition commune à toutes les venues acceptant l'actif (source S02, 22/04/2026).
  - Les venues intermédiaires n'entretiennent ni registre de dépendances par actif, ni analyse de concentration par fournisseur (constat de recherche ouverte).
  - Le cadre réglementaire européen impose désormais un registre des accords, une analyse de concentration et la visibilité sur les sous-traitants de rang 2 et 3 pour les entités financières (sources S16 et S17, 2026).
  - Environ 47 % des applications d'un fournisseur de messagerie inter-chaînes restaient en configuration à vérificateur unique en septembre 2026 (source S05).
- **Niveau de confirmation de la source** : OBSERVÉ (mécanisme confirmé ; applicabilité par venue = probable)
- **Source(s) avec URL** :
  - S02 — DeFi's $606M April: Kelp DAO bridge drain, Drift Protocol oracle+key compromise, Resolv AWS heist (bex.co, 2026-04-22) : https://bex.co/blog/2026/04/22/april-606m-hack-spree-defi-protocol-upgrade-vulnerabilities-kelp-drift-resolv
  - S05 — DeFi has lost $1.3 billion to hacks in 2026 and the same attack keeps working (cryptonews.net, 2026-09-05) : https://cryptonews.net/news/security/33396919/
- **Date des sources** : 2026-09-05
- **Mission précise que Roch pourrait proposer** : Registre des dépendances d'actifs admis : fiche de dépendance par actif (pont, vérificateur, oracle, émissions, sous-traitants), analyse de concentration par fournisseur, seuils d'alerte et plan de sortie documenté.
- **Livrable proposé** : Registre des dépendances par actif + analyse de concentration + seuils d'alerte + plan de sortie.
- **Intervention solo** : PARTIEL
- **Durée estimée** : 5-8
- **Charge estimée (heures / jours)** : 40–60 heures (5–8 jours)
- **Travail à distance** : OUI
- **Niveau de difficulté** : Moyenne à élevée
- **Compétences nécessaires** : Registre des dépendances, Analyse de concentration, Gestion des tiers, Rédaction de plans de sortie, Anglais technique
- **Besoin éventuel d'un partenaire** : OUI (analyse on-chain) (Analyste on-chain)
- **Personne ou fonction à contacter** : Fournisseur de risque, comité de marché, équipe protocole
- **Nom du contact publiquement identifié** : Fonction : fournisseur de risque, comité de marché, équipe protocole. Nom non publié dans ce rapport.
- **Canal de contact public disponible** : Forums de gouvernance des protocoles ; Publications des fournisseurs de risque ; Conférences sectorielles
- **Raison pour laquelle cette organisation est une cible** : Population large de venues de taille moyenne où la concurrence des grands cabinets est faible : le registre des dépendances est un livrable cadré, vendable à l'unité, puis renouvelable chaque trimestre.
- **Besoin** : PROBABLE (mécanisme confirmé ; applicabilité par venue à vérifier)
- **Potentiel** : récurrent trimestriel
- **Ordre de grandeur d'honoraires envisageable** : Forfait 6–11 k€ pour 5–8 jours — estimation indicative ; revue trimestrielle récurrente
- **Prochaine action recommandée** : Constituer la liste des venues cibles et proposer un registre pilote à prix fixe. Validation L5 avant envoi.
- **Statut commercial actuel** : NON CONTACTÉ — validation L5 requise

### OPP-05 — Arbitrum DAO (Treasury Management Committee)

- **ID de l'opportunité** : OPP-05
- **Organisation / projet** : Arbitrum DAO (Treasury Management Committee)
- **Pays ou zone** : Mondial / Web3 - inconnu (entité DAO)
- **Secteur** : Infrastructure L2 - trésorerie DAO
- **Score opportunité** : 67.8/100
- **Score DARKINT** : 85.5/100
- **Priorité** : FORTE OPPORTUNITÉ
- **Problème détecté** : Transfert en mars 2026 de 6 000 ETH et de stablecoins inactifs vers un Treasury Management Portfolio géré par mandat (IPS, mandataires, bandes d'allocation). Le dispositif crée un besoin d'assurance indépendante : contrôle des reportings de mandataires, respect des limites de risque, réconciliation on-chain, information des délégués.
- **Éléments factuels ayant conduit à identifier le besoin** :
  - Un appel à propositions pour la gestion de trésorerie a été publié par la commission de gestion, portant sur les jetons de gouvernance, les stablecoins et l'ether (source S08, 22/01/2025).
  - En mars 2026, la communauté a examiné le transfert de 6 000 ETH et de stablecoins inactifs vers un portefeuille de gestion encadré par une politique d'investissement (source S07, 19/08/2026).
  - Le dispositif prévoit des mandats, des bandes d'allocation, des limites de risque et un reporting périodique aux délégués (source S07).
  - Les mandataires professionnels opèrent sous mandat voté avec reporting mensuel, mais le contrôle indépendant de leur conformité n'est pas structuré (source S09, 26/05/2026).
- **Niveau de confirmation de la source** : CONFIRMÉ (propositions et documents de gouvernance publics)
- **Source(s) avec URL** :
  - S07 — DAO Treasury Diversification: Funding opérations Without Dumping Tokens (Treasury Management Portfolio Arbitrum, 6 000 ETH, mars 2026) (cryptodaily.co.uk, 2026-08-19) : https://cryptodaily.co.uk/2026/08/dao-treasury-diversification-funding-operations
  - S08 — [RFP Process] Request for Proposals: Treasury Management Services for Arbitrum DAO (forum.arbitrum.foundation, 2025-01-22) : https://forum.arbitrum.foundation/t/rfp-process-request-for-proposals-treasury-management-services-for-arbitrum-dao/28242
  - S09 — DAO Treasury Management: Onchain Governance & Spend (seuils, signataires, prestataires: Steakhouse, Karpatkey, Block Analitica, Coinshift, Den) (eco.com, 2026-05-26) : https://eco.com/support/en/articles/14799687-dao-treasury-management-onchain-governance-spend
- **Date des sources** : 2026-03-15
- **Mission précise que Roch pourrait proposer** : Conception d'un cadre d'assurance et de reporting pour mandats de gestion de trésorerie DAO : indicateurs de conformité au mandat, seuils d'alerte, revue trimestrielle indépendante, format de reporting aux délégués.
- **Livrable proposé** : Cadre d'assurance des mandats + modèle de reporting trimestriel + grille de conformité au mandat.
- **Intervention solo** : PARTIEL
- **Durée estimée** : 7-10
- **Charge estimée (heures / jours)** : 50–70 heures (7–10 jours)
- **Travail à distance** : OUI
- **Niveau de difficulté** : Moyenne à élevée
- **Compétences nécessaires** : Contrôle de mandat et conformité, Reporting financier, Analyse de risque et de concentration, Gouvernance, Rédaction de cadre d'assurance
- **Besoin éventuel d'un partenaire** : OUI (pour l'accès au mandat principal) (Cabinet de gestion d'actifs / structure de gestion de trésorerie on-chain)
- **Personne ou fonction à contacter** : Treasury Management Committee, Entropy Advisors, délégués majeurs
- **Nom du contact publiquement identifié** : Organe public : commission de gestion de trésorerie de la DAO ; mandataire identifié publiquement (Entropy Advisors). Nom de personne non publié dans ce rapport.
- **Canal de contact public disponible** : Forum de gouvernance de la fondation (fil d'appel à propositions, source S08) ; Appels de travail publics de la commission
- **Raison pour laquelle cette organisation est une cible** : Un mandat de gestion voté crée mécaniquement un besoin d'assurance indépendante : contrôle du reporting du mandataire, respect des limites, et information des délégués. La DAO est solvable et habituée à rémunérer des prestataires externes.
- **Besoin** : EXPLICITEMENT EXPRIMÉ (appel à prestataires de gestion de trésorerie publié ; mandat ensuite voté)
- **Potentiel** : récurrent (mandats pluriannuels)
- **Ordre de grandeur d'honoraires envisageable** : Forfait 10–16 k€ pour 7–10 jours — estimation indicative ; volet récurrent trimestriel envisageable
- **Prochaine action recommandée** : Publier une contribution méthodologique courte sur le forum (cadre d'assurance des mandats) pour se positionner sans concurrence frontale. Validation L5 avant publication.
- **Statut commercial actuel** : NON CONTACTÉ — validation L5 requise

### OPP-08 — Aave (et marchés de prêt acceptant des LST pontés)

- **ID de l'opportunité** : OPP-08
- **Organisation / projet** : Aave (et marchés de prêt acceptant des LST pontés)
- **Pays ou zone** : Mondial / Web3 - inconnu
- **Secteur** : DeFi - lending
- **Score opportunité** : 67.6/100
- **Score DARKINT** : 87.5/100
- **Priorité** : FORTE OPPORTUNITÉ
- **Problème détecté** : Après le drain du bridge rsETH, environ 196 M$ de bad debt se sont concentrés sur une seule paire rsETH/wrapped-ether. Les venues de prêt acceptant ce collatéraux ne pouvaient pas voir que leur garantie reposait sur un pont à modèle de défaillance 1-sur-1 (vérificateur unique, 47% des applications LayerZero concernées selon les données de septembre 2026).
- **Éléments factuels ayant conduit à identifier le besoin** :
  - Après le drain du pont rsETH, environ 196 M$ de bad debt se sont concentrés sur une paire rsETH/wrapped-ether (source S02, 22/04/2026).
  - Les venues de prêt acceptant l'actif en garantie ne pouvaient pas voir que leur collatéral reposait sur un pont à défaillance 1-sur-1 (source S02).
  - En septembre 2026, environ 47 % des applications d'un fournisseur de messagerie inter-chaînes restaient configurées avec un vérificateur unique (source S05, 05/09/2026).
  - Le protocole dispose de fournisseurs de risque et d'un forum de gouvernance active, ce qui facilite l'entrée d'une analyse externe (source S09).
- **Niveau de confirmation de la source** : CONFIRMÉ (analyse publique, données on-chain)
- **Source(s) avec URL** :
  - S02 — DeFi's $606M April: Kelp DAO bridge drain, Drift Protocol oracle+key compromise, Resolv AWS heist (bex.co, 2026-04-22) : https://bex.co/blog/2026/04/22/april-606m-hack-spree-defi-protocol-upgrade-vulnerabilities-kelp-drift-resolv
  - S05 — DeFi has lost $1.3 billion to hacks in 2026 and the same attack keeps working (cryptonews.net, 2026-09-05) : https://cryptonews.net/news/security/33396919/
- **Date des sources** : 2026-04-22
- **Mission précise que Roch pourrait proposer** : Revue du cadre d'admission des collatéraux : cartographie des dépendances (pont, vérificateur, oracle, émission), analyse de concentration, scénario de défaillance en cascade, limites d'exposition et plan de réduction progressive.
- **Livrable proposé** : Matrice de dépendances des collatéraux + analyse de concentration + limites d'exposition proposées + plan de réduction progressive.
- **Intervention solo** : PARTIEL
- **Durée estimée** : 6-10
- **Charge estimée (heures / jours)** : 45–70 heures (6–10 jours) avec appui d'analyse on-chain
- **Travail à distance** : OUI
- **Niveau de difficulté** : Élevée
- **Compétences nécessaires** : Analyse de risque de contrepartie et de dépendances, Admission des collatéraux, Analyse de concentration, Gestion de crise, Rédaction de limites d'exposition
- **Besoin éventuel d'un partenaire** : OUI (Analyste on-chain / data scientist DeFi pour la reconstitution des expositions)
- **Personne ou fonction à contacter** : Risk Council / service providers de risque du protocole, équipe croissance
- **Nom du contact publiquement identifié** : Fonction : conseil des risques du protocole, fournisseurs de risque mandatés, équipe croissance. Nom de personne non publié dans ce rapport.
- **Canal de contact public disponible** : Forum de gouvernance du protocole ; Publications des fournisseurs de risque
- **Raison pour laquelle cette organisation est une cible** : Le protocole est la première victime de contagion documentée : la thématique de concentration des dépendances est déjà dans son agenda, et une revue ciblée peut s'intégrer à un travail existant porté par les fournisseurs de risque.
- **Besoin** : PROBABLE (mécanisme de contagion confirmé par les analyses publiques ; position du protocole non exprimée)
- **Potentiel** : Ponctuel + revue trimestrielle
- **Ordre de grandeur d'honoraires envisageable** : Mission 9–15 k€ pour 6–10 jours — estimation indicative ; concurrence élevée sur ce segment, viser une niche (dépendances de rang 2 et 3)
- **Prochaine action recommandée** : Cibler d'abord les venues de taille moyenne (Euler, Silo, Fluid, Morpho) ou la concurrence est plus faible que sur Aave. Validation L5 avant envoi.
- **Statut commercial actuel** : NON CONTACTÉ — validation L5 requise

### OPP-04 — Drift Protocol

- **ID de l'opportunité** : OPP-04
- **Organisation / projet** : Drift Protocol
- **Pays ou zone** : Solana (mondial) - inconnu
- **Secteur** : DeFi - perps / derivatives
- **Score opportunité** : 67.1/100
- **Score DARKINT** : 94.5/100
- **Priorité** : FORTE OPPORTUNITÉ
- **Problème détecté** : 285 M$ soustraits en 128 secondes (01/04/2026) : autorité pré-signée obtenue auprès du Security Council via un nonce durable (fonctionnalité native de Solana), token sans valeur accepte comme collatéraux, oracle contrôlé par l'attaquant, retraits massifs. Conflit d'intérêt signalé : les multisigs et l'infrastructure partagée entre protocoles concentrent le risque.
- **Éléments factuels ayant conduit à identifier le besoin** :
  - Le 01/04/2026, 285 M$ ont été retirés en 128 secondes après obtention d'une autorité pré-signée auprès du conseil de sécurité via un nonce durable, fonctionnalité native de Solana (sources S02 et S05).
  - Un audit antérieur (Neodyme, 2024) avait identifié l'absence de validation de compte oracle, classée en remarque informative au motif que seul l'administrateur pouvait l'appeler (source S05, 05/09/2026).
  - Dépôt de 500 millions de jetons sans valeur en collatéral contre un oracle contrôlé pendant trois semaines avant l'attaque (source S05).
  - L'attaque a reposé sur une relation de confiance construite sur plusieurs mois avec les contributeurs (source S05).
- **Niveau de confirmation de la source** : CONFIRMÉ (analyse Neodyme citée, déclarations publiques, post-mortem)
- **Source(s) avec URL** :
  - S02 — DeFi's $606M April: Kelp DAO bridge drain, Drift Protocol oracle+key compromise, Resolv AWS heist (bex.co, 2026-04-22) : https://bex.co/blog/2026/04/22/april-606m-hack-spree-defi-protocol-upgrade-vulnerabilities-kelp-drift-resolv
  - S05 — DeFi has lost $1.3 billion to hacks in 2026 and the same attack keeps working (cryptonews.net, 2026-09-05) : https://cryptonews.net/news/security/33396919/
- **Date des sources** : 2026-04-01
- **Mission précise que Roch pourrait proposer** : Cartographie des autorités administratives et de leurs modes d'approbation (qui peut faire quoi, avec quel délai), revue des autorisations pré-signées et des nonces durables, politique de clé, procédure de revue des collatéraux, plan de sortie de la dépendance à une entité de sécurité unique.
- **Livrable proposé** : Cartographie des autorités + registre des autorisations pré-signées + politique de signature + plan de remédiation.
- **Intervention solo** : PARTIEL
- **Durée estimée** : 8-12
- **Charge estimée (heures / jours)** : 60–90 heures (8–12 jours) avec appui technique
- **Travail à distance** : OUI
- **Niveau de difficulté** : Élevée
- **Compétences nécessaires** : Gouvernance et séparation des pouvoirs, Cartographie des autorités administratives, Politique de clés et d'autorisations pré-signées, Contrôle interne, Gestion des conflits d'intérêts
- **Besoin éventuel d'un partenaire** : OUI (ingénieur Solana / expert gouvernance on-chain pour l'analyse technique des autorités)
- **Personne ou fonction à contacter** : Security Council, fondation Drift, responsable sécurité
- **Nom du contact publiquement identifié** : Fonction : conseil de sécurité, équipe de sécurité, direction du protocole. Nom non publié dans ce rapport.
- **Canal de contact public disponible** : Post-mortem public du protocole ; Forum et canaux officiels du protocole
- **Raison pour laquelle cette organisation est une cible** : Le sinistre le plus documenté de 2026 sur l'abus d'autorité administrative : la direction a besoin de reconstruire un dispositif d'autorisations opposable, y compris vis-à-vis de ses investisseurs et partenaires de marché.
- **Besoin** : EXPLICITEMENT EXPRIMÉ (post-mortem public d'un détournement de 285 M$)
- **Potentiel** : Ponctuel
- **Ordre de grandeur d'honoraires envisageable** : Mission 12–20 k€ pour 8–12 jours — estimation indicative, à valider ; dossier à mener avec un partenaire technique
- **Prochaine action recommandée** : Positionner d'abord la cartographie des autorités (composant non technique, 5-6 jours) comme porte d'entree, avec expertise technique en appui. Validation L5 avant envoi.
- **Statut commercial actuel** : NON CONTACTÉ — validation L5 requise

### OPP-17 — Entreprises de taille moyenne à forte intensité de paiements (immobilier, construction, santé, industrie)

- **ID de l'opportunité** : OPP-17
- **Organisation / projet** : Entreprises de taille moyenne à forte intensité de paiements (immobilier, construction, santé, industrie)
- **Pays ou zone** : Europe / Amérique du Nord - France, UE, Amérique du Nord
- **Secteur** : Tous secteurs - processus de paiement
- **Score opportunité** : 65.6/100
- **Score DARKINT** : 79.0/100
- **Priorité** : FORTE OPPORTUNITÉ
- **Problème détecté** : La compromission de messagerie de fournisseur représente environ 61% des cas de fraude au président en 2026 : l'attaquant compromet un fournisseur réel et modifié un numero de compte. L'an dernier, les autorités americaines ont enregistré 24 768 plaintes et 3,05 milliards de dollars de pertes. Les contrôles de messagerie ne valident pas le processus métier : demande de changement de coordonnées vérifiée ou non, paiement à double autorisation ou non.
- **Éléments factuels ayant conduit à identifier le besoin** :
  - La compromission de la messagerie d'un fournisseur représente environ 61 % des cas de fraude au président en 2026 : l'attaquant modifie un numéro de compte sur une facture attendue (source S18, 24/08/2026).
  - Une campagne d'usurpation assistée par intelligence artificielle a envoyé plus d'un million de courriers en trois jours en août 2026, en visant les équipes comptables (source S20, 10/09/2026).
  - Les pertes vérifiées dépassent 100 k$ en moyenne par incident (source S18) ; les contrôles de messagerie ne valident pas le processus métier (source S18).
  - Environ 30 % des violations impliquent désormais un tiers, contre 15 % un an plus tôt (source S21, 14/05/2026).
- **Niveau de confirmation de la source** : CONFIRMÉ (statistiques officielles et recherches fournisseurs) - applicabilité par entreprise = probable
- **Source(s) avec URL** :
  - S18 — Business Email Compromise Statistics 2026 (FBI 2025: 24 768 plaintes, 3,05 Md$; VEC ~61% du BEC; AFP: 74% des organisations touchées) (deepstrike.io, 2026-08-24) : https://deepstrike.io/blog/business-email-compromise-statistics
  - S20 — Protecting organizations from AI-assisted exécutive impersonation and invoice fraud (>1 million d'e-mails, 3-5 aout 2026) (Microsoft Security Blog, 2026-09-10) : https://www.microsoft.com/en-us/security/blog/2026/09/10/protecting-organizations-ai-assisted-executive-impersonation-invoice-fraud/
  - S21 — Third-Party Email Compromise doubled in one year (Verizon DBIR 2025: 30% des violations impliquent un tiers) (duocircle.com, 2026-05-14) : https://www.duocircle.com/blog/third-party-email-compromise-doubled-smb-vendor-security-risks-solutions/
- **Date des sources** : 2026-08-24
- **Mission précise que Roch pourrait proposer** : Revue du processus de paiement et anti-usurpation : vérification des changements de coordonnées, autorisations, seuils, gestion des fournisseurs, détection des règles de transfert automatique, plan de reaction et récupération des fonds, formation des équipes comptables.
- **Livrable proposé** : Cartographie des points de défaillance + procédure anti-usurpation + matrice d'autorisation des paiements + scénario d'exercice de crise + module de formation.
- **Intervention solo** : OUI
- **Durée estimée** : 4-6
- **Charge estimée (heures / jours)** : 30–45 heures (4–6 jours)
- **Travail à distance** : OUI
- **Niveau de difficulté** : Faible à moyenne
- **Compétences nécessaires** : Cartographie des points de défaillance, Contrôles de paiement et autorisations, Exercice de crise, Formation, Gestion des fournisseurs
- **Besoin éventuel d'un partenaire** : NON
- **Personne ou fonction à contacter** : DAF, responsable comptabilité, directeur des systèmes d'information
- **Nom du contact publiquement identifié** : Fonction : directeur administratif et financier, responsable comptabilité, directeur des systèmes d'information, courtier en assurance cyber. Nom non publié dans ce rapport.
- **Canal de contact public disponible** : Cabinet comptable partenaire ; Courtiers d'assurance risques cyber ; Associations de directeurs financiers
- **Raison pour laquelle cette organisation est une cible** : Le sujet est porté par les assureurs et les courtiers, qui financent les revues exigées : canal de distribution naturel pour une prestation courte de revue du processus de paiement.
- **Besoin** : PROBABLE (phénomène massif documenté ; besoin non exprimé par une entreprise identifiée)
- **Potentiel** : Ponctuel + exercice annuel
- **Ordre de grandeur d'honoraires envisageable** : Forfait 5–9 k€ pour 4–6 jours — estimation indicative ; exercice annuel et formation récurrents
- **Prochaine action recommandée** : Cibler les secteurs à paiement sensible (immobilier, construction) et passer par les courtiers d'assurance comme canal. Validation L5 avant démarchage.
- **Statut commercial actuel** : NON CONTACTÉ — validation L5 requise avant démarchage par les courtiers

### OPP-22 — UNFPA - roster de consultants finance (branche finance du siège)

- **ID de l'opportunité** : OPP-22
- **Organisation / projet** : UNFPA - roster de consultants finance (branche finance du siège)
- **Pays ou zone** : International - international (missions courtes)
- **Secteur** : Organisations internationales - finance
- **Score opportunité** : 65.4/100
- **Score DARKINT** : 69.5/100
- **Priorité** : FORTE OPPORTUNITÉ
- **Problème détecté** : UNFPA constitue un roster de consultants locaux et internationaux pour des affectations de courte durée couvrant les opérations financières, le reporting bailleurs, la comptabilité des stocks et les transferts de fonds aux partenaires de mise en œuvre. Les besoins portent sur les normes IPSAS, la réconciliation des avances aux partenaires, la qualité des rapports financiers aux bailleurs et les outils de consolidation.
- **Éléments factuels ayant conduit à identifier le besoin** :
  - L'agence constitue un vivier de consultants locaux et internationaux pour des affectations courtes couvrant les opérations financières, le reporting bailleurs, la comptabilité des stocks et les transferts de fonds aux partenaires (source S26, 23/06/2026).
  - Les besoins portent sur les normes comptables du secteur public, la réconciliation des avances aux partenaires et la qualité des rapports financiers (source S26).
  - Les affectations sont courtes et répétées, sous l'autorité du chef d'unité de la branche finance (source S26).
  - Le français est valorisé comme l'une des langues officielles (source S26).
- **Niveau de confirmation de la source** : EXPRIMÉ (roster permanent publié)
- **Source(s) avec URL** :
  - S26 — Roster: Finance Consultant (UNFPA - IPSAS, reporting bailleurs, transferts de fonds aux partenaires, compta stocks) (unfpa.org, 2026-06-23) : https://www.unfpa.org/jobs/roster-finance-consultant
- **Date des sources** : 2026-06-23
- **Mission précise que Roch pourrait proposer** : Consultances courtes : opérations financières IPSAS, reporting bailleurs, comptabilité et contrôle des stocks, transferts de fonds et réconciliation des avances aux partenaires de mise en œuvre.
- **Livrable proposé** : Rapports financiers bailleurs, états de réconciliation, procédures et notes de guidance.
- **Intervention solo** : OUI
- **Durée estimée** : Affectations courtes répétées
- **Charge estimée (heures / jours)** : 30 jours ouvrés par affectation type
- **Travail à distance** : OUI (certaines missions sur site possibles)
- **Niveau de difficulté** : Moyenne
- **Compétences nécessaires** : Normes comptables du secteur public, Reporting bailleurs, Réconciliation d'avances, Contrôle interne, Anglais; français valorisé
- **Besoin éventuel d'un partenaire** : NON
- **Personne ou fonction à contacter** : Chef d'unite de la branche finance, chef comptes, chef de la branche finance
- **Nom du contact publiquement identifié** : Fonction : chef d'unité de la branche finance, chef des comptes, chef de branche. Adresse dédiée du vivier publiée dans l'avis.
- **Canal de contact public disponible** : Avis de vivier publié par l'organisation (source S26) ; Portails de recrutement des agences des Nations unies
- **Raison pour laquelle cette organisation est une cible** : Vivier à alimenter une fois pour des missions courtes répétées, réalisables largement à distance, avec une exigence linguistique où le profil français est avantagé.
- **Besoin** : EXPLICITEMENT EXPRIMÉ (vivier de consultants publié par la branche finance)
- **Potentiel** : récurrent
- **Ordre de grandeur d'honoraires envisageable** : Selon grille de l'agence, ordre de grandeur 300–550 € par jour — estimation indicative, à confirmer
- **Prochaine action recommandée** : Actualiser le dossier de candidature (IPSAS, reporting bailleurs, transferts de fonds) et candidater au roster. Validation L5 avant dépôt.
- **Statut commercial actuel** : NON CONTACTÉ — dossier de candidature au vivier à actualiser (validation L5)

### OPP-18 — Prestataires de services sur crypto-actifs et fintechs en cours d'agrément (MiCA, DORA)

- **ID de l'opportunité** : OPP-18
- **Organisation / projet** : Prestataires de services sur crypto-actifs et fintechs en cours d'agrément (MiCA, DORA)
- **Pays ou zone** : Union européenne - France, UE
- **Secteur** : conformité financière
- **Score opportunité** : 63.8/100
- **Score DARKINT** : 68.5/100
- **Priorité** : OPPORTUNITÉ EXPLOITABLE
- **Problème détecté** : Mise en conformité continue des acteurs crypto agreees : dispositif de contrôle interne, cartographie des risques, procédures, gouvernance, articulation avec les obligations de résilience numérique. Beaucoup d'entites de taille modeste n'ont pas de responsable conformité à temps plein.
- **Éléments factuels ayant conduit à identifier le besoin** :
  - Les obligations de conformité continue s'appliquent aux prestataires de services sur crypto-actifs agréés : dispositif de contrôle interne, cartographie des risques, procédures, gouvernance (sources S15 et S16).
  - Le cadre européen impose aux entités concernées des attestations et des preuves de réserves récurrentes (source S15, 21/07/2026).
  - Beaucoup d'entités de taille modeste n'ont pas de responsable conformité à temps plein (constat de recherche ouverte).
  - Les exigences de résilience numérique s'ajoutent au dispositif de contrôle interne classique (source S16).
- **Niveau de confirmation de la source** : PROBABLE (obligations certaines, besoin non exprimé individuellement)
- **Source(s) avec URL** :
  - S15 — Digital Asset Policy Changes in 2025 and 2026 (attestations mensuelles, portefeuilles ségréguées, proof-of-reserves, MiCA) (bitgo.com, 2026-07-21) : https://www.bitgo.com/resources/blog/digital-asset-policy-changes-2026/
  - S16 — How Does DORA Address Third-Party ICT Risk? (Art. 28-30, registre d'informations, sous-traitance en chaîne, concentration) (thingsrecon.com, 2026-09-02) : https://www.thingsrecon.com/blog/how-does-dora-address-third-party-ict-risk
- **Date des sources** : 2026-07-21
- **Mission précise que Roch pourrait proposer** : Appui conformité et contrôle interne à temps partagé : cartographie des risques, procédures, plan de contrôle annuel, préparation des revues du superviseur.
- **Livrable proposé** : Cartographie des risques + plan de contrôle annuel + procédures clés + dossier de préparation d'inspection.
- **Intervention solo** : OUI
- **Durée estimée** : récurrent : 1-3 jours par mois
- **Charge estimée (heures / jours)** : 8–24 heures par mois selon le mandat
- **Travail à distance** : OUI
- **Niveau de difficulté** : Moyenne
- **Compétences nécessaires** : Conformité financière, Cartographie des risques, Plan de contrôle annuel, Préparation d'inspection, Gouvernance
- **Besoin éventuel d'un partenaire** : NON
- **Personne ou fonction à contacter** : Dirigeant, responsable conformité, conseil d'administration
- **Nom du contact publiquement identifié** : Fonction : dirigeant, responsable conformité, conseil d'administration. Nom non publié dans ce rapport.
- **Canal de contact public disponible** : Associations professionnelles du secteur ; Incubateurs et accélérateurs ; Cabinets d'avocats spécialisés
- **Raison pour laquelle cette organisation est une cible** : Besoin récurrent de conformité par nature, clientèle concentrée en France et en Europe, et possibilité d'un mandat mensuel de 1 à 3 jours : modèle économique régulier.
- **Besoin** : PROBABLE (obligations certaines, besoin individuel non exprimé)
- **Potentiel** : récurrent mensuel
- **Ordre de grandeur d'honoraires envisageable** : 1 200–4 000 € par mois selon 1–3 jours par mois — estimation indicative
- **Prochaine action recommandée** : Identifier 12 fintechs et prestataires crypto en phase d'agrément ou de post-agrement en France. Validation L5 avant envoi.
- **Statut commercial actuel** : NON CONTACTÉ — liste de 12 entités à constituer (validation L5)

### OPP-21 — Banque africaine de développement (BAD) - consultant individuel via DACON et avis à manifestation d'intérêt

- **ID de l'opportunité** : OPP-21
- **Organisation / projet** : Banque africaine de développement (BAD) - consultant individuel via DACON et avis à manifestation d'intérêt
- **Pays ou zone** : Afrique / international - Cote d'Ivoire (siège) et opérations régionales
- **Secteur** : Financement international - assistance technique
- **Score opportunité** : 62.5/100
- **Score DARKINT** : 77.0/100
- **Priorité** : OPPORTUNITÉ EXPLOITABLE
- **Problème détecté** : La BAD recrute en continu des consultants individuels pour des missions de 6 à 12 semaines (souvent sur court préavis) et publié des avis à manifestation d'intérêt, dont des postes en télétravail (par exemple l'appui au secrétariat du hub NDC en 2026, ou l'assistance technique à la banque du Ghana). Les candidats éligibles doivent être ressortissants d'un pays membre, titulaires d'un master et justifier de dix ans d'expérience ; l'inscription à DACON conditionne le repérage, pas la sélection.
- **Éléments factuels ayant conduit à identifier le besoin** :
  - La banque recrute en continu des consultants individuels pour des missions de 6 à 12 semaines, souvent à court préavis, avec des postes en télétravail complet (sources S23 et S24).
  - Un avis d'assistance technique pour la mise en œuvre d'un code de financement auprès d'une banque centrale a été publié en mai 2026 (source S23).
  - L'inscription au fichier de consultants conditionne le repérage, pas la sélection : l'éligibilité exige la nationalité d'un pays membre, un master et dix ans d'expérience (source S24).
  - Les candidatures passent par le fichier de consultants et par des avis à manifestation d'intérêt publiés en continu (source S24).
- **Niveau de confirmation de la source** : EXPRIMÉ (avis et procédures publics)
- **Source(s) avec URL** :
  - S23 — EOI - Technical Assistance to the Bank of Ghana in the implementation of the WE Finance Code (AHGC) (afdb.org, 2026-05-20) : https://www.afdb.org/en/consultants/eoi-technical-assistance-bank-ghana-implementation-we-finance-ahgc-93448
  - S24 — Acquisition of Consultancy Services - Individual Consultants (BAD: DACON, éligibilité, missions de 6 à 12 semaines) (afdb.org, 2024-01-01) : https://www.afdb.org/en/projects-and-operations/procurement/frequently-asked-questions/acquisition-of-consultancy-services-individual-consultants
  - S36 — Cork Finance exploit post-mortem 28 mai 2025 (hook Uniswap v4, 3 761 wstETH, multsig pour pause) (cork.tech, 2025-06-04) : https://www.cork.tech/blog/post-mortem
- **Date des sources** : 2026-05-20
- **Mission précise que Roch pourrait proposer** : Missions d'assistance technique et de contrôle financier : appui au suivi financier de projets, revue des dispositifs de contrôle interne, rapports financiers, appui à la mise en place de procédures.
- **Livrable proposé** : Selon la mission : rapport de revue, note de procédure, appui au reporting.
- **Intervention solo** : OUI
- **Durée estimée** : Missions de 6 à 12 semaines
- **Charge estimée (heures / jours)** : Missions de 30 à 60 jours ouvrés
- **Travail à distance** : PARTIEL (mises à jour de poste ; télétravail frequent)
- **Niveau de difficulté** : Moyenne
- **Compétences nécessaires** : Suivi financier de projets, Contrôle interne, Reporting bailleurs, Français et anglais, Connaissance des procédures des banques de développement
- **Besoin éventuel d'un partenaire** : NON
- **Personne ou fonction à contacter** : Départements sectoriels de la BAD, comité de recrutement et de supervision des consultants, unités d'exécution des projets emprunteurs
- **Nom du contact publiquement identifié** : Fonction : départements sectoriels, comité de recrutement et de supervision des consultants, unités d'exécution des projets. Nom non publié dans ce rapport.
- **Canal de contact public disponible** : Page consultants du site institutionnel (source S24) ; Avis à manifestation d'intérêt publiés (source S23)
- **Raison pour laquelle cette organisation est une cible** : Canal institutionnel à faible concurrence relative, missions de 6 à 12 semaines répétées, possibilité de télétravail : un dossier d'inscription bien préparé ouvre un flux régulier de sollicitations.
- **Besoin** : EXPLICITEMENT EXPRIMÉ (procédures publiques de recrutement de consultants individuels)
- **Potentiel** : récurrent continu
- **Ordre de grandeur d'honoraires envisageable** : Selon grille institutionnelle, généralement 250–600 € par jour pour un consultant individuel senior — estimation indicative, à confirmer au dossier
- **Prochaine action recommandée** : Vérifier l'éligibilité (nationalité d'un pays membre, diplôme, dix ans d'expérience), s'inscrire à DACON et préparer une fiche d'identification standard. Validation L5 avant inscription.
- **Statut commercial actuel** : NON CONTACTÉ — vérification d'éligibilité et inscription au fichier requises (validation L5)

### OPP-24 — Organisations non gouvernementales mettant en œuvre des programmes financés par l'Union européenne et des bailleurs bilatéraux

- **ID de l'opportunité** : OPP-24
- **Organisation / projet** : Organisations non gouvernementales mettant en œuvre des programmes financés par l'Union européenne et des bailleurs bilatéraux
- **Pays ou zone** : Afrique, Asie, Amérique latine - multi-pays
- **Secteur** : Financement international - conformité et contrôle
- **Score opportunité** : 61.8/100
- **Score DARKINT** : 67.5/100
- **Priorité** : OPPORTUNITÉ EXPLOITABLE
- **Problème détecté** : Les projets financés exigent un dispositif de contrôle interne à la hauteur des exigences des bailleurs : procédures d'engagement de dépenses, contrôle des pièces, suivi des marchés, vérification des dépenses avant déclaration, gestion des avances aux partenaires, suivi des recommandations d'audit. Les équipes locales sont souvent incomplètes et les audits bailleurs sanctionnent les mêmes faiblesses chaque année.
- **Éléments factuels ayant conduit à identifier le besoin** :
  - Les projets financés exigent un dispositif de contrôle interne à la hauteur des exigences des bailleurs : engagement des dépenses, contrôle des pièces, suivi des marchés, vérification avant déclaration (sources S22 et S27).
  - Les faiblesses constatées portent sur les justificatifs, les procédures d'engagement et le suivi des recommandations d'audit (source S22).
  - Les équipes locales sont souvent incomplètes, ce qui crée un besoin d'appui externe ponctuel (source S27).
  - Les procédures d'achat des organisations non gouvernementales permettent fréquemment une contractualisation de gré à gré pour des missions courtes (constat de recherche ouverte, à vérifier par organisation).
- **Niveau de confirmation de la source** : OBSERVÉ (constat récurrente des rapports d'audit ; besoin probable selon les organisations)
- **Source(s) avec URL** :
  - S27 — UN Women Home-Based Associate Consultant 2026 - Finance and Programme (Kenya, 6 mois, clos le 11/09/2026) (campuslifestyle.org, 2026-09-07) : https://campuslifestyle.org/2026/09/07/un-women-home-based-associate
  - S22 — Audit C2D2: le CTR lancé un appel à candidatures à Kinshasa (audit financier et comptable 2026-2028, RDC, clôture 16/10/2026) (congoquotidien.com / actualite.cd, 2026-09-15) : https://www.congoquotidien.com/2026/09/15/recrutement-consultant-audit-c2d2/
- **Date des sources** : 2026-09-15
- **Mission précise que Roch pourrait proposer** : Diagnostic flash du dispositif de contrôle interne d'un projet finance : cartographie des risques de non-conformite, revue des pièces justificatives, procédés d'engagement, suivi des recom- mandations d'audit, plan d'action à 90 jours.
- **Livrable proposé** : Rapport de diagnostic (10-15 pages) + cartographie des risques + plan d'action 90 jours + matrice de suivi des dépenses inéligibles potentielles.
- **Intervention solo** : OUI
- **Durée estimée** : 5-8
- **Charge estimée (heures / jours)** : 40–60 heures (5–8 jours)
- **Travail à distance** : PARTIEL (revue documentaire à distance possible)
- **Niveau de difficulté** : Moyenne
- **Compétences nécessaires** : Contrôle interne de projets, Conformité des dépenses de bailleurs, Cartographie des risques de non-conformité, Révision documentaire, Français et anglais
- **Besoin éventuel d'un partenaire** : NON
- **Personne ou fonction à contacter** : Directeur pays, responsable financier ou administratif, responsable des programmes
- **Nom du contact publiquement identifié** : Fonction : directeur pays, responsable financier ou administratif, responsable des programmes. Nom non publié dans ce rapport.
- **Canal de contact public disponible** : Réseaux d'assistance technique ; Appels à consultants publiés par les organisations internationales ; Plateformes d'offres
- **Raison pour laquelle cette organisation est une cible** : Besoins récurrents alignés sur le cycle de projet et le cycle d'audit, seuils de contractualisation compatibles avec des missions courtes, et travail largement réalisable à distance sur revue documentaire.
- **Besoin** : PROBABLE (faiblesses récurrentes dans les rapports d'audit des programmes financés)
- **Potentiel** : récurrent (cycle de projet et cycle d'audit)
- **Ordre de grandeur d'honoraires envisageable** : Forfait 6–11 k€ pour 5–8 jours — estimation indicative ; suivi trimestriel récurrent envisageable
- **Prochaine action recommandée** : Cibler les ONG internationales avec des projets financés en Afrique francophone, proposer un diagnostic de 5 jours à distance. Validation L5 avant envoi.
- **Statut commercial actuel** : NON CONTACTÉ — validation L5 requise

### OPP-11 — DAO en cours de structuration juridique (DUNA Wyoming, Harmony Framework)

- **ID de l'opportunité** : OPP-11
- **Organisation / projet** : DAO en cours de structuration juridique (DUNA Wyoming, Harmony Framework)
- **Pays ou zone** : États-Unis / international - États-Unis (Wyoming) et equivalents
- **Secteur** : Structuration juridique et financière DAO
- **Score opportunité** : 60.2/100
- **Score DARKINT** : 66.0/100
- **Priorité** : OPPORTUNITÉ EXPLOITABLE
- **Problème détecté** : L'adoption de structures juridiques (Wyoming DUNA, Harmony Framework de février 2025) fait naitre des obligations financières et de gouvernance (comptes, administration, information des membres) que les DAO n'ont pas les moyens internes de tenir.
- **Éléments factuels ayant conduit à identifier le besoin** :
  - L'adoption de structures juridiques dédiées aux organisations décentralisées (cadre du Wyoming, cadre Harmony de février 2025) crée des obligations financières et de gouvernance nouvelles (source S12, 12/03/2026).
  - Ces structures exigent comptes, administration et information des membres, fonctions que les organisations concernées n'ont pas en interne (source S12).
  - Le marché du conseil juridique spécialisé est actif, sans offre structurée sur la partie finance, comptabilité et contrôles (constat de recherche ouverte).
  - La demande porte sur l'articulation entre entité juridique et exécution on-chain, sujet peu traité par les cabinets généralistes.
- **Niveau de confirmation de la source** : PROBABLE (causes documentées, besoin non exprimé par une organisation identifiée)
- **Source(s) avec URL** :
  - S12 — How DAOs Failed to Deliver on Their Original Promise (participation <10%, top 10% détient 76,2% du pouvoir de vote, Compound 2024) (medium / lopetaku, 2026-03-12) : https://lopetaku.medium.com/dao-governance-failures-whales-low-turnout-attacks-d1375c556384
- **Date des sources** : 2026-03-12
- **Mission précise que Roch pourrait proposer** : Mise en place de la fonction finance et gouvernance post-structuration : plan de comptes, calendrier de reporting, contrôles minimaux, articulation entre entité juridique et exécution on-chain.
- **Livrable proposé** : Manuel de procédures finance/gouvernance + calendrier de reporting + plan de comptes + contrôles minimaux.
- **Intervention solo** : PARTIEL
- **Durée estimée** : 6-10
- **Charge estimée (heures / jours)** : 45–70 heures (6–10 jours) avec partenaire juridique
- **Travail à distance** : OUI
- **Niveau de difficulté** : Moyenne à élevée
- **Compétences nécessaires** : Mise en place de fonction finance, Procédures et contrôles minimaux, Reporting aux membres, Articulation juridique/on-chain, Anglais juridique opérationnel
- **Besoin éventuel d'un partenaire** : OUI (Avocat spécialisé structures DAO (Wyoming / UE))
- **Personne ou fonction à contacter** : Fondation, conseil d'administration de l'entité, conseil juridique
- **Nom du contact publiquement identifié** : Fonction : fondation, conseil d'administration de l'entité, conseil juridique. Nom non publié dans ce rapport.
- **Canal de contact public disponible** : Cabinets juridiques spécialisés structuration d'organisations décentralisées ; Forums de gouvernance
- **Raison pour laquelle cette organisation est une cible** : Besoin de jonction entre droit, finance et exécution on-chain : positionnement complémentaire des cabinets juridiques, qui peuvent devenir apporteurs d'affaires plutôt que concurrents.
- **Besoin** : PROBABLE (cadre juridique documenté ; besoin non exprimé par une organisation identifiée)
- **Potentiel** : Ponctuel
- **Ordre de grandeur d'honoraires envisageable** : Mission 8–15 k€ (quote-part conseil finance) — estimation indicative, à valider ; forte dépendance au partenaire juridique
- **Prochaine action recommandée** : Identifier 5 cabinets spécialisés structuration DAO et proposer un partenariat d'apport mutuel. Validation L5 avant prise de contact.
- **Statut commercial actuel** : NON CONTACTÉ — aucun partenaire juridique approché à ce stade (validation L5)

### OPP-20 — CTR / C2D2 (projets financés par l'AFD en République démocratique du Congo)

- **ID de l'opportunité** : OPP-20
- **Organisation / projet** : CTR / C2D2 (projets financés par l'AFD en République démocratique du Congo)
- **Pays ou zone** : Afrique centrale - République démocratique du Congo
- **Secteur** : Financement international - audit de projets
- **Score opportunité** : 59.1/100
- **Score DARKINT** : 89.5/100
- **Priorité** : OPPORTUNITÉ EXPLOITABLE
- **Problème détecté** : Appel à manifestation d'intérêt publié le 15/09/2026 pour l'audit financier et comptable des comptes de plusieurs projets AFD sur les exercices 2026 à 2028 (FEP, PILAEP3, PREACE, formation professionnelle, gouvernance financière et administrative). Clôture le 16/10/2026 à 16 h (TU+1).
- **Éléments factuels ayant conduit à identifier le besoin** :
  - Appel publié le 15/09/2026 pour l'audit financier et comptable de projets financés par l'agence française de développement sur les exercices 2026 à 2028 (source S22, 15/09/2026).
  - Projets concernés : fonds d'études et de pilotage, PILAEP3, PREACE, formation professionnelle, gouvernance financière et administrative (source S22).
  - Exigences : cabinet de réputation internationale, membre d'un ordre reconnu et de l'ordre national congolais, dix ans d'expérience, références supérieures ou égales à 200 k€ par an, expérience en RDC ou en Afrique centrale (source S22).
  - Sélection en deux étapes avec liste restreinte d'au moins six candidats, puis proposition technique et financière (source S22).
- **Niveau de confirmation de la source** : EXPRIMÉ (appel public)
- **Source(s) avec URL** :
  - S22 — Audit C2D2: le CTR lancé un appel à candidatures à Kinshasa (audit financier et comptable 2026-2028, RDC, clôture 16/10/2026) (congoquotidien.com / actualite.cd, 2026-09-15) : https://www.congoquotidien.com/2026/09/15/recrutement-consultant-audit-c2d2/
- **Date des sources** : 2026-09-15
- **Mission précise que Roch pourrait proposer** : Audit financier et comptable pluriannuel des projets. Réserve : le dossier exige un cabinet d'audit et d'expertise comptable de réputation internationale, membre de l'ordre national congolais, dix ans d'expérience, références supérieures ou égales à 200 000 EUR par an et expérience en RDC ou en Afrique centrale.
- **Livrable proposé** : Rapports d'audit annuels sur les comptes des projets et lettres de recommandations (à l'interne : apport d'expertise finance et contrôle interne à un groupement).
- **Intervention solo** : NON
- **Durée estimée** : Mission pluriannuelle (3 exercices)
- **Charge estimée (heures / jours)** : Variable selon l'exercice audité ; apport d'expertise estimé à 15–30 jours par exercice
- **Travail à distance** : PARTIEL
- **Niveau de difficulté** : Élevée
- **Compétences nécessaires** : Contrôle interne de projets financés, Suivi financier et reporting bailleurs, Connaissance des procédures de l'agence, Français professionnel, Capacité à travailler en groupement
- **Besoin éventuel d'un partenaire** : OUI (obligatoire) (Cabinet d'audit membre IFAC/FIDEF et de l'ordre congolais, disponible pour un groupement)
- **Personne ou fonction à contacter** : Cellule de passation des marchés du CTR, coordination des projets
- **Nom du contact publiquement identifié** : Fonction : cellule de passation des marchés et coordination des projets. Nom de personne non publié dans ce rapport.
- **Canal de contact public disponible** : Avis public et dossier d'appel (source S22) ; Dépôt auprès de la cellule de passation à Kinshasa
- **Raison pour laquelle cette organisation est une cible** : Marché pluriannuel solvable et daté, accessible en apport d'expertise dans un groupement plutôt qu'en candidature directe : la contrainte d'éligibilité est contournable par partenariat.
- **Besoin** : EXPLICITEMENT EXPRIMÉ (appel à manifestation d'intérêt public, clôture le 16/10/2026 à 16 h TU+1)
- **Potentiel** : récurrent sur 2026-2028
- **Ordre de grandeur d'honoraires envisageable** : Marché pluriannuel de plus de 200 k€ par an pour le titulaire ; quote-part d'expert conseil à négocier (ordre de grandeur 15–30 k€ par an) — estimation indicative
- **Prochaine action recommandée** : Identifier 3 cabinets éligibles et proposer un apport d'expertise finance/contrôle interne dans un groupement, avant le 16/10/2026. Validation L5 avant prise de contact.
- **Statut commercial actuel** : NON CONTACTÉ — 3 cabinets éligibles à identifier avant le 16/10/2026 (validation L5 avant toute prise de contact)

### OPP-23 — UN Women - consultance finance et programme à distance (Kenya, financement Union européenne)

- **ID de l'opportunité** : OPP-23
- **Organisation / projet** : UN Women - consultance finance et programme à distance (Kenya, financement Union européenne)
- **Pays ou zone** : Afrique de l'Est - Kenya (télétravail)
- **Secteur** : Organisations internationales - gestion financière de programme
- **Score opportunité** : 57.4/100
- **Score DARKINT** : 69.0/100
- **Priorité** : OPPORTUNITÉ EXPLOITABLE
- **Problème détecté** : Besoin exprimé : consultance de 6 mois à distance pour l'appui financier d'un programme finance par l'Union européenne (revue de transactions, contrôle des procédures, suivi des recommandations d'audit, appui budgétaire, système QUANTUM). L'avis est clos depuis le 11/09/2026 : le besoin est récurrent et le canal reste actif.
- **Éléments factuels ayant conduit à identifier le besoin** :
  - Avis publié le 31/08/2026 pour une consultance de six mois à distance en appui financier d'un programme financé par l'Union européenne, clos le 11/09/2026 (source S27).
  - Missions : revue de conformité des transactions, contrôle des procédures, suivi des recommandations d'audit, appui budgétaire, saisie dans le système de gestion (source S27).
  - Le poste est supervisé par un spécialiste de la gestion des programmes, avec supervision matricielle d'un coordinateur régional (source S27).
  - Des avis de même nature sont publiés plusieurs fois par an par les agences des Nations unies (source S27).
- **Niveau de confirmation de la source** : EXPRIMÉ (avis public, échéance dépassée)
- **Source(s) avec URL** :
  - S27 — UN Women Home-Based Associate Consultant 2026 - Finance and Programme (Kenya, 6 mois, clos le 11/09/2026) (campuslifestyle.org, 2026-09-07) : https://campuslifestyle.org/2026/09/07/un-women-home-based-associate
- **Date des sources** : 2026-09-11
- **Mission précise que Roch pourrait proposer** : Appui financier de programme : revue de conformité des transactions, suivi budgétaire, appui au reporting, suivi des recommandations d'audit.
- **Livrable proposé** : Revues de transactions, états de suivi budgétaire, mise à jour du plan d'action d'audit.- **Intervention solo** : OUI
- **Durée estimée** : 6 mois à temps plein (modèle)
- **Charge estimée (heures / jours)** : 6 mois à temps plein pour le modèle observé
- **Travail à distance** : OUI
- **Niveau de difficulté** : Faible à moyenne
- **Compétences nécessaires** : Gestion financière de programmes, Conformité des dépenses de bailleurs, Suivi budgétaire, Suivi des recommandations d'audit, Anglais professionnel
- **Besoin éventuel d'un partenaire** : NON
- **Personne ou fonction à contacter** : spécialiste de la gestion des programmes (superviseur), coordinateur régional
- **Nom du contact publiquement identifié** : Fonction : spécialiste de la gestion des programmes (superviseur), coordinateur régional. Nom non publié dans ce rapport.
- **Canal de contact public disponible** : Portails de recrutement des agences des Nations unies (source S27) ; Veille quotidienne des avis de consultance à distance
- **Raison pour laquelle cette organisation est une cible** : Le besoin est structurel et le canal est éprouvé : au-delà de cet avis clos, une veille systématique des avis de consultance finance à distance permet de capter les prochaines occurrences.
- **Besoin** : EXPLICITEMENT EXPRIMÉ (avis public clos le 11/09/2026 ; besoin récurrent)
- **Potentiel** : récurrent (avis de même nature plusieurs fois par an)
- **Ordre de grandeur d'honoraires envisageable** : Selon grille de l'agence, ordre de grandeur 4 000–7 000 € par mois — estimation indicative, à confirmer
- **Prochaine action recommandée** : Ne pas poursuivre cet avis (clos). Mettre en place une veille automatisee des avis de consultance finance à distance (UN Women, UNFPA, PNUD, UNICEF) avec alerte. Validation L5 avant candidature.
- **Statut commercial actuel** : NON CONTACTÉ — avis clos : positionner une veille automatique (validation L5 avant toute candidature)

## 3. MISSIONS SOLO PRIORITAIRES

Classement des missions les plus adaptées à une intervention de Roch seul. Les autres missions restent listées à la section 2 ; aucune n'est supprimée.

Format de référence (une ligne par mission) :

```
OPP-03 | Moonwell | Audit cible du processus de modification des paramètres d'oracle et de collatéraux (double validation, revu... | 82.2 | 3-5 | OUI | Responsable risque / fondation Moonwell ; multisig de gouvernance | Envoyer une note courte chiffrant le coût des deux incidents face au coût d'un contrôle trimestriel. Valida...
OPP-15 | Entités financières UE de taille intermédiaire et prestataires de services sur crypto-actifs (DORA art. 28-30) | Revue d'écart DORA troisième et quatrième partie : qualité du registre des accords TIC, examen des contrats... | 81.9 | 5-10 | OUI | Directeur conformité, DAF, responsable des risques, comité d'audit | Préparer une offre cadrée « registre des accords TIC et chaînes de sous-traitance » de 5 jours, en français...
OPP-01 | Kelp DAO | Revue post-incident, 8 jours maximum, de la couche contrôle interne: inventaire des modules et autorisation... | 81.1 | 5-8 | OUI | Fondation/core team Kelp DAO, responsable sécurité ou opérations, comité multisig de trésorerie | Préparer une note d'approche de 1 page (angle: contrôles de la couche autorisation, pas d'audit de code) et...
OPP-07 | Population cible : 24 DAO détenant des Safe avec modules actifs (trésorerie > 20 M$) | Offre productisée : « Inventaire et révocation des modules Safe » - recensement des modules et automatisati... | 80.5 | 2-4 par organisation | OUI | Multisig signataires, comité de trésorerie, responsable sécurité, cercles de délégués | Constituer la liste des 24 cibles avec le Safe concerne et le contact de gouvernance, puis campagne d'appro...
OPP-02 | Nostra Finance | Refonte du dispositif de contrôle des paramètres de marché et des oracles : politique d'activation des coll... | 80.0 | 4-6 | OUI | équipe fondatrice / responsable risque du protocole ; conseil de gouvernance | Proposer un diagnostic flash de 3 jours sur le change control oracle, à prix forfaitaire, livrable en 10 jo...
OPP-14 | Directions financières de sociétés détenant de la trésorerie crypto (sociétés de trésorerie d'actifs numériques, fintechs, e-money) | Revue de préparation à l'audit de la trésorerie crypto : chaîne d'approbation, séparation des rôles, invent... | 77.4 | 5-8 | OUI | DAF, contrôleur de gestion, comité d'audit, expert-comptable | Constituer la liste de 15 sociétés européennes détenant du bitcoin ou des stablecoins en trésorerie et prop...
OPP-16 | Cabinets d'expertise comptable et de paie de taille intermédiaire (Royaume-Uni, France, Benelux) | Revue des contrôles anti-fraude du cabinet et de ses clients : contrôle des changements de coordonnées banc... | 77.0 | 3-5 | OUI | Associé gérant, responsable qualité et risque, responsable informatique | Constituer une liste de 30 cabinets cibles au Royaume-Uni et en France, proposer un diagnostic de 3 jours. ...
OPP-10 | DAO de taille intermédiaire (trésorerie 10-50 M$) sans fonction finance structurée | Pack mensuel de reporting et de contrôle pour trésorerie DAO : états de trésorerie mensuels, réconciliation... | 76.7 | 5 jours de mise en place puis 0,5-1 jour par mois | OUI | trésorier, multisig signataires, cercle de délégués, fondation | Constituer une liste de 20 DAO cibles avec trésorerie dans la fourchette et absence de prestataire de repor...
OPP-13 | Fintech / edtech (recrutement publié, mandat d'approche par cabinet) | Direction financière fractionnaire : pilotage de la trésorerie, prévisionnel, reporting investisseurs, mise... | 73.2 | récurrent : 6-8 heures par semaine | OUI | Fondateur/CEO, CFO, responsable recrutement du cabinet mandataire | Vérifier l'éligibilité (statut de travail, monnaie, contrat international) avant dépôt ; visée en priorité ...
OPP-09 | DAO utilisant les modules de gouvernance Zodiac / Reality (SafeSnap) | Runbook d'exécution de gouvernance : inventaire des chemins d'exécution (votes, modules, automatisations), ... | 71.8 | 4-6 | OUI | comité de sécurité de la DAO, signataires, administrateurs du module | Écrire un guide public court (« ce que votre module de gouvernance peut faire sans vous ») et le diffuser c...
OPP-06 | Unlock DAO | Revue indépendante du dispositif de quorum et de délégation : analyse des conséquences (sécurité, légitimit... | 70.2 | 5-8 | OUI | Stewards, contributeurs actifs, délégués (leaderboard de participation) | Répondre au fil de discussion ouvert en proposant une analyse structurée des options et une offre de revue ...
OPP-17 | Entreprises de taille moyenne à forte intensité de paiements (immobilier, construction, santé, industrie) | Revue du processus de paiement et anti-usurpation : vérification des changements de coordonnées, autorisati... | 65.6 | 4-6 | OUI | DAF, responsable comptabilité, directeur des systèmes d'information | Cibler les secteurs à paiement sensible (immobilier, construction) et passer par les courtiers d'assurance ...
OPP-22 | UNFPA - roster de consultants finance (branche finance du siège) | Consultances courtes : opérations financières IPSAS, reporting bailleurs, comptabilité et contrôle des stoc... | 65.4 | Affectations courtes répétées | OUI | Chef d'unite de la branche finance, chef comptes, chef de la branche finance | Actualiser le dossier de candidature (IPSAS, reporting bailleurs, transferts de fonds) et candidater au ros...
OPP-18 | Prestataires de services sur crypto-actifs et fintechs en cours d'agrément (MiCA, DORA) | Appui conformité et contrôle interne à temps partagé : cartographie des risques, procédures, plan de contrô... | 63.8 | récurrent : 1-3 jours par mois | OUI | Dirigeant, responsable conformité, conseil d'administration | Identifier 12 fintechs et prestataires crypto en phase d'agrément ou de post-agrement en France. Validation...
OPP-21 | Banque africaine de développement (BAD) - consultant individuel via DACON et avis à manifestation d'intérêt | Missions d'assistance technique et de contrôle financier : appui au suivi financier de projets, revue des d... | 62.5 | Missions de 6 à 12 semaines | OUI | Départements sectoriels de la BAD, comité de recrutement et de supervision des consultants, unités d'exécution des projets emprunteurs | Vérifier l'éligibilité (nationalité d'un pays membre, diplôme, dix ans d'expérience), s'inscrire à DACON et...
OPP-24 | Organisations non gouvernementales mettant en œuvre des programmes financés par l'Union européenne et des bailleurs bilatéraux | Diagnostic flash du dispositif de contrôle interne d'un projet finance : cartographie des risques de non-co... | 61.8 | 5-8 | OUI | Directeur pays, responsable financier ou administratif, responsable des programmes | Cibler les ONG internationales avec des projets financés en Afrique francophone, proposer un diagnostic de ...
OPP-23 | UN Women - consultance finance et programme à distance (Kenya, financement Union européenne) | Appui financier de programme : revue de conformité des transactions, suivi budgétaire, appui au reporting, ... | 57.4 | 6 mois à temps plein (modèle) | OUI | spécialiste de la gestion des programmes (superviseur), coordinateur régional | Ne pas poursuivre cet avis (clos). Mettre en place une veille automatisee des avis de consultance finance à...
```

| ID | Organisation | Score | Mission | Durée | Solo | Contact cible | Action suivante |
|---|---|---|---|---|---|---|---|
| OPP-03 | Moonwell | 82.2 | Audit cible du processus de modification des paramètres d'oracle et de collatéraux (double validation, revue croisée, tests de non-régression sur les feeds, plafonds dynamiques, alertes) et mise en place d'un registre des changements. | 3-5 | OUI | Responsable risque / fondation Moonwell ; multisig de gouvernance | Envoyer une note courte chiffrant le coût des deux incidents face au coût d'un contrôle trimestriel. Validation L5 avant envoi. |
| OPP-15 | Entités financières UE de taille intermédiaire et prestataires de services sur crypto-actifs (DORA art. 28-30) | 81.9 | Revue d'écart DORA troisième et quatrième partie : qualité du registre des accords TIC, examen des contrats critiques, cartographie des chaînes de sous-traitance, analyse de concentration, plans de sortie, gouvernance et reporting annuel. | 5-10 | OUI | Directeur conformité, DAF, responsable des risques, comité d'audit | Préparer une offre cadrée « registre des accords TIC et chaînes de sous-traitance » de 5 jours, en français et en anglais. Validation L5 avant démarchage. |
| OPP-01 | Kelp DAO | 81.1 | Revue post-incident, 8 jours maximum, de la couche contrôle interne: inventaire des modules et autorisations actives, politique de révocation, règle de confirmation multi-signataires pour l'installation de modules, revue du modèle de confiance du pont (vérificateur unique) et plan de remédiation priorise. | 5-8 | OUI | Fondation/core team Kelp DAO, responsable sécurité ou opérations, comité multisig de trésorerie | Préparer une note d'approche de 1 page (angle: contrôles de la couche autorisation, pas d'audit de code) et demander un échange de 30 minutes. Validation L5 avant envoi. |
| OPP-07 | Population cible : 24 DAO détenant des Safe avec modules actifs (trésorerie > 20 M$) | 80.5 | Offre productisée : « Inventaire et révocation des modules Safe » - recensement des modules et automatisations attachés aux Safe de trésorerie, analyse du périmètre d'autorisation de chacun, identification des modules dormants ou non revus, recommandations de révocation et politique d'installation (qui approuve, quel délai, quelle revue). | 2-4 par organisation | OUI | Multisig signataires, comité de trésorerie, responsable sécurité, cercles de délégués | Constituer la liste des 24 cibles avec le Safe concerne et le contact de gouvernance, puis campagne d'approche par cohorte. Validation L5 avant tout envoi. |
| OPP-02 | Nostra Finance | 80.0 | Refonte du dispositif de contrôle des paramètres de marché et des oracles : politique d'activation des collatéraux, plafonds, oracle de repli, seuils d'alerte, revue croisée avant tout changement de paramètre, journal des changements, tests de liquidation. | 4-6 | OUI | équipe fondatrice / responsable risque du protocole ; conseil de gouvernance | Proposer un diagnostic flash de 3 jours sur le change control oracle, à prix forfaitaire, livrable en 10 jours. Validation L5 avant envoi. |
| OPP-14 | Directions financières de sociétés détenant de la trésorerie crypto (sociétés de trésorerie d'actifs numériques, fintechs, e-money) | 77.4 | Revue de préparation à l'audit de la trésorerie crypto : chaîne d'approbation, séparation des rôles, inventaire des portefeuilles et seuils, rapprochement des écritures, preuves horodatées, dossier de justification pour l'auditeur et le conseil d'administration. | 5-8 | OUI | DAF, contrôleur de gestion, comité d'audit, expert-comptable | Constituer la liste de 15 sociétés européennes détenant du bitcoin ou des stablecoins en trésorerie et proposer un diagnostic de 5 jours. Validation L5 avant envoi. |
| OPP-16 | Cabinets d'expertise comptable et de paie de taille intermédiaire (Royaume-Uni, France, Benelux) | 77.0 | Revue des contrôles anti-fraude du cabinet et de ses clients : contrôle des changements de coordonnées bancaires, vérification par canal indépendant, double approbation, surveillance des boites mail, procédure d'incident et de déclaration, formation des équipes. | 3-5 | OUI | Associé gérant, responsable qualité et risque, responsable informatique | Constituer une liste de 30 cabinets cibles au Royaume-Uni et en France, proposer un diagnostic de 3 jours. Validation L5 avant envoi. |
| OPP-10 | DAO de taille intermédiaire (trésorerie 10-50 M$) sans fonction finance structurée | 76.7 | Pack mensuel de reporting et de contrôle pour trésorerie DAO : états de trésorerie mensuels, réconciliation on-chain, journal des décisions de gouvernance rattachees aux mouvements, indicateurs de risque (concentration, liquidité, runway en stablecoins), seuils d'approbation par taille de transaction. | 5 jours de mise en place puis 0,5-1 jour par mois | OUI | trésorier, multisig signataires, cercle de délégués, fondation | Constituer une liste de 20 DAO cibles avec trésorerie dans la fourchette et absence de prestataire de reporting ; proposer un mois pilote. Validation L5 avant envoi. |
| OPP-13 | Fintech / edtech (recrutement publié, mandat d'approche par cabinet) | 73.2 | Direction financière fractionnaire : pilotage de la trésorerie, prévisionnel, reporting investisseurs, mise en place de contrôles, due diligence finance. | récurrent : 6-8 heures par semaine | OUI | Fondateur/CEO, CFO, responsable recrutement du cabinet mandataire | Vérifier l'éligibilité (statut de travail, monnaie, contrat international) avant dépôt ; visée en priorité des mandats UE/UK. Validation L5 avant candidature. |
| OPP-09 | DAO utilisant les modules de gouvernance Zodiac / Reality (SafeSnap) | 71.8 | Runbook d'exécution de gouvernance : inventaire des chemins d'exécution (votes, modules, automatisations), qui doit surveiller quoi et quand, fenêtres de veto, astreinte et escalade, tests trimestriels d'un scénario d'attaque, journal des exécutions. | 4-6 | OUI | comité de sécurité de la DAO, signataires, administrateurs du module | Écrire un guide public court (« ce que votre module de gouvernance peut faire sans vous ») et le diffuser comme outil d'entree. Validation L5 avant publication. |
| OPP-06 | Unlock DAO | 70.2 | Revue indépendante du dispositif de quorum et de délégation : analyse des conséquences (sécurité, légitimité, risque de capture), cadre de délégation depuis la trésorerie, garde-fous d'exécution, politique de quorum cible et mécanisme de délégation dynamique. | 5-8 | OUI | Stewards, contributeurs actifs, délégués (leaderboard de participation) | Répondre au fil de discussion ouvert en proposant une analyse structurée des options et une offre de revue de 5 jours. Validation L5 avant envoi. |
| OPP-17 | Entreprises de taille moyenne à forte intensité de paiements (immobilier, construction, santé, industrie) | 65.6 | Revue du processus de paiement et anti-usurpation : vérification des changements de coordonnées, autorisations, seuils, gestion des fournisseurs, détection des règles de transfert automatique, plan de reaction et récupération des fonds, formation des équipes comptables. | 4-6 | OUI | DAF, responsable comptabilité, directeur des systèmes d'information | Cibler les secteurs à paiement sensible (immobilier, construction) et passer par les courtiers d'assurance comme canal. Validation L5 avant démarchage. |
| OPP-22 | UNFPA - roster de consultants finance (branche finance du siège) | 65.4 | Consultances courtes : opérations financières IPSAS, reporting bailleurs, comptabilité et contrôle des stocks, transferts de fonds et réconciliation des avances aux partenaires de mise en œuvre. | Affectations courtes répétées | OUI | Chef d'unite de la branche finance, chef comptes, chef de la branche finance | Actualiser le dossier de candidature (IPSAS, reporting bailleurs, transferts de fonds) et candidater au roster. Validation L5 avant dépôt. |
| OPP-18 | Prestataires de services sur crypto-actifs et fintechs en cours d'agrément (MiCA, DORA) | 63.8 | Appui conformité et contrôle interne à temps partagé : cartographie des risques, procédures, plan de contrôle annuel, préparation des revues du superviseur. | récurrent : 1-3 jours par mois | OUI | Dirigeant, responsable conformité, conseil d'administration | Identifier 12 fintechs et prestataires crypto en phase d'agrément ou de post-agrement en France. Validation L5 avant envoi. |
| OPP-21 | Banque africaine de développement (BAD) - consultant individuel via DACON et avis à manifestation d'intérêt | 62.5 | Missions d'assistance technique et de contrôle financier : appui au suivi financier de projets, revue des dispositifs de contrôle interne, rapports financiers, appui à la mise en place de procédures. | Missions de 6 à 12 semaines | OUI | Départements sectoriels de la BAD, comité de recrutement et de supervision des consultants, unités d'exécution des projets emprunteurs | Vérifier l'éligibilité (nationalité d'un pays membre, diplôme, dix ans d'expérience), s'inscrire à DACON et préparer une fiche d'identification standard. Validation L5 avant inscription. |
| OPP-24 | Organisations non gouvernementales mettant en œuvre des programmes financés par l'Union européenne et des bailleurs bilatéraux | 61.8 | Diagnostic flash du dispositif de contrôle interne d'un projet finance : cartographie des risques de non-conformite, revue des pièces justificatives, procédés d'engagement, suivi des recom- mandations d'audit, plan d'action à 90 jours. | 5-8 | OUI | Directeur pays, responsable financier ou administratif, responsable des programmes | Cibler les ONG internationales avec des projets financés en Afrique francophone, proposer un diagnostic de 5 jours à distance. Validation L5 avant envoi. |
| OPP-23 | UN Women - consultance finance et programme à distance (Kenya, financement Union européenne) | 57.4 | Appui financier de programme : revue de conformité des transactions, suivi budgétaire, appui au reporting, suivi des recommandations d'audit. | 6 mois à temps plein (modèle) | OUI | spécialiste de la gestion des programmes (superviseur), coordinateur régional | Ne pas poursuivre cet avis (clos). Mettre en place une veille automatisee des avis de consultance finance à distance (UN Women, UNFPA, PNUD, UNICEF) avec alerte. Validation L5 avant candidature. |

## 4. MISSIONS À CONTACTER MAINTENANT

Information préparée pour validation L5. **Aucun contact n'a été envoyé.**

### OPP-03 — Moonwell

- **Pourquoi agir maintenant** : Deux incidents sur le même processus en six mois : le coût des pertes dépasse largement le coût d'un contrôle trimestriel, argument économique immédiat et vérifiable.
- **Qui contacter** : Responsable risque / fondation Moonwell ; multisig de gouvernance
- **Sur quel sujet** : Deuxième défaillance oracle en 6 mois. 15/02/2026 : erreur de configuration (taux cbETH/ETH non multiplié par ETH/USD) ayant entraîné 1,8 M$ de bad debt et des liquidations à un prix plusieurs milliers de fois trop bas. 27/08/2026 : manipulation du prix MAMO (~9 M$). Cause récurrente : contrôle des changements de configuration insuffisant, pas de revue croisée.
- **Avec quelle proposition de mission** : Audit cible du processus de modification des paramètres d'oracle et de collatéraux (double validation, revue croisée, tests de non-régression sur les feeds, plafonds dynamiques, alertes) et mise en place d'un registre des changements.
- **Livrable** : Rapport d'audit cible (8-12 pages) + registre des changements + matrice de validation des paramètres + 5 contrôles clés opérationnels.
- **Honoraires (ordre de grandeur)** : Forfait 4–7 k€ pour 3–5 jours — estimation indicative ; prestation récurrente trimestrielle envisageable
- **Statut commercial** : NON CONTACTÉ — validation L5 requise
- **Envoi autorisé** : NON — validation L5 requise avant tout envoi

### OPP-15 — Entités financières UE de taille intermédiaire et prestataires de services sur crypto-actifs (DORA art. 28-30)

- **Pourquoi agir maintenant** : Obligation légale avec échéance annuelle, budget existant, et un livrable parfaitement standardisable (registre + écarts + clauses manquantes). C'est la niche la plus industrialisable du registre, en français comme en anglais.
- **Qui contacter** : Directeur conformité, DAF, responsable des risques, comité d'audit
- **Sur quel sujet** : DORA s'applique depuis le 17/01/2025 : registre des accords contractuels TIC, évaluation avant conclusion, analyse de concentration, cartographie des sous-traitants en chaîne (4e partie), clauses minimales et étendues, plan de sortie documenté, reporting annuel. Les entités de taille intermédiaire (sociétés de gestion, prestataires de paiement, e-money, prestataires crypto) ont souvent un dispositif incomplet et la responsabilité reste entièrement la leur, y compris quand le prestataire est conforme.
- **Avec quelle proposition de mission** : Revue d'écart DORA troisième et quatrième partie : qualité du registre des accords TIC, examen des contrats critiques, cartographie des chaînes de sous-traitance, analyse de concentration, plans de sortie, gouvernance et reporting annuel.
- **Livrable** : Registre des informations fiabilisé + rapport d'écart + clauses contractuelles manquantes + plan de sortie type + dossier de gouvernance.
- **Honoraires (ordre de grandeur)** : Forfait 8–14 k€ pour 5–10 jours — estimation indicative ; mise à jour annuelle du registre récurrente (3–5 k€)
- **Statut commercial** : NON CONTACTÉ — validation L5 requise avant démarche
- **Envoi autorisé** : NON — validation L5 requise avant tout envoi

### OPP-01 — Kelp DAO

- **Pourquoi agir maintenant** : Incident public très récent touchant directement la couche autorisation : la fenêtre d'approche est ouverte 30 à 60 jours, et la direction doit pouvoir documenter ses contrôles d'autorisation auprès de sa communauté, de ses intégrateurs et des venues qui acceptent ses actifs.
- **Qui contacter** : Fondation/core team Kelp DAO, responsable sécurité ou opérations, comité multisig de trésorerie
- **Sur quel sujet** : Exploitation le 15/09/2026 d'un module personnalisé autorisé par l'utilisateur sur un Safe (poste rsETH/aEthrsETH, hook Uniswap v4) après le drain de 292 M$ du bridge rsETH en avril 2026. Le composant tiers autorisé élargit la frontière de confiance du wallet ; aucun inventaire ni révocation systématique des modules n'existe.
- **Avec quelle proposition de mission** : Revue post-incident, 8 jours maximum, de la couche contrôle interne: inventaire des modules et autorisations actives, politique de révocation, règle de confirmation multi-signataires pour l'installation de modules, revue du modèle de confiance du pont (vérificateur unique) et plan de remédiation priorise.
- **Livrable** : Rapport de revue de contrôle interne (15-25 pages) + inventaire des autorisations + politique d'installation/révocation des modules + plan de remédiation 30/60/90 jours + note de synthèse pour la gouvernance.
- **Honoraires (ordre de grandeur)** : Forfait 7–12 k€ pour 5–8 jours — estimation indicative, à valider
- **Statut commercial** : NON CONTACTÉ — validation L5 requise
- **Envoi autorisé** : NON — validation L5 requise avant tout envoi

### OPP-07 — Population cible : 24 DAO détenant des Safe avec modules actifs (trésorerie > 20 M$)

- **Pourquoi agir maintenant** : Problème systémique documenté à quatre reprises, offre standardisable en 2 à 4 jours par organisation, décision prise directement par les signataires : un seul modèle de prestation peut être vendu à une cohorte de DAO.
- **Qui contacter** : Multisig signataires, comité de trésorerie, responsable sécurité, cercles de délégués
- **Sur quel sujet** : Problème structurel : tout module attaché à un Safe peut exécuter des transactions sans confirmation des propriétaires. Aucune des DAO ciblées ne publie d'inventaire de ses modules ni de politique de révocation. L'incident rsETH du 15/09/2026 et le cas SuDAO (2022) démontrent le même mode de défaillance à 4 ans d'intervalle.
- **Avec quelle proposition de mission** : Offre productisée : « Inventaire et révocation des modules Safe » - recensement des modules et automatisations attachés aux Safe de trésorerie, analyse du périmètre d'autorisation de chacun, identification des modules dormants ou non revus, recommandations de révocation et politique d'installation (qui approuve, quel délai, quelle revue).
- **Livrable** : Inventaire des modules + fiche d'autorisation par module + recommandations de révocation + politique d'installation et de revue + déclaration d'intégrité pour la gouvernance.
- **Honoraires (ordre de grandeur)** : Forfait 3–5 k€ par DAO pour 2–4 jours — estimation indicative ; revue récurrente trimestrielle ou semestrielle facturable séparément
- **Statut commercial** : NON CONTACTÉ — liste de 24 cibles à confirmer par analyse on-chain avant toute approche (validation L5)
- **Envoi autorisé** : NON — validation L5 requise avant tout envoi

### OPP-02 — Nostra Finance

- **Pourquoi agir maintenant** : Deuxième incident oracle en dix-huit mois : le besoin de contrôle des paramètres de marché et des feeds est démontré, et la direction vient de perdre la confiance d'une partie de ses utilisateurs. La remédiation documentée devient un enjeu de survie du marché.
- **Qui contacter** : équipe fondatrice / responsable risque du protocole ; conseil de gouvernance
- **Sur quel sujet** : Second incident oracle en 18 mois. Le 17/09/2026 un prix NSTR manipulé à permis à un seul compte d'emprunter ~3,5 M$ contre un collatéraux surévalué (5x la capitalisation du token). Marché en pause, réconciliation par pool en cours, aucun oracle de secours disponible pour ces actifs.
- **Avec quelle proposition de mission** : Refonte du dispositif de contrôle des paramètres de marché et des oracles : politique d'activation des collatéraux, plafonds, oracle de repli, seuils d'alerte, revue croisée avant tout changement de paramètre, journal des changements, tests de liquidation.
- **Livrable** : Cadre de contrôle oracle et collatéraux (framework) + checklist de change control + tableau de bord de suivi + note de gouvernance pour validation DAO.
- **Honoraires (ordre de grandeur)** : Forfait 5–9 k€ pour 4–6 jours — estimation indicative, à valider
- **Statut commercial** : NON CONTACTÉ — validation L5 requise
- **Envoi autorisé** : NON — validation L5 requise avant tout envoi

### OPP-08 — Aave (et marchés de prêt acceptant des LST pontés)

- **Pourquoi agir maintenant** : Le protocole est la première victime de contagion documentée : la thématique de concentration des dépendances est déjà dans son agenda, et une revue ciblée peut s'intégrer à un travail existant porté par les fournisseurs de risque.
- **Qui contacter** : Risk Council / service providers de risque du protocole, équipe croissance
- **Sur quel sujet** : Après le drain du bridge rsETH, environ 196 M$ de bad debt se sont concentrés sur une seule paire rsETH/wrapped-ether. Les venues de prêt acceptant ce collatéraux ne pouvaient pas voir que leur garantie reposait sur un pont à modèle de défaillance 1-sur-1 (vérificateur unique, 47% des applications LayerZero concernées selon les données de septembre 2026).
- **Avec quelle proposition de mission** : Revue du cadre d'admission des collatéraux : cartographie des dépendances (pont, vérificateur, oracle, émission), analyse de concentration, scénario de défaillance en cascade, limites d'exposition et plan de réduction progressive.
- **Livrable** : Matrice de dépendances des collatéraux + analyse de concentration + limites d'exposition proposées + plan de réduction progressive.
- **Honoraires (ordre de grandeur)** : Mission 9–15 k€ pour 6–10 jours — estimation indicative ; concurrence élevée sur ce segment, viser une niche (dépendances de rang 2 et 3)
- **Statut commercial** : NON CONTACTÉ — validation L5 requise
- **Envoi autorisé** : NON — validation L5 requise avant tout envoi

### OPP-04 — Drift Protocol

- **Pourquoi agir maintenant** : Le sinistre le plus documenté de 2026 sur l'abus d'autorité administrative : la direction a besoin de reconstruire un dispositif d'autorisations opposable, y compris vis-à-vis de ses investisseurs et partenaires de marché.
- **Qui contacter** : Security Council, fondation Drift, responsable sécurité
- **Sur quel sujet** : 285 M$ soustraits en 128 secondes (01/04/2026) : autorité pré-signée obtenue auprès du Security Council via un nonce durable (fonctionnalité native de Solana), token sans valeur accepte comme collatéraux, oracle contrôlé par l'attaquant, retraits massifs. Conflit d'intérêt signalé : les multisigs et l'infrastructure partagée entre protocoles concentrent le risque.
- **Avec quelle proposition de mission** : Cartographie des autorités administratives et de leurs modes d'approbation (qui peut faire quoi, avec quel délai), revue des autorisations pré-signées et des nonces durables, politique de clé, procédure de revue des collatéraux, plan de sortie de la dépendance à une entité de sécurité unique.
- **Livrable** : Cartographie des autorités + registre des autorisations pré-signées + politique de signature + plan de remédiation.
- **Honoraires (ordre de grandeur)** : Mission 12–20 k€ pour 8–12 jours — estimation indicative, à valider ; dossier à mener avec un partenaire technique
- **Statut commercial** : NON CONTACTÉ — validation L5 requise
- **Envoi autorisé** : NON — validation L5 requise avant tout envoi

## 5. NOUVELLES NICHES DÉTECTÉES

### NICHE-01 — Contrôle des modules et automatisations attachées aux portefeuilles multi-signatures

- **Problème récurrent** : Tout module attaché à un portefeuille Safe peut exécuter des transactions sans confirmation des propriétaires. Les organisations autorisent des modules pour automatiser des opérations puis ne revoient jamais ni l'inventaire ni les autorisations résiduelles.
- **Fréquence** : 4 épisodes documentés : SuDAO 2022 (56 k$), Cork 2025 (fun hook Uniswap v4), Bybit 2025 (infrastructure/interfaces), rsETH/Kelp 2026 (7,8 M$ sur un portefeuille utilisateur après un drain de 292 M$ sur le bridge).
- **Organisations déjà identifiées** : Kelp DAO ; 24 DAO avec Safe modulaires (trésorerie > 20 M$) - population à confirmer par analyse on-chain ; Protocoles utilisant des automatisations de gestion de position (hooks, keepers) ; Éditeurs des modules de gouvernance (Zodiac et assimilés) ; Sociétés de gestion crypto et trésoreries d'entreprise utilisant des portefeuilles multi-signatures
- **Nombre de cibles potentielles** : 5 (entrées listées dans le problème structurel rattaché ; détail en section 2)
- **Prestation standardisable** : Inventaire et révocation des modules (2-4 j) ; politique d'installation et de revue (inclus) ; revue trimestrielle récurrente ; formation des signataires.
- **Durée type** : 2 à 10 jours selon la cible (voir fiches)
- **Mission récurrente possible** : OUI
- **Compatibilité avec une intervention solo** : OUI
- **Secteurs concernés** : DeFi, trésorerie crypto, custody, infrastructure de gouvernance.
- **Causes communes** : Puissance des modules supérieure à celle des propriétaires ; absence d'inventaire et de cycle de révocation ; automatisation installée pour l'efficacité opérationnelle ; confiance implicite dans un composant tiers non audité.
- **Conséquences** : Perte directe de trésorerie, contagion vers les venues de prêt, perte de confiance, coût de remédiation et de communication d'incident.
- **Niveau de concurrence** : Élevée sur l'audit de code, faible sur la revue des contrôles d'autorisation, de la politique de signature et du cycle de révocation.
- **Potentiel de marché** : Élevé (24 organisations cibles identifiées dans le registre, mandat court et récurrent, décision prise par les signataires eux-mêmes).

### NICHE-02 — Maîtrise des changements de configuration des oracles et des paramètres de marché

- **Problème récurrent** : Des erreurs de configuration et des manipulations de prix provoquent des pertes répétées. Les changements de paramètres sont souvent effectués sans revue croisée, sans test de non-régression et sans oracle de repli.
- **Fréquence** : Au moins 7 épisodes en 12 mois : Moonwell 15/02/2026 (1,8 M$) puis 27/08/2026 (~9 M$), Silo 03/04/2026 (392 k$), Rhea 16/04/2026 (7,6 M$), Venus (3,7 M$), YieldBlox (11 M$), Nostra 17/09/2026 (3,5 M$).
- **Organisations déjà identifiées** : Moonwell (deux incidents en six mois) ; Nostra Finance (deux incidents oracle en dix-huit mois, marché en pause) ; Venues de prêt de taille moyenne (Euler, Silo, Fluid, Venus, YieldBlox) ; Protocoles acceptant des tokens à faible capitalisation en collatéraux
- **Nombre de cibles potentielles** : 4 (entrées listées dans le problème structurel rattaché ; détail en section 2)
- **Prestation standardisable** : Diagnostic flash de la configuration (3 j) ; audit du processus de changement ; ajout d'un oracle de repli ; plafonds et seuils d'alerte ; revue trimestrielle de configuration.
- **Durée type** : 2 à 10 jours selon la cible (voir fiches)
- **Mission récurrente possible** : OUI
- **Compatibilité avec une intervention solo** : OUI
- **Secteurs concernés** : DeFi (lending, derivatives, stablecoins), exchange, asset management tokenisé.
- **Causes communes** : Absence de processus de changement formalisé, absence de double validation, dépendance à un fournisseur d'oracle sans plan de repli, plafonds de collatéraux non ajustés, absence de surveillance des prix hors marché.
- **Conséquences** : Bad debt, liquidations erronées, suspensions de marché, pertes de revenus, contentieux communautaires, coût d'audit et de remédiation.
- **Niveau de concurrence** : Faible sur la couche processus et contrôle interne (les auditeurs de code ne traitent pas ce risque, les fournisseurs de risque sont partiellement concurrents).
- **Potentiel de marché** : Élevé (population large, budget disponible après incident, naturellement récurrent).

### NICHE-03 — Registre des dépendances de troisième et quatrième partie (trésorerie, marchés de prêt, entités financières)

- **Problème récurrent** : Double pression : le règlement européen sur la résilience opérationnelle imposé un registre des accords TIC, l'analyse de concentration et la cartographie des sous-traitants en chaîne ; en parallèle, la contagion d'avril 2026 à montre que 196 M$ de bad debt se sont concentrés sur une paire dont le collatéraux dépendait d'un pont à vérificateur unique.
- **Fréquence** : réglementaire et permanent (application depuis janvier 2025, reporting annuel) + épisodes de contagion 2026 (Kelp/rsETH, protocoles acceptant rsETH, 47% des applications LayerZero en vérificateur unique selon les données de septembre 2026).
- **Organisations déjà identifiées** : Marchés de prêt acceptant des actifs pontés ou tokenisés ; Applications LayerZero en configuration à vérificateur unique (population de 47%) ; Fournisseurs de risque des protocoles de prêt ; Preteurs et fonds exposant des garanties à des actifs tokenisés ; Sociétés de gestion et courtiers de taille intermédiaire ; Prestataires de paiement, établissements de monnaie électronique, prestataires sur crypto-actifs ; Mutuelles, institutions de prevoyance, courtiers d'assurance ; Fournisseurs TIC designes comme critiques (obligations remontées par leurs clients)
- **Nombre de cibles potentielles** : 8 (entrées listées dans le problème structurel rattaché ; détail en section 2)
- **Prestation standardisable** : Registre des informations fiabilisé (5-10 j) ; analyse de concentration ; clauses contractuelles manquantes ; plans de sortie ; mise à jour annuelle.
- **Durée type** : 2 à 10 jours selon la cible (voir fiches)
- **Mission récurrente possible** : A CONFIRMER
- **Compatibilité avec une intervention solo** : OUI
- **Secteurs concernés** : Finance réglementée, assurance, DeFi, trésorerie d'entreprise.
- **Causes communes** : Registres tenus de manière déclarative et non vérifiée, contrats signes sans clauses exigees, absence de vision sur les sous-traitants de rang 2 et 3, dépendances techniques tolérées par pragmatisme.
- **Conséquences** : réserves des superviseurs, sanctions, défaillance en cascade, impossibilité de mesurer une exposition concentrée, coût de sortie d'un fournisseur non testée.
- **Niveau de concurrence** : Élevée au niveau des grands cabinets, faible sur le segment des entités de taille intermédiaire et des venues DeFi.
- **Potentiel de marché** : très élevé (obligation légale, budget existant, renouvellement annuel).

### NICHE-04 — Surveillance de l'exécution de la gouvernance (qui surveillé les exécutions automatiques)

- **Problème récurrent** : Des exécutions légitimes peuvent être détournées : autorité pré-signée obtenue auprès d'un conseil de sécurité (Drift, 285 M$ en 128 secondes), question posée à l'oracle de gouvernance sans arbitre compétent (module de type SuDAO), interface falsifiée trompant des signataires (Bybit).
- **Fréquence** : 3 modèles d'attaque distincts confirmés sur 24 mois, tous fondes sur l'exécution ou la signature légitime d'une action détournée.
- **Organisations déjà identifiées** : Drift Protocol (post-incident) ; DAO utilisant des modules d'exécution de vote ; Protocoles disposant d'un conseil de sécurité avec pouvoirs d'urgence ; Fondations et entités opérationnelles signant pour une DAO
- **Nombre de cibles potentielles** : 4 (entrées listées dans le problème structurel rattaché ; détail en section 2)
- **Prestation standardisable** : Runbook de surveillance et d'escalade (4-6 j) ; matrice des fenêtres de veto ; test trimestriel de scénario d'attaque ; procédé de contrôle des autorités pré-signées.
- **Durée type** : 2 à 10 jours selon la cible (voir fiches)
- **Mission récurrente possible** : OUI
- **Compatibilité avec une intervention solo** : OUI
- **Secteurs concernés** : Gouvernance on-chain, DeFi, custody institutionnelle.
- **Causes communes** : Absence d'astreinte définie, fenêtres de veto non documentées, signatures sans lecture du contenu réel (blind signing), autorisations créées pour la commodite opérationnelle et jamais revues.
- **Conséquences** : Vidage de trésorerie en quelques minutes, impossibilité de récupération, perte de crédibilité du dispositif de gouvernance.
- **Niveau de concurrence** : Faible (sujet à la limite entre sécurité technique et gouvernance).
- **Potentiel de marché** : Moyen à élevé (population restreinte mais besoin aigu et récurrent).

### NICHE-05 — Contrôle des changements de coordonnées bancaires et anti-usurpation (cabinets, PME, secteurs à paiements sensibles)

- **Problème récurrent** : La fraude au changement de coordonnées bancaires est devenue le mode dominant de la fraude au président (environ 61% des cas de 2026 dans les données fournisseurs). Les contrôles de messagerie ne valident pas le processus métier : personne ne vérifié que le changement de coordonnées à fait l'objet d'une confirmation par un canal indépendant.
- **Fréquence** : 24 768 plaintes et 3,05 milliards de dollars de pertes déclarées en 2025 aux États-Unis (+10% sur un an) ; 74% des organisations touchées par la fraude au président selon l'enquete sectorielle ; campagne d'usurpation assistee par IA de plus d'un million de courriers (aout 2026) ; 4 schémas spécifiques documentés pour les cabinets comptables.
- **Organisations déjà identifiées** : Cabinets d'expertise comptable et de paie (fond clients, paiements fournisseurs gérés pour des clients) ; Agences immobilières et études (paiements à fort enjeu) ; Entreprises de construction et d'installation (paiements d'avancement) ; Courtiers et assureurs risques cyber (canal de distribution)
- **Nombre de cibles potentielles** : 4 (entrées listées dans le problème structurel rattaché ; détail en section 2)
- **Prestation standardisable** : Revue du processus de paiement (3-5 j) ; procédure de confirmation par canal indépendant ; matrice d'autorisation ; exercice de crise ; formation trimestrielle ; accompagnement après incident.
- **Durée type** : 2 à 10 jours selon la cible (voir fiches)
- **Mission récurrente possible** : OUI
- **Compatibilité avec une intervention solo** : OUI
- **Secteurs concernés** : Services professionnels, immobilier, construction, santé, industrie, secteur public local.
- **Causes communes** : Changement de coordonnées validé par le même canal que la demande, absence de double autorisation sur les paiements eleves, fichiers fournisseurs non verrouilles, alertes sur les règles de transfert automatique absentes, formation des équipes insuffisante.
- **Conséquences** : Perte de trésorerie immédiate (les pertes vérifiées depassent 100 k$ en moyenne), contentieux avec le fournisseur, obligations de déclaration, primes d'assurance revues à la hausse, perte de confiance client.
- **Niveau de concurrence** : Élevée sur la sécurité technique, quasi nulle sur la revue du processus de paiement et des contrôles de trésorerie.
- **Potentiel de marché** : Élevé (population très large, cycle de vente court, prestation facile à productiser et à repeter).

### NICHE-06 — Préparation à l'audit de la trésorerie en actifs numériques

- **Problème récurrent** : 42% des directeurs financiers citent la complexité comptable et de contrôle comme frein principal. Les normes de trésorerie exigent l'identite de l'initiateur, la preuve d'approbation, l'horodatage et l'alignement de la politique ; les explorateurs de blocs fournissent des hachages et des captures d'ecran, non des pistes d'audit. S'ajoutent les attestations mensuelles et les preuves de réserves attendues sous MiCA, et l'export limite des journaux d'audit de plusieurs plateformes de custody.
- **Fréquence** : Besoin structurel et permanent, renforcé par les échéances réglementaires 2026 et le nombre croissant de sociétés détenant des actifs numériques en trésorerie.
- **Organisations déjà identifiées** : sociétés de trésorerie d'actifs numériques, fintechs, établissements de monnaie électronique, prestataires de services sur crypto-actifs, fonds, sociétés non cotées détenant du bitcoin ou des stablecoins.
- **Nombre de cibles potentielles** : 0 (entrées listées dans le problème structurel rattaché ; détail en section 2)
- **Prestation standardisable** : Diagnostic de préparation à l'audit (5-8 j) ; matrice de contrôles ; dossier de preuves type ; rapprochement mensuel récurrente ; appui à l'auditeur.
- **Durée type** : 2 à 10 jours selon la cible (voir fiches)
- **Mission récurrente possible** : OUI
- **Compatibilité avec une intervention solo** : OUI
- **Secteurs concernés** : Finance d'entreprise, crypto, gestion d'actifs.
- **Causes communes** : Processus crypto dissocies des processus de trésorerie existants, absence de correspondance entre matrice d'approbation des paiements et signatures on-chain, rapprochement manuel, preuves non conservées dans un format auditable.
- **Conséquences** : réserves de l'auditeur, retards de certification, impossibilité de justifier une position à une date donnée, risque de requalification, refus bancaire.
- **Niveau de concurrence** : Moyenne (cabinets comptables et plateformes techniques) ; faible sur la jonction entre processus de trésorerie et preuve on-chain.
- **Potentiel de marché** : Élevé (mission récurrente mensuelle, clientele solvable, effet de recommandation entre pairs).

### NICHE-07 — Ingénierie du quorum et des délégations de gouvernance

- **Problème récurrent** : La participation reste sous 10% dans la plupart des DAO ; les 10% de porteurs les plus importants détiennent 76,2% du pouvoir de vote ; des propositions budgétaires echouent faute de quorum malgré une mobilisation record (cas Unlock DAO, février 2026) ; les solutions de court terme (abstention de la trésorerie, délégation multiple depuis la trésorerie) creent des risques de sécurité à l'exécution.
- **Fréquence** : Structurel (recherche academique 2025 sur plusieurs centaines de propositions) + cas datés 2024-2026 (Compound, Unlock).
- **Organisations déjà identifiées** : Unlock DAO ; DAO dont les votes budgétaires récentes n'ont pas atteint le quorum ; Protocoles préparant une délégation structurée depuis la trésorerie
- **Nombre de cibles potentielles** : 3 (entrées listées dans le problème structurel rattaché ; détail en section 2)
- **Prestation standardisable** : Analyse des options de quorum et de délégation (5-8 j) ; garde-fous d'exécution ; indicateur de santé de gouvernance ; revue semestrielle.
- **Durée type** : 2 à 10 jours selon la cible (voir fiches)
- **Mission récurrente possible** : A CONFIRMER
- **Compatibilité avec une intervention solo** : OUI
- **Secteurs concernés** : Web3, gouvernance, organisations décentralisées.
- **Causes communes** : Apathie rationnelle, coût du vote, concentration des tokens, délégations inactives, seuils de quorum mal calibrés par rapport à la distribution réelle du pouvoir de vote.
- **Conséquences** : Blocage des décisions budgétaires, capture par une minorite active, risque de gouvernance attaque, perte de légitimité.
- **Niveau de concurrence** : Faible (outils et plateformes existants, peu de conseil indépendant sur la conception du dispositif).
- **Potentiel de marché** : Moyen (population identifiée, budgets de gouvernance souvent limites ; valeur stratégique forte en entrée de relation).

## 6. ANNEXES

### Barèmes

- Score opportunité : {'exp': 12, 'solo': 12, 'dist': 8, 'duree': 8, 'cx': 8, 'prob': 12, 'dec': 8, 'urg': 8, 'rem': 8, 'recur': 6, 'conc': 5, 'sans_part': 3, 'acces': 2}
- Score DARKINT : {'fiabilite': 30, 'importance': 30, 'confirmation': 25, 'impact': 15}

### Sources du cycle

| ID | Titre | Éditeur | Date | URL |
|---|---|---|---|---|
| S01 | MEV Bot Yoink Beats Hacker to $7.8M rsETH Haul | shattered.io | 2026-09-19 | https://shattered.io/yoink-mev-bot-beats-hacker-rseth-2026/ |
| S02 | DeFi's $606M April: Kelp DAO bridge drain, Drift Protocol oracle+key compromise, Resolv AWS heist | bex.co | 2026-04-22 | https://bex.co/blog/2026/04/22/april-606m-hack-spree-defi-protocol-upgrade-vulnerabilities-kelp-drift-resolv |
| S03 | Nostra Halts Its Starknet Money Market After a $3.5M NSTR Oracle Exploit | cryptotimes.io | 2026-09-18 | https://www.cryptotimes.io/2026/09/18/nostra-halts-starknet-money-market-after-3-5m-nstr-oracle-exploit/ |
| S04 | Biggest DeFi Hacks and Exploits of 2026: $1 Billion+ Lost and Counting | ccn.com | 2026-05-19 | https://www.ccn.com/education/crypto/defi-hacks-exploits-causes-crypto-stolen-2026/ |
| S05 | DeFi has lost $1.3 billion to hacks in 2026 and the same attack keeps working | cryptonews.net | 2026-09-05 | https://cryptonews.net/news/security/33396919/ |
| S06 | Unlock DAO Newsletter février 2026 - The Quest for Quorum | paragraph.com / Unlock Protocol | 2026-02-12 | https://paragraph.com/@unlockprotocol/unlock-dao-newsletter-or-february-2026 |
| S07 | DAO Treasury Diversification: Funding opérations Without Dumping Tokens (Treasury Management Portfolio Arbitrum, 6 000 ETH, mars 2026) | cryptodaily.co.uk | 2026-08-19 | https://cryptodaily.co.uk/2026/08/dao-treasury-diversification-funding-operations |
| S08 | [RFP Process] Request for Proposals: Treasury Management Services for Arbitrum DAO | forum.arbitrum.foundation | 2025-01-22 | https://forum.arbitrum.foundation/t/rfp-process-request-for-proposals-treasury-management-services-for-arbitrum-dao/28242 |
| S09 | DAO Treasury Management: Onchain Governance & Spend (seuils, signataires, prestataires: Steakhouse, Karpatkey, Block Analitica, Coinshift, Den) | eco.com | 2026-05-26 | https://eco.com/support/en/articles/14799687-dao-treasury-management-onchain-governance-spend |
| S10 | DAO Accounting: A Practical Guide for Finance Leads and Accountants (audit trail gap) | breezing.io | 2026-04-08 | https://breezing.io/blog/dao-accounting-guide/ |
| S11 | DAO Treasury Management: Accounting and Financial Reporting Guide (matrices d'approbation, rotation des clés, séparation des fonctions) | fortress-accounting.com | 2026-01-02 | https://fortress-accounting.com/dao-treasury-management-accounting-financial-reporting/ |
| S12 | How DAOs Failed to Deliver on Their Original Promise (participation <10%, top 10% détient 76,2% du pouvoir de vote, Compound 2024) | medium / lopetaku | 2026-03-12 | https://lopetaku.medium.com/dao-governance-failures-whales-low-turnout-attacks-d1375c556384 |
| S13 | DAO Governance: Voting Power, Participation, and Controversy - A Review and an Empirical Analysis | ACM Digital Library | 2025-11-18 | https://dl.acm.org/doi/10.1145/3777416 |
| S14 | Crypto Treasury Management: The 2026 Institutional Playbook (42% des CFO citent la complexité comptable et de contrôle; fragmentation des pistes d'audit) | coinsdo.com | 2026-06-15 | https://www.coinsdo.com/en/crypto-treasury |
| S15 | Digital Asset Policy Changes in 2025 and 2026 (attestations mensuelles, portefeuilles ségréguées, proof-of-reserves, MiCA) | bitgo.com | 2026-07-21 | https://www.bitgo.com/resources/blog/digital-asset-policy-changes-2026/ |
| S16 | How Does DORA Address Third-Party ICT Risk? (Art. 28-30, registre d'informations, sous-traitance en chaîne, concentration) | thingsrecon.com | 2026-09-02 | https://www.thingsrecon.com/blog/how-does-dora-address-third-party-ict-risk |
| S17 | DORA Third-Party ICT Risk: Articles 28-30 Guide for 2026 (obligations, reporting annuel, plan de sortie) | cyadviso.com | 2026-06-01 | https://www.cyadviso.com/dora-third-party-ict-risk |
| S18 | Business Email Compromise Statistics 2026 (FBI 2025: 24 768 plaintes, 3,05 Md$; VEC ~61% du BEC; AFP: 74% des organisations touchées) | deepstrike.io | 2026-08-24 | https://deepstrike.io/blog/business-email-compromise-statistics |
| S19 | Business Email Compromise in Accountancy Firms: 4 patterns de fraude facture; hors dispositif de remboursement; sanction ICO DPP Law | progressiverobot.com | 2026-08-19 | https://www.progressiverobot.com/2026/08/19/invoice-fraud-accountancy-firms-business-email-compromise/ |
| S20 | Protecting organizations from AI-assisted exécutive impersonation and invoice fraud (>1 million d'e-mails, 3-5 aout 2026) | Microsoft Security Blog | 2026-09-10 | https://www.microsoft.com/en-us/security/blog/2026/09/10/protecting-organizations-ai-assisted-executive-impersonation-invoice-fraud/ |
| S21 | Third-Party Email Compromise doubled in one year (Verizon DBIR 2025: 30% des violations impliquent un tiers) | duocircle.com | 2026-05-14 | https://www.duocircle.com/blog/third-party-email-compromise-doubled-smb-vendor-security-risks-solutions/ |
| S22 | Audit C2D2: le CTR lancé un appel à candidatures à Kinshasa (audit financier et comptable 2026-2028, RDC, clôture 16/10/2026) | congoquotidien.com / actualite.cd | 2026-09-15 | https://www.congoquotidien.com/2026/09/15/recrutement-consultant-audit-c2d2/ |
| S23 | EOI - Technical Assistance to the Bank of Ghana in the implementation of the WE Finance Code (AHGC) | afdb.org | 2026-05-20 | https://www.afdb.org/en/consultants/eoi-technical-assistance-bank-ghana-implementation-we-finance-ahgc-93448 |
| S24 | Acquisition of Consultancy Services - Individual Consultants (BAD: DACON, éligibilité, missions de 6 à 12 semaines) | afdb.org | 2024-01-01 | https://www.afdb.org/en/projects-and-operations/procurement/frequently-asked-questions/acquisition-of-consultancy-services-individual-consultants |
| S25 | The end of World Bank Short-Term Consultants (gel des nominations STC à partir de juillet 2026) | mdbjobs.com | 2026-01-07 | https://www.mdbjobs.com/p/the-end-of-world-bank-short-term |
| S26 | Roster: Finance Consultant (UNFPA - IPSAS, reporting bailleurs, transferts de fonds aux partenaires, compta stocks) | unfpa.org | 2026-06-23 | https://www.unfpa.org/jobs/roster-finance-consultant |
| S27 | UN Women Home-Based Associate Consultant 2026 - Finance and Programme (Kenya, 6 mois, clos le 11/09/2026) | campuslifestyle.org | 2026-09-07 | https://campuslifestyle.org/2026/09/07/un-women-home-based-associate |
| S28 | Fractional CFO (6-8 heures/semaine) - Fintech / Remote; Fractional Controller 50-100$/h remote; Interim CFO 130-175$/h remote | fractionalpulse.com | 2026-08-30 | https://fractionalpulse.com/jobs/ |
| S29 | Financial Management Specialist - World Bank, Maputo (poste salarié, recrutement local, clôture 08/05/2026) | unjobnet.org | 2026-04-24 | https://www.unjobnet.org/jobs/detail/85832956 |
| S30 | Digital Asset Security Platforms Compared: DFNS vs Fireblocks vs Anchorage (limites des pistes d'audit exportables, custody qualifiée) | ridgewayfs.com | 2026-05-16 | https://www.ridgewayfs.com/digital-asset-security-platforms/ |
| S31 | Treasury Custody: Multi-Sig vs MPC vs HSM (architecture hybride hot/warm/cold, dépendance fournisseur MPC) | eco.com | 2026-05-26 | https://eco.com/support/en/articles/14799685-treasury-custody-multi-sig-vs-mpc-vs-hsm |
| S32 | MPC Wallets Aren't Enough for Institutional Custody (politique, moteur de règles, journal d'audit inviolable) | chainup.com | 2026-08-18 | https://chainup.com/blog/mpc-wallets-arent-enough-for-instutional-custody |
| S33 | A Technical Post Mortem of SuperUMAn DAO (SuDAO) Hack - Flaws In Existing Governance Tools (module Safe/Zodiac Reality, surveillance 24/7) | publish0x / medium-coinmonks | 2022-11-24 | https://www.publish0x.com/everythingblockchain/a-technical-post-mortem-of-superuman-dao-sudao-hack-flaws-in-xozrzmj |
| S34 | Bybit Hack Post-Mortem identifiés Safe Infrastructure as Exploit Point (frontend falsifié, blind signing) | bankless.com | 2025-02-26 | https://www.bankless.com/read/bybit-hack-post-mortem-identifies-safe-infrastructure-as-exploit-point |
| S35 | WBGeProcure RFx Now remplace eConsultant2 (nouvelle plateforme de passation Banque mondiale) | worldbank.org | 2026-01-15 | https://www.worldbank.org/en/about/corporate-procurement/announcements/WBGeProcure-RFxNow |
| S36 | Cork Finance exploit post-mortem 28 mai 2025 (hook Uniswap v4, 3 761 wstETH, multsig pour pause) | cork.tech | 2025-06-04 | https://www.cork.tech/blog/post-mortem |

### Rappel de validation

Aucune conversion commerciale n'est inventée : l'entonnoir reste à zéro (0 contact engagé, 0 proposition transmise, 0 négociation, 0 mission signée, 0 revenu). Toute action externe est subordonnée à une validation humaine L5.