# TiMe — Politique de confidentialité

**Dernière mise à jour :** 13 novembre 2026
**En vigueur :** 13 novembre 2026

> Ceci est une traduction. En cas de divergence, la version anglaise ou
> turque prévaut.

---

## En bref

TiMe est une app de suivi du cycle menstruel. Tes données sont **stockées
sur ton appareil par défaut.** Aucun compte n'est nécessaire. Nous ne
conservons pas tes données de cycle sur nos serveurs. Nous ne partageons
aucune donnée avec des réseaux publicitaires. Les statistiques d'utilisation ne fonctionnent que si tu les actives dans Réglages ; tes données de santé ne sont jamais envoyées aux statistiques.

Tes données ne quittent ton appareil que dans les cas suivants, chacun sous ton contrôle :

1. **Commentaires IA et discussion** — quand tu actives le modèle en ligne pour la discussion ou quand le modèle embarqué n'est pas
   disponible et que tu as donné ton consentement
2. **Échange avec Apple Santé (HealthKit)** — quand tu l'autorises
3. **Achats d'abonnement**
4. **Rapports de plantage et statistiques d'utilisation** — les rapports de plantage sont activés par défaut et peuvent être désactivés ; les statistiques seulement si tu les actives

Détails ci-dessous.

---

## 1. Responsable du traitement

| | |
|---|---|
| Nom | Batuhan Atabek |
| Adresse | Antalya, Turquie — les demandes peuvent être envoyées par e-mail |
| E-mail | atabeksoft+privacy@gmail.com |

Cette politique s'applique à l'application iOS TiMe.

---

## 2. Données traitées

### 2.1 Données qui restent sur ton appareil

Stockées dans la base de données locale de ton appareil et **jamais
envoyées à nos serveurs :**

- Dates de début et de fin des règles, durée des cycles
- Abondance du flux
- Symptômes (physiques, humeur, pertes, peau, digestion, sommeil, énergie)
- Enregistrements d'activité sexuelle
- Température basale, poids, résultats de tests d'ovulation
- Tes notes libres
- Préférences de l'app (langue, unités, heures de rappel)
- Ton historique de discussion avec l'IA

Certaines de ces données sont des **catégories particulières de données**
(données de santé et données relatives à la vie sexuelle) au sens de
l'article 9 du RGPD. C'est pourquoi notre architecture par défaut est le
stockage sur l'appareil.

### 2.2 Données pouvant quitter ton appareil

**a) Commentaires IA et discussion**

TiMe utilise d'abord **le modèle d'IA de ton appareil** pour générer des
commentaires. Dans ce cas, aucune donnée ne quitte ton appareil.

Si tu as donné ton consentement, tu peux aussi activer « Discussion plus pertinente avec le modèle en ligne » dans Réglages. Activée, tes messages de discussion vont d'abord au modèle en ligne selon les règles ci-dessous, même si ton appareil prend en charge le modèle embarqué. Elle est désactivée par défaut et n'affecte pas les commentaires ponctuels.

Si ton appareil ne prend pas en charge ce modèle, on te le demande une
fois, et **seulement si tu y consens**, les éléments suivants sont
envoyés via une connexion chiffrée à un serveur proxy, puis à un
fournisseur d'IA :

Envoyé :
- La durée de tes cycles (chiffres uniquement)
- Ta phase de cycle actuelle
- Les symptômes que tu as sélectionnés
- Les messages **que tu écris** dans la discussion
- La langue de l'interface

Non envoyé :
- Ton nom, ton e-mail, ta date de naissance
- Localisation
- Identifiant de l'appareil ou publicitaire
- Dates exactes
- Notes libres de tes enregistrements quotidiens

Tu peux retirer ce consentement à tout moment dans Réglages. L'app revient
alors aux commentaires basés sur des règles et continue de fonctionner.

**Important :** le texte que tu écris dans la discussion est transmis au
fournisseur tel quel. Nous te conseillons de ne pas y écrire
d'informations permettant de t'identifier.

