<div align="center">

<img src="https://exorp.one/logos/exorp_horizontal_dark.png#gh-light-mode-only" alt="eXorp" width="420" />
<img src="https://exorp.one/logos/exorp_horizontal_light.png#gh-dark-mode-only" alt="eXorp" width="420" />

<br/><br/>

### Connect Deeper — Where AI meets the heart.

**Des rencontres avec un vrai moteur de compatibilité.**
Moins de bruit. Plus de signal.

<br/>

[![Status](https://img.shields.io/badge/status-closed%20beta%202026-6750A4?style=flat-square)](https://exorp.one/fr)
[![Made in Paris](https://img.shields.io/badge/made%20in-Paris%20·%20eu--west--3-E8456B?style=flat-square)](https://exorp.one/fr)
[![GDPR](https://img.shields.io/badge/RGPD-by%20design-6750A4?style=flat-square)](https://exorp.one/fr/privacy)
[![Website](https://img.shields.io/badge/exorp.one-visit-9C64FF?style=flat-square)](https://exorp.one/fr)

[Site web](https://exorp.one/fr) · [Comment ça marche](https://exorp.one/fr#how) · [La science](https://exorp.one/fr#science) · [Presse](mailto:press@exorp.one) · [Contact](mailto:hello@exorp.one)

</div>

---

## À propos

**eXorp** est une application de rencontre qui combine l'attirance visuelle au moteur de compatibilité psychologique le plus transparent du marché. On garde le swipe, les photos, les gestes familiers — et on ajoute un vrai score de compatibilité, calculé en moins de 5 secondes après chaque match.

L'attirance ne suffit plus. EXORP calcule si vous êtes réellement compatibles.

## Comment ça marche

| Étape | Ce qui se passe |
|-------|-----------------|
| **1. Entretien** | Un chatbot conversationnel (Mistral) conduit un échange de 10 minutes pour apprendre comment vous pensez vraiment. |
| **2. Jumeau numérique** | Vos réponses sont converties en six vecteurs d'embedding stockés dans pgvector — votre empreinte de compatibilité. |
| **3. Swipe** | Vous découvrez des profils comme sur n'importe quelle app : photos, âge, distance. |
| **4. Score** | À chaque match, similarité cosinus sur les six dimensions. Score 0–100, statique, transparent. |

## La science : six dimensions, pondérées

| Dimension | Poids |
|-----------|------:|
| Valeurs | **30 %** |
| Intentions | **20 %** |
| Attachement | **20 %** |
| Communication | **10 %** |
| Gestion des conflits | **10 %** |
| Centres d'intérêt | **10 %** |

Modèle ajustable, peer-review ready. Pas de gamification, pas de boost trap, pas de score qui dérive avec le temps.

## Stack & architecture

```
Backend       Laravel 12 · PHP 8.2+
Mobile        React Native · Expo
Database      PostgreSQL + pgvector · Redis
AI            Mistral (entretien) · embeddings 6D
Infra         Scaleway eu-west-3 (Paris) via Ploi
Sécurité      AES-256 at rest · TLS 1.3 in transit · RGPD-compliant retention
```

## Privacy by design

- Données hébergées en Europe (Paris, eu-west-3).
- Chiffrement de bout en bout.
- Logs d'accès auditables.
- Suppression compte + données à tout moment.
- Le RGPD est notre architecture, pas une case à cocher.

## Repositories

Cette organisation héberge le code de la plateforme eXorp. La majorité des dépôts sont **privés** durant la closed beta. Les composants open-source (SDK, outils internes, librairies utilitaires) seront progressivement publiés au lancement public.

## Status

- **v0.1.0** · closed beta 2026
- 500 testeurs actifs
- Ouverture grand public : à venir
- [Rejoindre la liste d'attente](https://exorp.one/fr#cta)

## Contact

- **Général** — [hello@exorp.one](mailto:hello@exorp.one)
- **Presse** — [press@exorp.one](mailto:press@exorp.one)
- **Twitter** — [@exorp_app](https://twitter.com/exorp_app)
- **LinkedIn** — [/company/exorp](https://linkedin.com/company/exorp)
- **Instagram** — [@exorp_app](https://instagram.com/exorp_app)

---

<div align="center">

**eXorp** · Conçu à Paris
© 2026 eXorp. All rights reserved.

</div>
