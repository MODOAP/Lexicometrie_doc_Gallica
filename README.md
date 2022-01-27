# Lexicometrie_doc_Gallica

Ce script permet de calculer des informations lexicométriques d'une liste de termes au sein d'un corpus de textes numérisés.

Nécessite un compte Google et la synchronisation d'un Drive. 

La liste de termes à rechercher doit être fournie dans la dernière cellule sous forme d'un fichier texte contenant un terme par ligne.

Le corpus à interroger doit être fourni sous forme d'un dossier contenant un ou plusieurs documents Gallica au format json (issus d'un téléchargement depuis Gallica grâce au script Modoap - Téléchargement de texte structuré) (un fichier par document).

Lors d'une première utilisation, le corpus doit subir un pré-traitement linguistique (création d'un fichier .nlp par fichier .json).

Une fois les fichiers .nlp générés, le corpus pré-traité peut être rapidement importé.

Le résultat des calculs est un fichier tableau Google Sheet créé et partagé sur le compte synchronisé, contenant les informations.

Ces résultats peuvent ensuite être représentés dans une interface Web (voir :https://modoap.huma-num.fr/romans_scolaires/)

Calculs lexicométriques réalisés :

- Nombre total de mots du corpus

- Compte des occurrences de chaque terme

- Répartition des termes dans le corpus

Répartition des termes par :

- titre de document
- année de publication
- éditeur de document
- auteur de document

Fréquences des co-occurrences du terme dans une fenêtre donnée :

- pour toutes les co-occurrences
- pour les noms uniquement
- pour les verbes uniquement
- pour les adjectifs uniquement

Concordances des occurrences de chaque terme dans une fenêtre donnée
