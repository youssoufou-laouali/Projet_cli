cd ~

 mkdir cli_tmp
 
touch cli_tmp/je_suis_dans_tmp.txt

cd cli_tmp

touch in_cli_tmp.txt

mkdir in_cli_tmp
rm -r je_suis_dans_tmp_txt
cd ..
rm -r cli_tmp
mkdir grand_parent parent grand_frere grand_soeur ami connaissance
cd grand_frere
touch bachir.txt
mv bachir.txt ../ami
cd ../ami ../parent
cp -r ../ami ../parent
rm -r ../ami/bachir.txt
pwd
cd ~
rm -r grand_parent parent grand_frere grand_soeur ami connaissance
