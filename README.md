# CoPerf — Gestion de clubs d'athlétisme

Application mobile de gestion complète pour clubs d'athlétisme : planification des entraînements, suivi des résultats de compétition et messagerie temps réel entre coachs et athlètes.

---

## Stack technique

| Couche | Technologie |
|---|---|
| Frontend | Flutter (Dart) — iOS & Android |
| Backend | Firebase (Firestore, Auth, Cloud Functions, FCM) |
| Paiement | Stripe (abonnements clubs) |
| Notifications | Firebase Cloud Messaging |

---

## Fonctionnalités principales

- **Multi-rôles** : un utilisateur peut être simultanément athlète, coach et/ou administrateur de club
- **Gestion des groupes** : création de groupes d'entraînement, affectation des athlètes et coachs
- **Calendrier unifié** : vue personnalisée par rôle (entraînements, compétitions, indisponibilités, congés)
- **Suivi des performances** : saisie et historique des résultats par discipline (35+ disciplines FFA)
- **Messagerie temps réel** : conversations privées coach ↔ athlète, groupes d'entraînement, canal club
- **Inscriptions aux compétitions** : gestion des engagements par l'entraîneur
- **Indisponibilités** : déclaration de blessures, vacances et absences avec validation
- **Abonnements clubs** : intégration Stripe avec gestion du cycle de vie (Blaze plan Firebase)
- **Notifications push** : alertes pour les entraînements, compétitions et messages

---

## Chiffres clés

- ~1 200 athlètes actifs suivis
- 2 clubs en production
- 35+ disciplines athlétiques (référentiel FFA complet)
- Support multi-groupes et multi-rôles simultanés

---

## Installer l'app (Android)

L'APK de démonstration est disponible dans la section **[Releases](https://github.com/Raphael-344/coperf-app/releases)** de ce repo.

### Étapes d'installation

1. Télécharge le fichier `app-release.apk` depuis la dernière release
2. Sur ton téléphone Android, va dans **Paramètres → Applications → Autoriser les sources inconnues** (ou "Installer des apps inconnues" selon la version Android)
3. Ouvre le fichier APK téléchargé et suis les instructions d'installation

> L'app n'est pas publiée sur le Play Store — c'est une version de démonstration distribuée directement via APK.

---

## Compte de démonstration

Trois comptes sont disponibles selon ce que tu veux explorer :

| Rôle | Email | Mot de passe |
|---|---|---|
| Président | demo.president@coperf.app | Demo1234! |
| Coach | demo.coach@coperf.app | Demo1234! |
| Athlète | demo.athlete@coperf.app | Demo1234! |

**Président** — Vue globale du club : gestion des membres, des coachs et des groupes, accès à tous les canaux de messagerie (club, coachs, groupes d'entraînement), suivi des abonnements.

**Coach** — Gestion d'un groupe d'athlètes : planification des entraînements, inscription aux compétitions, suivi des performances, messagerie avec les athlètes du groupe.

**Athlète** — Vue personnelle : calendrier des entraînements et compétitions, historique des performances, déclaration d'indisponibilités, messagerie avec le coach.

---

## Contact

**Raphaël Gasparin**
📧 raphael.gasparin.34@gmail.com
