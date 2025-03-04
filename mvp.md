# Plant Manager MVP

## Comment on s'y prend
Reprendre les critères du RNCP et les différents modules à valider, et faire notre MVP en fonction

## Les différentes fonctionnalités

### Utilisateurices
  - Page d'inscription : enregistrement pseudo en dur, mais mail / mdp, et autres infos sensibles de façon hashée / cryptée
  - Page de connexion : vérification des informations à l'aide d'une clef de décryptage pour le mdp + penser à la création d'une session pour la navigation entre les pages
  - Page de déconnexion : supprimer la session
  - Page admin
    - Suppression des utilisateurices
    - Modification mdp / pseudos
    - Ajout et modification des plantes présentes en BDD
  - Page de profil : modification mdp / pseudo / autres infos (mais pas le mail)

### Banque de plantes
  - Ajout / suppression de plantes
  - Possibilité d'indiquer quand est la dernière fois qu'elle a été arrosée
  - Possibilité d'indiquer la période de rempotage

### Encyclopédie
  - Listing des plantes d'intérieur
    - Nom français / latin
    - Image (une au moins, plusieurs MVP +)
    - Période de rempotage
    - Substrat préféré (composition du terreau)
    - Comment l'arroser ?
    - Comment la rempoter / comment la bouturer ?
    - Quelle luminosité / emplacement / température ?
    - Description
    - Conseils supplémentaires
