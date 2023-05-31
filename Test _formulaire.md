# Test formulaire

D'abord on s'assurer du bon fonctionnement du formulaire dans le cas ou tout les champs du formulaire sont remplis correctement.

Premier constat, aucun champ n'est marqué comme optionnel. Tout les champs sont donc requis ?


## Test tout les champs remplis "correctement"

on test en remplissant le formulaire comme ceci:
- nom: Letest
- prénom: Juste
- email: juste.letest@partoo.co
- tel: 0777889900
- âge: 01/01/2000
- [x] J'accepte les termes du contrat
- importer une image format png de moins de 5mo

cliquer sur le bouton créer
vérifier que l'on reçois bien un mail de confirmation ou un sms

note:
- peut on remplir le champ âge avec son âge ? (example: 23 )
- le numéro avec le dénominatif en +33

## Test tout les champs remplis "correctement" mais en omettant des champs

on test en remplissant le formulaire comme avant:
- nom: Letest
- prénom: Juste
- email: juste.letest@partoo.co
- tel: 0777889900
- âge: 01/01/2000
- [x] J'accepte les termes du contrat
- importer une image format png de moins de 5mo

tester sans accepter les termes du contrat

cliquer sur le bouton créer
vérifier que l'on est bien notifier d'avoir oublier un champ

## Tester sans rien remplir

cliquer sur le bouton créer
vérifier que l'on est bien notifier d'avoir oublier tout les champs

## Tester de remplir le formulaire avec des champs invalides

- email: juste.letest
- tel: 07 77 88 99
- tester si on peux importer autres choses qu'une image ou dans un format invalides (gif, svg...)
- âge : 01/01/2025

cliquer sur le bouton créer

## Tester de remplir le formulaire avec des champs invalides

- email: juste.letest
- tel: 07 77 88 99

cliquer sur le bouton créer

## Tester le bouton annuler

## Tester l'accessibilité du formulaire

Peut on naviguer dans le formulaire avec tabulation.
Peut on envoyer le formulaire avec la touche entrer

## Tester que le formulaire s'affiche bien sur tout les format

tester sur:
- grand écran 
- petit écran
- smartphone 
- petit smartphone
Pas besoin de tester sur smartwatch je ne pense ;) .

## Tester sur les différent navigateur dans le cas d'un site web

tester sur:
- Chrome
- firefox
- safari 
- éventuellement tester edge, brave, opera mais ils sont normalement basé sur chromium donc cela ne devrais pas changer
Pus besoin de tester sur internet explorer.

## Sécurité

on peut envisager de vérifier que l'on ne puisse pas utiliser le formulaire pour faire des injections SQL qui pourrait compromettre l'infrastructure


## newsletter

vérifier que l'on reçois bien la newsletter et que l'on peux se désabonner.


