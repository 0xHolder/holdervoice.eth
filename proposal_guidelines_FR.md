GUIDELINES POUR CRÉER UNE PROPOSAL ON-CHAIN
HolderVoice – Processus démocratique de gouvernance par Series LLC
📌 Vue d'ensemble
Une Proposal est une déclaration on-chain formelle soumise au vote par les token holders d'une unique Series LLC. Chaque proposal concerne exclusivement les détenteurs de tokens d'une propriété/LLC donnée et ne peut pas affecter les autres Series.

Le vote on-chain enregistre chaque adresse ERC-20 signataire et crée une preuve immuable que X holders demandent Y action concernant la Series Z.

🎯 Types de Proposal autorisés
Catégorie 1 : Information & Transparence

✅ Demande d'accès aux comptes, états financiers, détails des flux de trésorerie (exemple : Series 118)

✅ Demande d'audit externe indépendant

✅ Demande de breakdown fiscal des distributions

✅ Demande de rapport sur l'état de la propriété, conformité des taxes, assurances

✅ Demande d'explication sur suspension/modification de distributions

✅ Demande de détail sur travaux, rénovations, dépenses

Fondement légal : §18-305 Delaware LLC Act (droit inaliénable d'accès aux livres et registres)


Catégorie 2 : Gouvernance & Procédure

✅ Élection/révocation du Board ou Administrator

✅ Changement d'adresse ou coordonnées de notification légale

✅ Approbation d'une action collective (class action, litigation supportée par les holders)

✅ Mandat à un cabinet d'avocat pour action légale (§18-305, etc.)


Fondement légal : Operating Agreement (pouvoir des members sur gouvernance)


❌ Ce qui N'EST PAS autorisé
❌ Proposal affectant plusieurs Series LLC à la fois (une proposal = une Series)

❌ Demande d'action contre les fondateurs /gestionnaires sans fondement légal documenté

❌ Demande de modification des droits des token holders sans compensation ou vote spécial prévu par l'Operating Agreement

❌ Proposal clairament abusive, harcelante ou sans objet légitime (spam)

❌ Demande de fonds ou distribution pour bénéficier un holder individuel (conflit d'intérêt)

❌ Proposal dans une autre langue que FR ou EN

❌ Contenu illégal, diffamant, ou discriminant

📝 Structure minimale d'une Proposal
Chaque proposal doit inclure ces éléments dans cet ordre :

1. Titre (court & clair)
Exemple :

« Series 118 – Demande d'accès aux comptes 2022-2025 »

❌ À éviter : « Important action needed » | « Fix the mess » | « Emergency »

2. Series LLC Identifier (obligatoire)
Déclare précisément quelle Series est concernée :

text
Series LLC: Series xxx
Propriété: 2318-2324 xxxxx, Chicago IL 60636
Juridiction: Delaware
Managing Member: xxx Inc.
3. Contexte / Justification (2–5 paragraphes max)

Réponds à ces questions :

Pourquoi cette proposal est soumise maintenant ?

Quel problème cherche-t-on à résoudre ?

Quels événements récents l'ont motivée ? (suspension de distributions, impayés taxes, etc.)

Quel dommage potentiel si on n'agit pas ?

Ton : factuel, pas émotionnel. Cite des données publiques si possible (Cook County Treasurer, dates officielles, etc.).

4. Objet de la Proposal (énuméré, précis)
Liste exactement ce que tu demandes. Pas de flou.

Bons exemples :

text
DEMANDE 1 : xxxx Inc. fournit les états financiers GAAP 
de Series 118 pour 2022, 2023, 2024 et QTD 2025.

DEMANDE 2 : Détail mensuel des loyers encaissés et dépenses 
par catégorie (property tax, insurance, management fees, etc.)

DEMANDE 3 : Plan écrit expliquant la suspension des distributions 
du 17 février 2025 et calendrier de reprise.

Délai de réponse : 30 jours calendaires après réception formelle.
Mauvais exemples :

text
❌ « Demander les comptes et infos sur la propriété »
❌ « Exiger de meilleures communications »
❌ « Autoriser la vente si le prix est bon »
5. Fondement légal (2–3 lignes obligatoires)
Cite le fondement qui te permet de faire cette demande :

Pour demande d'info :

Delaware LLC Act §18-305 (droit d'accès aux livres et registres) + Operating Agreement Article [X] (Books and Reports).

Pour décision opérationnelle :

Operating Agreement Article [Y] (Member Voting Rights) – les members peuvent voter sur [type de décision].

Pour action légale :

Operating Agreement Article [Z] + Common Law Fiduciary Duty. xxx Inc., en tant que Managing Member, a obligation fiduciaire envers les Series 118 members.

6. Impact fiscal / Proper Purpose (si applicable)
Obligatoire si c'est une demande d'info ou d'accès aux comptes.

Démontre que c'est légitime, pas harcelant :

text
PROPER PURPOSE:
- Permettre aux holders de déclarer correctement leurs impôts (IRC §164, §1031, §469)
- Évaluer le risque de perte de propriété lié aux taxes impayées
- Vérifier la conformité de l'allocation des cash flows selon l'Operating Agreement
- Protéger le capital investi des holders
7. Processus en cas de refus (escalade légale)
Optionnel mais recommandé si c'est une demande sérieuse :

text
ESCALADE:
Si xxx Inc. ne fournit pas une réponse complète dans les 30 jours,
les signataires autorisent [Cabinet d'avocat Delaware] à:
- Formaliser la demande §18-305 et la notifier par voies légales
- Déposer plainte en Delaware Chancery Court si nécessaire
- Demander fee-shifting si mauvaise foi prouvée

8. Disclaimers légaux minimaux
Ajoute toujours en bas :

text
DISCLAIMERS:
- Cette proposal ne constitue pas un conseil juridique, fiscal ou d'investissement.
- Elle ne garantit pas un résultat favorable ou l'obtention des informations demandées.
- Elle n'oblige financièrement aucun holder sauf s'il choisit de contribuer 
  volontairement aux frais juridiques (le cas échéant).
- En cas de divergence FR/EN, la version EN prévaut.
🗳️ Paramètres du vote
Chaque proposal doit spécifier :

Paramètre	Valeur	Notes
Série concernée	[Series XXX]	Un seul, obligatoire
Période de vote	[X jours]	Recommandation : 7–21 jours
Snapshot block	[TBD]	Bloc Ethereum/Gnosis où on « compte » les holdings
Quorum requis	30%+ des tokens	Ou défini par Operating Agreement
Majorité requise	Simple majorité (50%+1)	Ou super-majorité si demandé
Résultat liant	OUI = binding proposal	Les holders font voter = mandat au Managing Member
📋 Template standard à utiliser
text
# [SERIES XXX] – [Titre court de la Proposal]

## Series LLC
- **Série** : Series XXX
- **Propriété** : [Adresse complète]
- **PIN County** : [Si USA]
- **Juridiction** : Delaware
- **Managing Member** : xxx Inc.

## Contexte
[2–5 paragraphes : pourquoi, quoi, depuis quand, quel dommage]

## Objet de la Proposal
[Énuméré précisément]

## Fondement légal
[Delaware LLC Act §XX + Operating Agreement Article YY]

## Proper Purpose / Justification
[Si demande d'info ou action légale]

## Processus en cas de non-respect
[Escalade légale, si applicable]

## Disclaimers
[Standard legal disclaimers]

## Vote
- Période : [dates]
- Quorum : [%]
- Majorité : [type]

---

**Version : [Date] | Langue : FR/EN**
✅ Checklist avant de soumettre
 La proposal concerne 1 seule Series LLC (pas plusieurs)

 Le titre est court, clair et factuel (pas émotion)

 Le contexte inclut des données vérifiables (dates, montants, sources publiques)

 Les demandes sont énumérées précisément (pas de flou)

 Il y a un fondement légal cité (LLC Act, Operating Agreement, etc.)

 Le proper purpose est justifié (fiscal, protection du capital, etc.)

 Les disclaimers légaux sont présents

 Les paramètres de vote sont définis (dates, quorum, majorité)

 La proposal est en FR ou EN (ou les deux)

 La proposal respecte la loi (pas d'illégalité, pas de discrimination)

 Elle n'est pas spam/abusive (objet légitime)

🔧 Processus de validation (optionnel mais recommandé)
Avant de lancer le vote on-chain :

Relecture par les holders : Post-la dans le Discord/Telegram de la Series 48h avant vote pour feedback

Révision légale (optionnel mais recommandé pour demandes sérieuses) : Fais relire par avocat Delaware ($300–500)

Snapshot technique : Vérifie que le bloc Ethereum & adresses sont correctes

Go live : Lance le vote on-chain

💡 Exemples de proposals valides
Exemple 1 : Demande d'info (Catégorie 1)
text
# Series 118 – Demande d'accès aux comptes 2022–2025

## Contexte
Series 118 (2318-2324 xxx, Chicago) a suspendu les distributions 
le 17 février 2025. Aucun détail n'a été fourni sur l'allocation des loyers 
depuis. Les données Cook County Treasurer montrent 36,699 USD de taxes impayées.

## Objet
1. États financiers GAAP 2022–2024 + QTD 2025
2. Détail mensuel des loyers, dépenses, réserves
3. Situation fiscale Cook County complète
4. Breakdown fiscal des distributions passées
5. Mémo expliquant la suspension

Délai : 30 jours.

## Fondement
Delaware LLC Act §18-305 (droit inaliénable d'accès aux livres et registres).

## Proper Purpose
Permettre aux holders de se conformer aux obligations fiscales IRS 
et de protéger leur capital investi.

## Escalade
Si refus, les signataires autorisent [Avocat] à agir en Chancery Court.

[Disclaimers]
Exemple 2 : Décision opérationnelle (Catégorie 2)
text
# Series 42 – Autorisation de vente avec conditions

## Contexte
Series 42 (Detroit, MI) est en déclin de valeur depuis 18 mois. 
La gestion locale pose des défis. Une vente permettrait aux holders 
de réaliser leur capital à meilleur prix.

## Objet
1. Autoriser le Managing Member à commercialiser et vendre la propriété
2. Prix listing minimum : $95,000 USD (basé sur expertise récente)
3. Délai de commercialisation : 12 mois
4. Approbation requise des holders avant acceptation d'offre < $85,000

## Fondement
Operating Agreement Article V (Member Voting Rights).

## Disclaimers
[Standard]
Exemple 3 : Gouvernance (Catégorie 3)
text
# Series 87 – Changement de Property Manager

## Contexte
Le property manager actuel (ABC Properties) n'a pas répondu à 
maintenance requests depuis 6 mois. 3 plaintes locataires, retards 
sur rapports mensuels.

## Objet
1. Autoriser le Managing Member à terminer le contrat avec ABC Properties
2. Sélectionner un nouveau property manager selon critères : 
   - Fee < 10%
   - Réponse maintenance < 48h
   - Reporting mensuel en 5 jours

## Fondement
Operating Agreement Article III (Management).

## Disclaimers
[Standard]
🚨 Exemples de proposals REJETÉES
❌ « Series 12 & 45 – Réduire tous les fees »
→ Affecte 2 Series, spam potentiel

❌ « Series 67 – Emergency: fire the team »
→ Pas de contexte factuel, émotion, pas de fondement légal

❌ « All Series – Investigate xxx corruption »
→ Affecte toutes les Series, allégation sans preuve

❌ « Series 33 – I demand $10,000 personal compensation »
→ Conflit d'intérêt, demande individuelle

📞 Support

Validation technique : Ouvre issue sur repo GitHub HolderVoice

Version : 16 mars 2026 | Format : Français + English
