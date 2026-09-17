# atlas-site

Le site public d'[Atlas](https://gregoirelacoste.github.io/atlas-site) — **le build seul, jamais la source**.

Ce dépôt ne contient aucun code d'Atlas. Il porte deux choses :

- **`gh-pages`** — le site rendu, poussé par la release d'Atlas, en un commit orphelin à chaque fois (il n'y a pas d'histoire à lire ici, c'est voulu) ;
- **`main`** — le formulaire d'inscription à la bêta (`.github/ISSUE_TEMPLATE/beta.yml`) et l'automate qui invite (`.github/workflows/beta.yml`).

## S'inscrire à la bêta

Le paquet d'Atlas est privé pendant la bêta. [Ouvre une demande](../../issues/new?template=beta.yml) — le formulaire est **public**, n'y mets rien que tu ne dirais pas en public. Si c'est oui, une invitation en lecture sur le dépôt de distribution `atlas-dist` t'arrive par mail : c'est elle qui donne le droit d'installer, avec un jeton `read:packages` à toi. La page [Installer](https://gregoirelacoste.github.io/atlas-site/installer) donne les trois lignes.