**b) Apple Santé (HealthKit)**

Avec ton autorisation, le flux menstruel, la température basale et les
enregistrements associés sont échangés avec Apple Santé. Ces données
restent sur ton appareil et ne nous sont pas envoyées.

Nous **n'utilisons pas les données HealthKit à des fins de publicité, de
marketing ou d'exploration de données, et ne les partageons pas avec des
tiers.**

**c) Abonnements**

Les achats sont traités par Apple. Nous n'avons **aucun accès à tes
informations de paiement.** Nous utilisons RevenueCat pour suivre l'état
de l'abonnement ; seuls un identifiant utilisateur anonyme et l'état de
l'abonnement sont envoyés, jamais tes données de cycle.

**d) Prévention des abus**

Pour éviter les abus des requêtes IA, un identifiant aléatoire (UUID) est
créé sur ton appareil. Il ne peut pas être relié à toi, sert uniquement à
compter les requêtes quotidiennes et est réinitialisé à la suppression de
l'app.

**e) Rapports de plantage et statistiques d'utilisation (Google Firebase)**

- **Rapports de plantage (Firebase Crashlytics) :** si l'app plante, l'emplacement de l'erreur dans le code, le modèle d'appareil, la version d'iOS, la version de l'app et un identifiant d'installation aléatoire sont envoyés à Google. Le rapport ne contient ni cycles, ni symptômes, ni notes, ni autre donnée de santé. Activés par défaut ; désactive-les dans Réglages > Confidentialité > « Rapports de plantage ».
- **Statistiques d'utilisation (Firebase Analytics) :** **désactivées** par défaut ; elles ne fonctionnent que si tu actives Réglages > Confidentialité > « Statistiques d'utilisation ». Dans ce cas, les écrans principaux ouverts, la fin de la configuration, l'affichage de l'écran d'abonnement et les étapes d'achat (nom du produit compris) sont envoyés, avec un identifiant d'app aléatoire. Les cycles, symptômes, dates, notes et contenus de discussion ne sont **jamais** envoyés. Sont aussi envoyés le fait qu'un message de discussion a été envoyé (sans son contenu) et le résultat de la restauration des achats. Firebase enregistre aussi automatiquement des informations de base comme la première ouverture, le début de session, le temps passé dans l'app, le modèle d'appareil, la version d'iOS et le pays approximatif déduit de l'adresse IP. L'identifiant publicitaire (IDFA) n'est pas collecté et la publicité personnalisée est désactivée. Désactiver l'option supprime l'identifiant d'analyse sur ton appareil.

### 2.3 Données que nous ne collectons pas

- Nom, e-mail, numéro de téléphone
- Localisation
- Identifiant publicitaire (IDFA)
- Contacts, photos, appareil photo, micro
- Toute statistique contenant des données de santé

### 2.4 Fonctions non proposées actuellement

L'app ne propose **pas** de synchronisation cloud (iCloud). Tes données ne
sont pas synchronisées entre appareils. Si cette fonction est ajoutée,
cette politique sera mise à jour et ton consentement demandé séparément.

---

## 3. Base juridique (RGPD)

