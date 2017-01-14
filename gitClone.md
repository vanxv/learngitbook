#github和gitbook
他们的框架是一样的
一个是电子书的形式呈现
一个是时光机模式

#gitbook
#新建库上传
```
touch README.md SUMMARY.md
git init
git add README.md SUMMARY.md
git commit -m "first commit"
git remote add gitbook https://git.gitbook.com/{{UserName}}/{{Book}}.git
  例：git remote add gitbook https://git.gitbook.com/vanxv/gitbook.git
git push -u -f gitbook master
```
#现有库推送
```
git remote add gitbook https://git.gitbook.com/{{UserName}}/{{Book}}.git
  例：git remote add gitbook https://git.gitbook.com/vanxv/gitbook.git
git push -u -f gitbook master
```

#下载gitbook
```
git clone https://git.gitbook.com/vanxv/gitbook.git
```
#gitbookurl获取
An image: ![gras](image/gitbookurl.png)


#github
新建库直接丢上去就好了。
到首页新建库，然后
