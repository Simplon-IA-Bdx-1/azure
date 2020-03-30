# Préparation DP-100

## AMLS

- calcul scalable
- stockage
- orchestration de workflows => auto train, déploiement et gestion de modèles
- inscription et gestion de modèles
- métrics et supervision pour les données d'entraînement

## Espaces de travail

- un espace par projet?
- création d'un ws depuis un notebook => OK

## AML Interfaces

- AML Studio => Interface web
- SDK AML
<!--? Comment installer les modules bonus -->
<!-- ! pas réussi à créer de fichier de conf depuis `Ws.write_config`  -->
- Instances de calcul = VM en lien avec les ressources de l'espace de travail
  
## Expériences

- suivi de chaque exécution pour pouvoir comparer les résultats de chaque expérience
- on peut log les metrics d'expériences et sauver les outputs de ces expériences
- possibilité d'ajouter des packets via l'objet `CondaDependencies`
