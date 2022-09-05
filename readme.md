# Integration d'une page etudiant
Pour integrer une page étudiant au site il faux créer un nouveaux dossier dans le dossier assets/views avec l'identifiant de l'étudiant: 
 - dans un terminal ouvert à la racine du projet:
    - mkdir assets/views/etudiant-01

Une fois le dossier étudiant créer placer votre code html/css dans ce dossier avec index.html à la racine du dossier étudiant
example : assets/views/etudiant-01/index.html


# Pour être compatible avec l'architecture du site
Dans le dossier étudiant créer précedament retirer tout fichier puis dans un terminal à la racine du projet (pas du dossier étudiant):
    - cp ./assets/views/template-etudiant.html ./assets/views/etudiant-01/index.html (ici on copie le template d'une page étudiant compatible avec la structure du site)
    
## Integration de votre css
Dans le dossier de l'étudiant créer un dossier CSS et placer votre CSS 
Sur la page ajouter le link vers votre CSS à la apres les link CSS de base

## Les médias 
Pour integrer des médias veuillez créer un dossier médias dans le dossier étudiant puis placer vos image à l'interrieur 
Sur votre page étudiant dans la gallerie créer autant de .gallerie-box necessaire pour vos médias