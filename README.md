# Git Practice

## base
```shell script
git init
# git config user.name "qiaojianyong"
# git config user.email "qjyoung@163.com"
git add .
git status
git commit -m 'go!'
git remote add origin git@github.com:qjyoung/git-practice.git
git push -u origin master
```

## branch
```shell script
# branch ZGL_出师表
git checkout -b ZGL_出师表
git config user.name "诸葛亮"

# branch GYG_项脊轩志
git config user.name "归有光"
git branch GYG_项脊轩志
git branch
git checkout GYG_项脊轩志
```