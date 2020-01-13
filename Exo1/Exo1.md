les réponses ne sont pas Numeroté, on peut donc pas se retrouver

le formatage en markdown n'est pas bien appliquer essai de bien le reviser pour formater ton text

EXERCICE 1
  
  cd ~ 

  mkdir cli_tmp

touch cli_tmp/je_suis_dans_tmp.txt

cd cli_tmp

touch in_cli_tmp.txt

mkdir in_cli_tmp

rm -r je_suis_dans_tmp.txt (* pas la peine d'utiliser l'option -r, pas de réccursivité *)

cd ..

rm -r cli_tmp

mkdir grand_parent parent grand_frere grande_soeur ami connaissances

cd grand_frere

touch bachir.txt

mv bachir.txt ../ami


cp -r ../ami ../parent

rm  ../ami/bachir.txt

pwd

cd ~

rm -r grand_parent parent grand_frere grand_soeur ami connaissance **le dossier cible est `cli_tmp`  et non son contenu**
