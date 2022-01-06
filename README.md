# Machine learning pour la classification de genres musicaux 🎵

L'objectif de notre projet est de prédire le genre d'un morceau de musique.

Les features choisies pour les trois modèles (KNN, SVM, Random Forest) relèvent d'observations physiques sur le signal de plusieurs fichiers audio. Pour récolter ces données, nous avons utilisé la librairie Librosa sur 990 morceaux divisés en parts égales selon 10 genres. Ces fichiers sont disponibles non pas sur ce dépôt (trop volumineux) mais via le lien suivant https://drive.google.com/drive/folders/12YY4if6Xcg8-s1WlsqS0dXdSRWvysw_D?usp=sharing. La base de données finale est également disponible sur ce dépôt sous le nom "données".

Nous avons par la suite implémenté et comparé trois modèles de classification.

Enfin, à la fin du code, nous avons construit une fonction permettant à l'utilisateur de renseigner n'importe quel fichier audio au format WAV en entrée et d'en sortir le genre musical.

Le notebook complet s'intitule "Code principal".

⚠ Il vous faudra préalablement uploader les fichiers audio (le dossier "data_python") dans votre Google Drive. Si vous sauter l'étape de constitution du dataset, mettez directement le fichier données.csv dans un dossier "data_python".
