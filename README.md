# BarManager Pro

*La solution tout-en-un de gestion de bar et restaurant pour le Cameroun et l'Afrique Centrale.*

![Version](https://img.shields.io/badge/version-1.0.8-amber)
![Desktop](https://img.shields.io/badge/desktop-disponible-green)
![Web SaaS](https://img.shields.io/badge/web%20SaaS-bient%C3%B4t-orange)
![Pays](https://img.shields.io/badge/pays%20support%C3%A9s-29-blue)
![Langue](https://img.shields.io/badge/langue-FR%20%7C%20EN-lightgrey)

---

## Vision

Aujourd'hui, des milliers de gérants de bars et restaurants en Afrique Centrale pilotent leur activité à la main — carnets papier, feuilles Excel, calculs approximatifs — avec pour conséquence des erreurs de caisse, des pertes invisibles et une absence totale de visibilité sur leur rentabilité.

BarManager Pro est une application intégrée tout-en-un, conçue offline-first, qui couvre l'intégralité des besoins opérationnels d'un établissement de restauration : caisse, commandes, stocks, fournisseurs, dettes, conformité fiscale, analytics et gestion de l'équipe. Elle a été pensée dès le départ pour le contexte africain — connexion internet instable, paiements Mobile Money, devises locales, réglementations fiscales par pays.

L'objectif est d'autonomiser les gérants de bar et restaurant en Afrique Centrale en leur donnant les mêmes outils que les grandes chaînes, dans une application simple, rapide et fiable.

---

## Public cible

- 🍺 Bars, brasseries, restaurants, maquis, snacks, buvettes au Cameroun, Gabon, Congo, RCA, Tchad, Guinée Équatoriale, Côte d'Ivoire, RDC, Tanzanie et dans toute l'Afrique Centrale et de l'Ouest
- 👤 Gérants indépendants d'un seul établissement — version Desktop monoposte, installation en un clic
- 🏢 Propriétaires de chaînes multi-établissements — version Web SaaS bientôt disponible
- 📱 Serveurs, caissiers, managers de salle — interface tablette et smartphone en cours de développement

---

## Plateformes supportées

| Plateforme | Statut | Disponibilité |
|---|---|---|
| 💻 Ordinateur Windows 10 / 11 | ✅ Disponible | Téléchargement immédiat |
| 🌐 Application Web SaaS | 🟡 En développement | Bientôt disponible |
| 📱 Application mobile iOS / Android | 🟡 En développement | Bientôt disponible |
| 📊 Tablette tactile (POS) | 🟡 En développement | Bientôt disponible |
| 🐧 Linux (Ubuntu, Debian, Fedora) | 🟡 Prévu | Roadmap 2026 |
| 🍎 macOS (Apple Silicon + Intel) | 🟡 Prévu | Roadmap 2026 |

---

## Modules fonctionnels

BarManager Pro regroupe neuf modules métier entièrement intégrés, accessibles depuis un tableau de bord unifié.

- 💵 **Caisse** — Ouverture et clôture de caisse, gestion du fond de caisse, suivi des écarts et application d'une tolérance configurable
- 🛍️ **POS et Commandes** — Saisie rapide des commandes, gestion des tables, transferts entre tables, fusion de commandes et suivi des statuts en temps réel
- 📦 **Stocks et Magasin** — Catalogue de produits par catégorie, mouvements d'entrée et de sortie, inventaires, seuils d'alerte et suivi des marges
- 🚚 **Fournisseurs** — Annuaire fournisseurs, catalogue d'approvisionnement, bons de commande et réception de marchandises
- 💳 **Dettes et Paiements** — Suivi des créances clients, dettes fournisseurs, historique des remboursements et relances
- 👥 **Équipe et Rôles** — Gestion des utilisateurs et des permissions par rôle, module RH avec fiches employés et bulletins de paie
- 📈 **Analytics** — Tableaux de bord de performance, chiffre d'affaires, top produits, performances par caissier et tendances hebdomadaires et mensuelles
- 🏛️ **Conformité DGI Cameroun** — TVA à 19,25 %, génération de factures conformes à la réglementation, mentions légales obligatoires et NIU
- 🔒 **Sécurité et Backup** — Chiffrement local des données, backup automatique journalier, audit logs des opérations sensibles et récupération de compte par code unique

---

## Spécificités africaines

BarManager Pro n'est pas une application occidentale adaptée à la va-vite. Elle a été conçue natif pour le marché africain.

- ✅ **Mode 100 % hors-ligne** — L'application fonctionne parfaitement sans connexion internet, ce qui est essentiel dans les zones à réseau instable ou saturé
- ✅ **Paiements Mobile Money** — Intégration native d'Orange Money et MTN MoMo pour accepter les paiements directement depuis l'interface
- ✅ **Multi-devises** — XAF (zone CEMAC), XOF (zone UEMOA), CDF (RDC), TZS (Tanzanie), MAD, DZD, TND, EGP, NGN, KES, RWF et autres devises africaines majeures
- ✅ **Multi-pays** — 29 pays africains supportés avec TVA, indicatif téléphonique et fuseau horaire pré-configurés pour chaque pays
- ✅ **Bilingue** — Interface disponible en français et en anglais, avec changement de langue en temps réel sans redémarrage
- ✅ **Conformité fiscale locale** — Factures conformes à la réglementation de la DGI Cameroun, avec extension prévue aux autres pays

---

## Sécurité et confidentialité

La protection des données des établissements est une priorité non négociable.

- Les données sont stockées localement sur l'appareil du client et chiffrées au repos
- Aucune donnée n'est transmise à un serveur tiers sans consentement explicite de l'utilisateur
- Un backup automatique est effectué chaque jour sur le poste local pour prévenir toute perte de données
- Un audit log enregistre toutes les opérations sensibles : encaissements, modifications de prix, suppressions et changements de configuration
- L'authentification est sécurisée avec des mots de passe hashés à douze rounds via bcrypt
- Un système de récupération par code unique permet de retrouver l'accès à un compte sans intervention extérieure

---

## Roadmap

| Version | Date prévue | Faits marquants |
|---|---|---|
| **v1.0.8** | Avril 2026 | Version Desktop stable. Neuf modules complets. Conformité DGI. Mobile Money. 29 pays. |
| **v1.1** | Été 2026 | Application Web SaaS — accès depuis n'importe quel navigateur, synchronisation cloud |
| **v1.2** | Automne 2026 | Application mobile native iOS et Android |
| **v1.3** | Hiver 2026-2027 | Multi-établissements pour les chaînes, API publique REST, SSO entreprise |
| **v2.0** | 2027 | Intelligence artificielle prédictive (alertes stock intelligentes, prévisions des ventes), SSO Microsoft et Google |

---

## Téléchargement

**[Télécharger BarManager Pro v1.0.8 pour Windows](https://github.com/guylain237/barmanagerpro-download/releases/download/v1.0.8/BarManager.Pro_1.0.8_x64-setup.exe)** — 35 Mo, Windows 10/11 64-bit, installation en un clic, aucune configuration requise.

La version Web SaaS sera bientôt disponible sur [https://barmanagerpro.cm](https://barmanagerpro.cm).

---

## Support

- 📍 Équipe basée à **Douala et Yaoundé, Cameroun**
- 💬 Support disponible en **français 🇫🇷 et en anglais 🇬🇧**
- 📧 Email : support@barmanagerpro.cm
- 🌐 Site web : [https://barmanagerpro.cm](https://barmanagerpro.cm)
- ⏱️ Délai de réponse : sous 24h ouvrées en plan Pro, sous 1h en plan Business

---

## Licence et propriété

© 2026 BarManager Pro — Tous droits réservés.

BarManager Pro est une application propriétaire. Son utilisation à des fins commerciales est soumise à l'acquisition d'une licence valide. Pour toute demande de partenariat, d'intégration ou de distribution, veuillez contacter l'équipe à l'adresse indiquée ci-dessus.
