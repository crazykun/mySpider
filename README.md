### go语言爬虫 采集(头条)文章到mysql

根据指定标签爬取对应文章图片，以"年月日"为目录存储。

### RUN

```
导入go.sql到mysql的数据库中

$ git clone git@github.com:crazykun/mySpider.git
$ cd MySpider
$ //main.go后添加需要爬取的标签名
$ go run main.go 街拍 摄影
```

### SCREENSHOT

![2016-12-11 19-31-51](https://cloud.githubusercontent.com/assets/1927478/21079839/4849bd16-bfd9-11e6-8bed-ea2517e11b8a.gif)


### TODO 

> 并发爬取

