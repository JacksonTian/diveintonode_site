《深入浅出Node.js》配套网站
=================

## 简介
![深入浅出Node.js](http://img5.douban.com/lpic/s27134708.jpg)

- [豆瓣主页](http://book.douban.com/subject/25768396/)，简介、书评、购买链接请前往。
- [图灵主页](http://www.ituring.com.cn/book/1290)，预览章节，请前往。

同名专栏请前往InfoQ浏览<http://www.infoq.com/cn/master-nodejs>

## 堪误
- 序一。只有你爱好技术 -> 只要你爱好技术
- 30页的`binding.gyp`，`sources`的值应该是`src/hello.cc`
- @吕耿敏 95页中间等价代码段中`fs.readFile("file1.txt")`嵌套中的`fs.readFile`应该是`file2.txt`，不是`file1.txt`
- 56页，tick图，左边还有连线
- 84页，倒数第二行`err` -> `data`
- 85页，`promise.resolve(result);` -> `deferred.resolve(result);` `promise.reject(err);` -> `deferred.reject(err);`
- 147页，取消掉。。。前的注释
- 317页，方法命名处，方法名尽量采用动词或判断性词汇 行 -> 性
- 122页，图5-9上的locol是错误的，应该是`local`。一共两处。
- 143页，`trunk` -> `chunk`

## 相关源码
请访问<https://github.com/JacksonTian/diveintonode_examples>查看相关源码。
