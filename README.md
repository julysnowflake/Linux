# Linux

* github download
sudo apt-get install git-core
sudo add-apt-repository ppa:git-core/ppa
sudo apt-get update
sudo apt-get install git-core
git version

* github setting
git config --global user.name "username"
git config --global user.email "useremail"
git remote add origin https://github.com/username/repositoryname.git

* making file
mkdir Linux
vi helloworld.c
git add helloworld.c
git commit -m "output sentence helloworld"
git push origin master

* change helloworld to hellolinux
vi helloworld.c
git add helloworld.c
git commit -m "change helloworld to hellolinux"
git push origin master
