mkdir -p projet_scolaire/{maths,science}: projet_scolaire/maths projet_scolaire/sciences.
cd maths: accède au dossier maths.
touch equation.txt: crée le fichier equation.txt
echo x^2 + y^2 = z^2 > equation.txt: affiche x^2 + y^2 = z^2 dans le fichier  equation.txt
cd ..: remonte dans projet_scolaire.
cd sciences: accède au dossier sciences.
touch experiences.txt: crée le fichier  experiences.txt.
echo eau + huile = séparation > experiences.txt: affiche eau + huile = séparation dans le fichier experiences.txt.
cd ..: remonte dans projet_scolaire.
cd maths: accède au dossier maths.
mv equations.txt geometrie.txt: renome equations.txt en geometrie.txt.
mv /Users/nanafourera/projet_scolaire/sciences/experiences.txt /Users/nanafourera/projet_scolaire/maths: déplace experiences.txt dans maths.
cd ..: remonte dans projet_scolaire.
rm -r sciences: supprime le dossier sciences 
