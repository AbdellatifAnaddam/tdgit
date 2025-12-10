#les instruction utiliser
•	git init
•	touch ‘index.html’
•	git add index.html / git commit -m ‘creer un fichier’
•	git checkout -b ‘fn/tab’
•	apres la modification sur le fichier index.html on valider les modification avec : git add index.html / git commit -m ' ajouter modifiction dans branch fn/tab ‘
•	git switch master
•	git checkout -b ‘fn/footer’
•	apres la modification sur le fichier index.html on valider les modification avec : git add index.html / git commit -m ' ajouer un footer  dans branch fn/footer ‘
•	git switch fn/tab 
•	git merge fn/footer
•	git switch master
•	git merge fn/tab
