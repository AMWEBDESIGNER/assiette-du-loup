# L’Assiette du Loup — maquette indépendante

Vitrine statique pour **L’Assiette du Loup**, restaurant à La Joue du Loup, commune du Dévoluy (05).

## Vérification et sources

- Activité : la fiche de l’Office de tourisme du Dévoluy indique une ouverture aux saisons été 2026 et hiver 2026–2027 ; l’annuaire local toutle05 a été mis à jour par la gérante le 30 avril 2026.
- Sources : [Office de tourisme](https://www.ledevoluy.com/hiver/offres/lassiette-du-loup-la-joue-du-loup-fr-hiver-3736108/), [toutle05](https://www.toutle05.fr/annuaire/l-assiette-du-loup.666024.html), [Pappers — O'BAR'REST'O](https://www.pappers.fr/entreprise/obarresto-900824210).
- Logo : pas de fichier logo officiel réutilisable clairement licencié trouvé ; la signature est une typographie d’attente à substituer par le fichier autorisé.
- Photographies : URLs d’images d’ambiance Unsplash dans `index.html`, sous licence Unsplash ; elles n’illustrent pas l’établissement. Les visuels publics de l’Office servent uniquement de référence territoriale.

## Liens

- GitHub : https://github.com/AMWEBDESIGNER/assiette-du-loup
- Cloudflare Pages : https://assiette-du-loup.pages.dev

## Parcours livré

La page d’accueil est complétée par `menu.html` et `infos.html` : envies de carte, contexte saisonnier, adresse, itinéraire et appel direct. Le site reste une maquette indépendante ; carte, logo, photos, horaires et coordonnées doivent être validés par l’établissement.

## Personnalisation

Remplacer la signature, les photos, coordonnées et périodes avec les éléments validés par l’établissement. Site sans build : `index.html`, `style.css`, `app.js`.

Cette publication est une maquette indépendante, sans affiliation avec l’établissement.

## Motion design et provenance du code

Animations réalisées en CSS vanilla, avec respect de `prefers-reduced-motion`, et une révélation progressive inspirée du pattern public [Scroll animation: IntersectionObserver and CSS](https://codepen.io/oscar-jite/pen/qBzwOVq). La logique reste locale, légère et adaptée à l’identité de chaque établissement ; aucune dépendance payante ni contenu généré n’est requis.

## Informations pratiques livrées

`site-enhance.js` ajoute sur l’accueil un bloc dédié à l’adresse, aux horaires, aux services, au téléphone et à l’itinéraire, ainsi qu’un footer local complet. Les informations signalées « à confirmer » doivent être validées par l’établissement avant mise en production commerciale.
