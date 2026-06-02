# tentando de novo

# git fetch + git merge (merge to its local)


fazer um push and pull

cd
vim 2.txt #vai abrir o arquivo para poder ser modificado
git add 2.txt
git commit 2.txt -m "add the fourth line" #vai add as modificaçoes
git push

pode dar errado

to clone : 
git clone xxxx


se der errado o clone
git fetch (se fizer git pull direto depoi pode nao dar certo)


Branch - alternative version of the same set of files
    master/main is checked out by default

    Types
        main
        develop
        feature - branch who the main goel is to be merged into the main
        release
        hotfix
        LTS


git br XXXXXX / to create a branch

git br / list of branches

git checkout XXX / to swicht the branch

git branch -d XXXX / delete branch

to reverse after deleting a branch : git checkout xxxxx (number of the branch) -b xxxxx(name of the branch)

if -d doesn't work: try to use -D

cherry-pick: go to main first, put the cherry-pick command with the branch code

fork the project: copy from somewhere else to your project (and you can change it, without changing other persons or your other project)

