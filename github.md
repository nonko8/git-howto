# GitHub
## Initialize / Push
### create a new repository on the command line
echo "# {repo-name}" >> README.md  
git init  
git add README.md  
git commit -m "first commit"  
git remote add origin https://github.com/nonko8/{repo-name}.git  
git push -u origin master  

### push an existing repository from the command line
git remote add origin https://github.com/nonko8/{repo-name}.git  
git push -u origin master  

### import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.  

## Pull
git remote add origin https://github.com/nonko8/{repo-name}.git  
git pull origin master

## Other
git remote rm https://github.com/nonko8/{repo-name}.git  
  
git push origin :branch-name  
git push origin branch-name  
