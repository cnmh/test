# Test Manuelle de l'entretien social : 

 ## issues Bloquant
 ## entretien-social : Ajouter beneficier -  
```
SQLSTATE[HY000]: General error: 1366 Incorrect integer value: 'undefined' for column 'tuteur_id' at row 1

```
## rendez-vous : Ajouter rendez-vous-liste-attente : il manque la barre de recherche 
- il manque la barre de recherche des dossiers en liste d'atttente

## rendez-vous : editer THIS ACTION UNAUTHORIZED
- chemin :" http://127.0.0.1:8000/rendez-vous/update/1 "
- error :  403 THIS ACTION IS UNAUTHORIZED.











### issues
## entretien-social : Ajouter tuteur - Le bouton "supprimer" ne fonctionne pas 
```
 App\Repositories\BaseRepository::find(): Argument #1 ($id) must be of type int, string given, called in C:\Solicoders\app\app\Http\Controllers\TuteurController.php on line 148
```

## Notes pour le test de conception
- le manque de seeders pour le test

  

## Notes pour le test des scenario
-   J'ai la possibilité d'ajouter un bénéficiaire sans nécessairement sélectionner de tuteur
