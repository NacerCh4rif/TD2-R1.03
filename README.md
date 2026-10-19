# Notre Projet
## Notre Distribution Triskel

_Nous avons choisi de vous présenter dans cette partie, notre distribution Triskel que nous sommes actuellement entrain de réaliser._

### L'objectif

Nous avions pour objectif de réussir, à partir d'une image ISO de Triskel 12 Mini, à la modifier afin d'obtenir une distribution prête à l'utilisation pour, notamment des développeurs web. Par ce faire, il fallait que _MariaDB_ ainsi que _Apache_ soit déjà présent, mais également _Forgejo_, une forge virtuelle. 
____
Nous devions également ajouter un maximum de personnalisation à notre distribution. Tout d'abord par l'ajout d'un fond d'écran modifié puis en ajoutant des personnalisation, simplement de style :
- Changement thème ;
- Apparence des dossiers ;
- Apparence du gestionnaire de fichier ;
- La police d'écriture ;
- Apparence des autres icônes ;

Ou encore des personnalisations vraiment utiles comme **des allias** par exemple
____
### Réalisation

Nous avons donc commencé par, chacun de notre coté, nous familiariser avec **Cubic**, qui permet de modifier une ISO déjà existante afin de créer notre propre image ISO avec toutes les fonctionnalités que l'ont voulait ajouter à l'intérieur. Il nous fallait comprendre comment ajouter ajouter les paquets de _MariaDB_, de _Apache_ et de _Forgejo_ ainsi que de le configurer directement via le terminal de configuration de **Cubic**. 
____
Une fois que nous avions compris et acquis les bases, chacun à commencé les recherches sur des parties spécifiques de la configuration :
1. La configuration de _MariaDB_, _Apache_ et _Forgejo_ ;
2. Ajouter le fond d'écran personnalisé ;
3. Ajouter les icônes personnalisées ;
4. Créer le fichier $HOME à partir du _/etc/skel_ ;
5. Trouver des idées de personnalisation supplémentaire ;
____

Décrire toutes ces étapes est en réalité facile, mais la réalisation de chacune d'entre elles nous à demander un gros travail de recherche mais également beaucoup de test par nous même, à modifier des fichiers sur une ISO de test dans l'espoir que les modifications apporter fonctionnent et arrivent au résultat attendu.
____
### Difficultés rencontrées
1. Le terminal de Cubic n'est pas très intuitif, il nous à fallu passer beaucoup de temps à chercher les bonnes commandes ;
2. La documentation est très faible quand à la personnalisation d'une image ISO avec Cubic ;
3. De manière générale, il y a très peu de ~documentation~ sur Cubic ;
4. Le fait de devoir réinstaller une nouvelle machine virtuelle à chaque fois que l'on ajoutait des modifications, en effet, l'installation est assez lente, ce qui nous à fait perdre pas mal de temps ;
5. Enfin, nous avons voulu modifier l'image des dossiers pour les adapter au style de notre "entreprise fictive" ainsi que de notre fond d'écran, toute fois, il nous a été très compliquer de trouver des informations quant à ce sujet.
____
### Pas que du négatif
Même si ce projet a été sur certain aspect assez compliqué à mettre en place et à comprendre, il nous à toutefois permis d'acquérir un grand nombre de connaissance sur le fonctionnement de Triskel et donc d'une distribution de Linux au global. Également, nous avons développer notre capacité à travailler en équipe, puisque ce projet à demandé un investissement personnel de la part de tous les membres du groupe, sans quoi on n'aurait jamais réussi à ~avancer sur le projet et à le terminer à temps~.
___
### Configuration minimum nécessaire à l'utilisation de notre distribution

| |Infos|
|--|--|
|Stockage|20 Go en SSD ou HDD|
|Mémoire|4 Go de RAM|
|Processeur|64bits Intel ou amd64|


