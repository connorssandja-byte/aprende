# Mon profil (copie de Connors)

| | |
|---|---|
| Prénom | Connors |
| Langue maternelle | français |
| Langue apprise | anglais seul (`config.js` : `langs: ['en']`) ; l'espagnol et le lingala restent dans le code, masqués |
| Niveau | B1+ → objectif B2 professionnel |
| Variante | anglais américain, oral en priorité |
| Thèmes | affacturage, démarrage de clients (onboarding), appels, e-mails, chiffres ; football, e-sport, séries |
| Erreurs à traiter | -s de la 3e personne · préposition + -ing · make / do · go to · who / which · pluriel après « one of the » · discours rapporté |
| Prononciation | th, voyelles longues / courtes, R final, lettres muettes |
| Ton | direct et concis |
| Jour du « génère » | vendredi |
| Dépôt | `connorssandja-byte/aprende` |

## Ce qui a changé par rapport à l'appli d'origine

- `config.js` : mode local, pas de progression embarquée, `langs: ['en']`.
- `app.js` : `APP_LANGS` (langues actives) filtre l'accueil, les quotidiennes, les objectifs, les badges et la révision.
- `courses/en.js` : sections « Tes erreurs fossiles » (5 unités) et « Factoring et onboarding » (6 unités, accès libre) en tête ; les unités C1+ / C2 et « Perso » de l'auteur sont retirées.
- `courses/feedback_en_connors.js` : les 88 fiches des nouvelles unités.
- `app.js` : paquet `ENGLISH` et journal vidés, 16 phrases de prononciation ciblées, histoire « The Kickoff Call ».
