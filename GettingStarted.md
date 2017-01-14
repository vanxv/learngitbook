gitbook有2种模式

1.指令版（cmd指令版：dir\cd\ls）

2.[桌面版](https://www.gitbook.com/editor)（有个软件和word一样用）

安装指令版(linux\mac\win(没试过))

```
npm install gitbook-cli -g
```

启动图书:进一个页面
```
gitbook init
```
SUMMARY.md代码例子
```
# Summary

* [Part I](part1/README.md)
    * [Writing is nice](part1/writing.md)
    * [GitBook is nice](part1/gitbook.md)
----
* [Part II](part2/README.md)
    * [We love feedback](part2/feedback_please.md)
    * [Better tools for authors](part2/better_tools.md)
```

启动服务器
```
gitbook serve
```
[打开http://localhost:4000](http://localhost:4000)

生成网页：
```
gitbook build
```
