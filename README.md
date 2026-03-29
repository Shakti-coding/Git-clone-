ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

cat ~/.ssh/id_rsa.pub

then copy whole code and put ssh key in github setting 

git remote set-url origin git@github.com:Shakti-coding/Cropper1.git

git init

git add .

git commit -m "Initial commit"

git branch -M main

git push -u origin main

to overwrite use this

git push origin main --force
