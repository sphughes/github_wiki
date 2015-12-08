How to set up for Git-Hub


ls -al ~/.ssh
rm ~/.ssh/*
ssh-keygen -t rsa -b 4096 -C "xxxxxxxxxx@yyyyy.com"
ls -al ~/.ssh
cat ~/.ssh/id_rsa.pub 
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
ssh -T git@github.com

