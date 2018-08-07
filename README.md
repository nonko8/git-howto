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

git push origin :branch-name  
git push origin branch-name  

### import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.  

## Pull
git remote add origin https://github.com/nonko8/{repo-name}.git  
git pull origin master

## Reset
git reset HEAD
git reset --hard

## Other
git remote rm https://github.com/nonko8/{repo-name}.git  
  
## Pull Req
1. 変更を加えたいリポジトリをフォークする
2. ブランチを修正しコミットする
3. リポジトリのトップへ移動し「New pull request」をクリックしてプルリクを作成する
4. プルリク元とプルリク先が正しいことを確認し、問題がなければ「Create pull request」をクリックする
5. コメントを入力し「Create pull request」をクリックする

