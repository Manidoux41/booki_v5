# Booki.com
## _Projet 2 - Formation developpeur Web - Openclassroom_

[![Github](https://cldup.com/dTxpPi9lDf.thumb.png)](https://github.com/Manidoux41/booki_v5.git)


Voici l’ensemble des points techniques et fonctionnels à prendre en
compte pour le développement du nouveau site Booki. L’ensemble de ces
éléments ont été validés par l’équipe Produit, il est donc important de les
respecter.


- Les usagers pourront rechercher des hébergements dans la ville de
leur choix. Le champ de recherche est un champ de saisie, le texte
doit donc pouvoir être édité par l’utilisateur. Il faut englober ce
champ dans un formulaire pour que ce dernier soit valide auprès du
W3C. La partie recherche ne doit pas être fonctionnelle.
- Chaque carte d’hébergement ou d’activité devra être cliquable dans
son intégralité (pas uniquement le titre). Pour l’instant, les liens sont
vides. On peut utiliser un attribut `href=”#”` pour simuler la
présence d’un lien.
- Les filtres doivent changer d’apparence au survol. Je te laisse décider
de l’effet approprié, je n’ai pas encore eu le temps de me pencher
dessus. Par contre, ils ne doivent pas être fonctionnels.
- Les textes “Hébergements” et “Activités”, situés dans l’en-tête, sont
des liens. Ils doivent mener respectivement vers la section
“Hébergements à Marseille” et “Activités à Marseille

## Spécifications techniques

- Deux maquettes ont été réalisées : l’une desktop et l’autre mobile. Le
site devra être également adapté aux formats tablette. Pour les
tablettes, nous sommes libres de faire les adaptations nécessaires. Il
est important qu’aucun élément ne soit coupé, et que le texte ait
une taille suffisante.
- Concernant les breakpoints, nous avons convenu avec le designer UI
d’utiliser 992 px et 768 px.
992 px pour les écrans d’ordinateurs et 768 px pour les tablettes, et
tout ce qui est en dessous de 768 pour les téléphones portables.
- Il faut d’abord réaliser l’intégration pour les ordinateurs (autrement
dit, en desktop first), puis les tablettes et enfin les téléphones.
L’utilisation des Media Queries nous permettra de réaliser
l’intégration pour les différents supports.
- Plusieurs formats et tailles d’images ont été exportés. Il faudra choisir
le format le plus adapté par rapport à la résolution et au temps de
chargement.
- Les icônes proviennent de la bibliothèque Font Awesome. Nous
pouvons passer par un CDN pour faciliter le chargement des icônes.
- Les couleurs de la charte sont le bleu (#0065FC), une version plus
claire de ce bleu (#DEEBFF) et le gris pour le fond (#F2F2F2).
- La police du site est Raleway. Nous pouvons passer par Google Font
pour importer facilement cette police dans le code :
https://fonts.google.com/specimen/Raleway.
- Il est important d’utiliser les pixels et les pourcentages plutôt que les
REM et les EM.
- Il est important d’utiliser Flexbox plutôt que Grid car c’est la techno
que l’équipe maîtrise le mieux.
- Aucun framework CSS (type BootStrap ou Tailwind CSS) ou
préprocesseur CSS (type Sass ou Less) ne doit être utilisé.
- Il est important d’utiliser des balises sémantiques (type `main`,
`header`, `nav`, etc.).
- Le code doit être valide aux validateurs W3C HTML et CSS.
- La maquette doit être compatible avec les dernières versions de
Google Chrome et de Mozilla Firefox. Il faudra tester le prototype sur
ces deux navigateurs.
- Il n’est pas nécessaire de versionner le code.
Markdown is a lightweight markup language based on the formatting conventions
that people naturally use in email.
As [John Gruber] writes on the [Markdown site][df1]

> A Noter que ce projet a été réalisé dans le délais
> imparti, sans que je n'ai eu besoin de relire l'intégralité
> des cours consacrés au HTML/CSS inhérents à ce 
> module 2 de la formation suivie.
> Ces derniers ayant été respectivement suivi en 2017/2018,  > dans le cadre de ma formation en autodidacte.
> Il peut, néanmoins subsister dans mon code des erreurs qu'un
> initié pourrait trouvé abberrantes. Vous pouvez par  
>   conséquent, prendre ce code en exemple, mais utilisez-le > uniquement si vous êtes dans la capacité d'expliquer 
> comment et pourquoi j'ai utilisé telle ou telle 
> fonctionnalités et ce que ces dernières produisent 
> concrètement. 


## Resultat

Le résultat de mon travail est visible sur la Github page créée à cet effet:

https://manidoux41.github.io/booki_v5/

Plusieurs branches ont été créée, dans un soucis organisationnel. Celà a été en effet plus simple pour moi de partitionner mon code notamment, le CSS(divisé en plusieurs fichiers, chacun d'entre eux dédiés à une section bien précise de mon HTML)

