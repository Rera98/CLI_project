mkdir personnel: crée le dossier personnel.
cd personnel: accède au dossier personnel.
touch banque.txt sante.txt .mdp: crée les fichiers banque.txt sante.txt et le fichier caché .mdp en un seule commande.
ls -a: affiche tout le contenu du dossier personnel
echo Relevé bancaire janvier. >  banque.txt: affiche Relevé bancaire janvier. dans le fichier  banque.txt.
echo Vaccination complète. >  sante.txt: affiche Vaccination complète.dans le fichier sante.txt .
mv sante.txt  medical.txt: renome  sante.txt en medical.txt.
mkdir documents: crée le dossier documents.
mv /Users/nanafourera/personnel/banque.txt /Users/nanafourera/personnel/documents: déplace le fichier banque.txt dans documents
mv /Users/nanafourera/personnel/medical.txt /Users/nanafourera/personnel/documents: déplace le fichier medical.txt  dans documents.
rm -r .mdp: supprime le dossier caché .mdp.
