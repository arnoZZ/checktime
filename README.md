# checktime
mon aide git

git config --global user.email "Vous@exemple.com"

git config --global user.name "Votre Nom"

sudo git remote add origin https://github.com/arnoZZ/checktime


sudo git --work-tree=/opt/checktime/ --git-dir=. commit -a -m ""
sudo git --work-tree=/opt/checktime/ --git-dir=. push --set-upstream origin main

