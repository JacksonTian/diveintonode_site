《深入浅出Node.js》配套网站
=================

## 简介
![深入浅出Node.js](http://img5.douban.com/lpic/s27134708.jpg)

- [豆瓣主页](http://book.douban.com/subject/25768396/)，简介、书评、购买链接请前往。
- [图灵主页](http://www.ituring.com.cn/book/1290)，预览章节，请前往。

同名专栏请前往InfoQ浏览<http://www.infoq.com/cn/master-nodejs>

## 堪误
- ~~序一。只有你爱好技术 -> 只要你爱好技术~~
- ~~6页，trunk -> chunk~~
- ~~30页的`binding.gyp`，`sources`的值应该是`src/hello.cc`~~
- ~~56页，tick图，左边还有连线~~
- ~~84页，倒数第二行`err` -> `data`~~
- ~~85页，`promise.resolve(result);` -> `deferred.resolve(result);` `promise.reject(err);` -> `deferred.reject(err);`~~
- ~~@吕耿敏 95页中间等价代码段中`fs.readFile("file1.txt")`嵌套中的`fs.readFile`应该是`file2.txt`，不是`file1.txt`~~
- ~~122页，图5-9上的locol是错误的，应该是`local`。一共两处。~~
- ~~126页，第一行，process.memoryUsage()写成momoryUsage了~~
- ~~143页，`trunk` -> `chunk`~~
- ~~147页，取消掉。。。前的注释~~
- ~~165页，倒数第三行`var this = that;`应该改为`var that = this;`~~
- ~~177页，Structs 应该是 Struts~~
- ~~188页，`store.get(id, function(err, sesson){` 参数名错误 应为`session`~~
- 192页，浏览器在收到Etag: "..."这样的请求后 -> 这样的响应后
- ~~228、229页，代码中的`fs.join`应该为`path.join`。~~
- ~~232页，最后一段中文文字，第二行："这里的文件名为bagpipe.js"应该为"这里的文件名为bigpipe.js"。~~
- ~~233页，`<title>Bagpipe示例</title>`应该为`<title>Bigpipe示例</title>`~~
- ~~317页，方法命名处，方法名尽量采用动词或判断性词汇 行 -> 性~~

带横线的为第四印中就修改的堪误
## 相关源码
请访问<https://github.com/JacksonTian/diveintonode_examples>查看相关源码。