| Finalité | Données | Base juridique |
|---|---|---|
| Prévision et suivi du cycle | Données de cycle et de symptômes | Consentement explicite, art. 9(2)(a) |
| Commentaires IA (sur l'appareil) | Données de cycle et de symptômes | Consentement explicite |
| Commentaires IA (en ligne) | Données du §2.2(a) | Consentement explicite distinct |
| Intégration Apple Santé | Données de santé | Consentement explicite |
| Notifications | Dates prévues, heures choisies | Consentement |
| Gestion de l'abonnement | ID anonyme, état de l'abonnement | Contrat, art. 6(1)(b) |
| Prévention des abus | Identifiant aléatoire de l'appareil | Intérêt légitime, art. 6(1)(f) |

---

## 4. Transferts internationaux

Si tu consens aux commentaires IA en ligne, les données listées au
§2.2(a) sont transférées vers des serveurs situés hors de ton pays.

| Destinataire | Rôle | Pays |
|---|---|---|
| Cloudflare, Inc. | Serveur proxy | États-Unis |
| Anthropic, PBC | Fournisseur d'IA — commentaires et discussion (Claude) | États-Unis |
| Google LLC | Rapports de plantage et statistiques d'utilisation (Firebase) — §2.2(e) | États-Unis |

Les transferts liés à l'IA et aux statistiques d'utilisation reposent sur ton **consentement explicite.** Les rapports de plantage ne contiennent aucune donnée de santé ; si tu ne veux pas les envoyer, désactive-les dans Réglages. Sans consentement pour l'IA, tes données de cycle et de symptômes ne sont pas transférées et l'app continue de fonctionner sur l'appareil.

Notre proxy **n'enregistre pas** tes données de santé.

Conditions des fournisseurs :
- Google Firebase : https://firebase.google.com/support/privacy
- Anthropic : https://www.anthropic.com/legal/commercial-terms

---

## 5. Durée de conservation

- **Données sur l'appareil :** jusqu'à ce que tu les supprimes.
  Supprimer l'app les supprime.
- **Données envoyées au fournisseur d'IA :** non conservées par nous
  après la génération de la réponse.
- **Identifiant anti-abus :** 24 heures.
- **Rapports de plantage :** jusqu'à 90 jours chez Google Firebase.
- **Statistiques d'utilisation :** données au niveau des événements jusqu'à 2 mois chez Google Analytics.
- **Données d'abonnement :** conservées par Apple et RevenueCat selon les
  obligations légales.

---

## 6. Tes droits

En vertu du RGPD, tu disposes d'un droit d'accès, de rectification,
d'effacement, de limitation du traitement, de portabilité, d'opposition,
et du droit de retirer ton consentement à tout moment. Tu peux aussi
introduire une réclamation auprès de ton autorité de contrôle (en France,
la CNIL).

**En pratique :** comme la plupart de tes données ne se trouvent que sur
ton appareil, tu peux exercer plusieurs de ces droits directement dans
l'app :

- **Accès / portabilité :** Réglages → Exporter tes données
- **Effacement :** Réglages → Supprimer toutes les données
- **Retrait du consentement :** Réglages → Consentement IA

Pour toute autre demande : atabeksoft+privacy@gmail.com. Nous répondons
sous 30 jours.

---

## 7. Enfants

TiMe ne s'adresse pas aux enfants de moins de 13 ans et nous ne
collectons pas sciemment leurs données. Si tu es parent ou tuteur et
penses que ton enfant utilise l'app, écris à
atabeksoft+privacy@gmail.com.

---

## 8. Sécurité

- Les données sont stockées dans le bac à sable standard des apps iOS.
- Verrouillage facultatif de l'app (Face ID / Touch ID).
- Tout le trafic réseau est chiffré en TLS.
- Notre proxy n'enregistre pas de données de santé.
- Les données envoyées au fournisseur d'IA sont minimisées.

Aucun système n'est totalement sûr. Nous te conseillons de garder ton
appareil à jour et d'utiliser un code d'accès.

---

## 9. Avertissement médical

TiMe sert à l'information et au suivi personnel. Ce n'est **ni un
diagnostic médical, ni un traitement, ni une méthode de contraception.**
Les prévisions sont statistiques et peuvent être erronées. Consulte un
professionnel de santé pour toute décision concernant ta santé.

---

## 10. Modifications

Si nous modifions cette politique, nous afficherons un avis dans l'app et
mettrons à jour la date ci-dessus. Pour les changements importants, nous
te redemanderons ton consentement.

---

## 11. Contact

**Batuhan Atabek**
Antalya, Turquie — les demandes peuvent être envoyées par e-mail
atabeksoft+privacy@gmail.com
