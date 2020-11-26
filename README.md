# test-ifocop

Description du projet

git branch -vv  // dit on est sur quelle branche on est, je suis sur la branche alpha

git checkout -  //retourne un cran en arriere, je suis sur main (sur mon pc pas sur github)

git branch -D alpha  //efface la branche alpha (sur mon pc dans le dossier .git)

git push origin :alpha  //efface la branche alpha sur github

push = pousser donc tu envoie
pull = tirer donc tu recupere

Pour le moment on voit comment créer un fichier texte distant, l'exporter sur github, le deplacer de branche en branche (donc de sous dossier) et le supprimer ou le rappeler pour modifications.

echo 'content' > newfile.txt //ajoute au content newfile.txt

git stash -u // suppression de tout fichier en cours de modifications

git stash pop  //recuperer les fichiers en cours de modificatione et qui ont été effacé ?
