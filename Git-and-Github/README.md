Some useful Youtube links in an useful order:

[Basics](https://www.youtube.com/watch?v=SWYqp7iY_Tc)

[Basics+](https://www.youtube.com/watch?v=RGOj5yH7evk)

[Advanced](https://www.youtube.com/watch?v=0SJCYPsef54)

How to insert links in markdown(.md) format [Youtube](https://www.youtube.com/watch?v=0aJCGOxeHVk)
\
\
\
\
checking ubuntu version command : 
```
lsb_release -a
```
\
\
installing git on ubuntu commands : 
```
sudo apt update
sudo apt install git
```
\
\
check git version : 
```
git --version
```
\
\
Configuring github :
```
git config --global user.name "user_name"
git config --global user.email "email_id"
```
\
\
Creating a local repository:
```
git init Mytest
```
\
change directory:
```
cd Mytest
```
\
creating a readme file to provide description for the directory:
```
gedit README
```
\
Adding files to index
```
git add README
```
\
Committing changes made to the index:
```
git commit -m "some_message"
```
\
create a repo on github account by selecting the plus icon and the same name as the local one
\
\
\
adding tokens:
github settings->developer settings->personal access tokens->generate new token->copy and save token
\
\
\
connecting and pushing local repo contents to github repo:
```
git branch -M main
git remote add origin https://token@github.com/TheHarbinger99/Mytest.git
git push -u origin main
```
\
