# githubtest

1、先输入git remote rm origin 删除关联的origin的远程库
2、关联自己的仓库 git remote add origin https://gitee.com/xxxxxx.git
3、最后git push origin main，这样就推送到自己的仓库了。


git config --global user.name "gggann"
git config --global user.email "thefgfgasdf@163.com"

git commit -m "名称"
git remote rm origin
git remote add origin https://github.com/gggann/githubtest.git
git push origin main
git push -u origin main