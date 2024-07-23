# git

1.Chnage the branch

git checkout branchname
git checkout master
git branch new-branch-to-save-current-commits
git fetch --all
git reset --hard origin/master

git checkout -b branchname - create the new branch

Merge
git fetch origin
git merge origin/yourbranc

git pull
git checkout release/1.1.0
git pull origin development

reslove the conflicts then add those files
git add filename
git commit -m "message"
git push

Update password

1.git config --global credential.helper wincred
 git pull
 or
 git pull cloneURL
 
 Git branch rename
 Rename the branch from 1.4 to 1.4.0
 
 git branch -m release/1.4.0
 git push origin :release/1.4

---------

commit message change
git commit --amend
-----------------

Git reset

Reset the working directory
git reset --hard HEAD
 git push --set-upstream origin release/1.4.0
 
 
 Revert the local changes
 git checkout-index -a -f


history

git log file/fldername

Merge only specific changes

git cherry-pick super-long-hash-here
git pusg

Revert to local checkout to according to commit ID



$ git reset --hard 0ad5a7a6   

git stash
unstash
pop

change the commit message
git commit --amend


 Git reset multiple commits

git reset --hard commitID

git push --force-with-lease

which will rewrite history only if no one else has committed to the branch after or within the range of the commits to vapourize



sudo add-apt-repository ppa:git-core/ppa
sudo apt-get update
sudo apt-get install git


yum install curl-devel expat-devel gettext-devel
yum install gcc openssl-devel zlib-devel perl-ExtUtils-MakeMaker
cd /usr/src
wget https://www.kernel.org/pub/software/scm/git/git-2.16.2.tar.gz
tar xzf git-2.16.2.tar.gz
cd git-2.16.2
make prefix=/usr/local/git all
make prefix=/usr/local/git install
echo "export PATH=$PATH:/usr/local/git/bin" >> /etc/bashrc
source /etc/bashrc

git init --bare

 git config --global user.name "balaji2003engg"

 git config --global user.email "balaji2003engg@gmail.com"


git clone pathofrepo

git push origin master
