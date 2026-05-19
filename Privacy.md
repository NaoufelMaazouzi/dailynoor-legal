# Politique de confidentialité — DailyNoor

**Dernière mise à jour : 22 mai 2026**

## 1. Qui sommes-nous ?

DailyNoor est une application mobile éditée par **Naoufel Maazouzi**
(« nous », « notre », « DailyNoor »), proposant des rappels
quotidiens d'inspiration.

- Éditeur : Naoufel Maazouzi
- Contact : naoufel.maazouzi@live.fr
- Adresse : 32 rue de l'orée des bois, 28500 Vernouillet

## 2. Données que nous collectons

### 2.1 Données fournies par toi

- **Prénom** (saisi pendant l'onboarding) — pour personnaliser
  l'application.
- **Adresse email** (optionnelle, via l'écran d'opt-in ou via
  Connexion avec Apple) — pour t'envoyer des nouvelles sur l'app et
  retrouver ton compte sur un autre appareil.
- **Réponses au questionnaire d'onboarding** (genre, situation,
  centres d'intérêt, objectifs, etc.) — pour personnaliser le
  contenu et améliorer l'application.

### 2.2 Données générées par ton usage

- **Rappels favoris, historique de lecture, collections** — stockés
  localement et synchronisés avec ton compte.
- **Préférences d'affichage** : thème visuel, icône d'application,
  langue, fréquence des rappels du widget, paramètres de
  notifications.
- **Statut d'abonnement** : si tu es Premium ou non, date
  d'expiration de l'essai.

### 2.3 Données techniques (anonymisées)

- **Identifiant utilisateur Supabase** : un UUID anonyme généré au
  premier lancement, ré-attribué si tu te connectes avec Apple.
- **Événements d'usage produit** (PostHog) : ouverture du feed,
  étapes d'onboarding terminées, écrans de paywall vus/fermés,
  achats. Aucune donnée personnelle (email, prénom) n'est jointe à
  ces événements.
- **Rapports de plantage et de performance** (Sentry) : stack traces,
  modèle d'appareil, version iOS. Aucune information personnelle
  identifiable n'est envoyée (configuration `sendDefaultPii = false`
  + filtre `beforeSend` qui nettoie les emails dans les breadcrumbs).

### 2.4 Données que nous ne collectons PAS

- Pas de géolocalisation.
- Pas de carnet d'adresses, photos, microphone, caméra.
- Pas de tracking publicitaire (`NSPrivacyTracking = false`).
- Pas d'IDFA, pas de cookies tiers.

## 3. Comment nous utilisons tes données

| Donnée | Finalité | Base légale (RGPD) |
|---|---|---|
| Prénom, email, réponses onboarding | Personnalisation de l'app | Exécution du contrat |
| Identifiant utilisateur, sync rappels favoris | Synchronisation multi-appareils | Exécution du contrat |
| Statut d'abonnement | Déblocage Premium | Exécution du contrat |
| Événements d'usage produit (PostHog) | Amélioration de l'app | Intérêt légitime (opt-out possible) |
| Rapports de plantage (Sentry) | Stabilité de l'app | Intérêt légitime (opt-out possible) |

## 4. Avec qui partageons-nous tes données ?

DailyNoor s'appuie sur les prestataires suivants, qui agissent en
qualité de sous-traitants au sens du RGPD :

- **Supabase** (Inc., USA — clauses contractuelles types) :
  hébergement de la base de données et de l'authentification.
- **RevenueCat** (Inc., USA) : gestion des abonnements iOS.
- **PostHog** (Cloud EU si configuré, sinon US) : analytics produit.
- **Sentry** (Functional Software Inc., USA) : monitoring des
  plantages.
- **Apple** (Apple Inc.) : Sign In with Apple, traitement des
  paiements via l'App Store.

Nous ne **vendons jamais** tes données à des tiers.

## 5. Où sont stockées tes données ?

- Les données de profil et de contenu sont stockées sur les serveurs
  de Supabase (région **eu-west-3, Paris**).
- Les événements d'analytics (PostHog) sont stockés en région **EU**
  (instance `eu.posthog.com`).
- Les rapports de plantage (Sentry) sont stockés en région **EU**.

## 6. Durée de conservation

- Données de compte : tant que ton compte existe.
- Si tu supprimes ton compte via « Mon compte → Supprimer mon
  compte », toutes les données sont effacées dans un délai de **30
  jours**.
- Événements d'analytics : 12 mois maximum.
- Rapports de plantage : 90 jours maximum.

## 7. Tes droits

Conformément au RGPD et à la loi Informatique et Libertés, tu
disposes des droits suivants :

- **Accès** : tu peux nous demander une copie des données que nous
  détenons sur toi.
- **Rectification** : tu peux modifier ton prénom, email, etc.
  directement dans l'app.
- **Effacement** : tu peux supprimer ton compte dans « Mon compte »
  ou nous écrire à naoufel.maazouzi@live.fr.
- **Portabilité** : tu peux nous demander un export de tes données.
- **Opposition** : tu peux désactiver l'analytics via « Mon profil →
  Confidentialité → Aider à améliorer DailyNoor ».
- **Limitation** : tu peux nous demander de geler le traitement.

Pour exercer ces droits, contacte-nous à
**naoufel.maazouzi@live.fr**. Tu peux aussi introduire une
réclamation auprès de la CNIL (cnil.fr).

## 8. Sécurité

- Toutes les communications avec nos serveurs sont chiffrées (HTTPS,
  TLS 1.2+).
- Les paiements sont gérés par Apple et RevenueCat — nous n'avons
  jamais accès à tes données bancaires.

## 9. Enfants

DailyNoor n'est pas destinée aux enfants de moins de **13 ans**.
Nous ne collectons pas sciemment de données concernant ces
utilisateurs.

## 10. Modifications

Cette politique peut être mise à jour. Nous t'en informerons en
modifiant la date en haut de ce document. L'usage continu de l'app
après modification vaut acceptation.

## 11. Contact

Naoufel Maazouzi
32 rue de l'orée des bois, 28500 Vernouillet
naoufel.maazouzi@live.fr
