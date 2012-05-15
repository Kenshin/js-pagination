##Pagination JavaScript Library
独立版的JavaScript分页组件

### 使用方法：  
引入（独立版）：  
<pre>
&lt;script src=&quot;javascripts/js-pagination.min.js&quot;&gt;&lt;/script&gt;
</pre>
或者（jQuery插件版）：  
<pre>
&lt;script src=&quot;javascripts/jquery.js-pagination.min.js&quot;&gt;&lt;/script&gt;
</pre>

使用（独立版）：  
<pre>
total      : 总数
page       : 当前页
pagesize   : 每页包含的内容
offset     : 偏移量（例如1 2 3 4 5 6，点击6时，产生4 5 6 7 8 9，而非 7 8 9 10 11 12）
length     : 例如 上一页 2 3 4 5 6 下一页，则步长为5

var pv = pagination.build( total, page, pagesize, offset, length );
</pre>

使用（jQuery插件版）：  
<pre>
total      : 总数
page       : 当前页
pagesize   : 每页包含的内容
offset     : 偏移量（例如1 2 3 4 5 6，点击6时，产生4 5 6 7 8 9，而非 7 8 9 10 11 12）
length     : 例如 上一页 2 3 4 5 6 下一页，则步长为5

var pv = $.pagination.build( total, page, pagesize, offset, length );
</pre>

计算后结果（两种版本的计算结果一样）：  
<pre>
pv.total      //总数
pv.page       //当前页
pv.pagesize   //每页的内容数
pv.lastpage   //最后一页
pv.loopcount  //共计多少分页
pv.previous   //前一页
pv.next       //后一页
pv.isprevious //是否显示前一页
pv.isnext     //是否显示后一页
pv.begin      //开始
pv.end        //结束
pv.length     //原始的步长（即传入的参数，也是begin -> end时的步长）
pv.step       //步长（真实的步长）
pv.isforward  //是否可以前进，指&quot;&gt;&gt;&quot;
pv.isback     //是否可以后退，指&quot;&lt;&lt;&quot;
pv.forward    //前进到第几页
pv.back       //后退到第几页
pv.offset     //偏移量
</pre>

其他版本的分页组件：  
Node.js版：[https://github.com/kenshin/node-pagination](https://github.com/kenshin/node-pagination)  
ActionScript版：[https://github.com/kenshin/as-pagination](https://github.com/kenshin/as-pagination)

## 更新日志：
version 1.0 [2012-05-04]
* 适合任意支持JavaScript的浏览器
* 支持复杂分页

version 1.1 [2012-05-14]
* 增加了jQuery插件版（在非插件版的基础上修改而成）
* 增加了测试页面test/test.html

## 联系方式：
* 博客：[k-zone.cn](http://www.k-zone.cn/zblog)
* 微博：[新浪微博](http://weibo.com/23784148)
* 联络：kenshin[AT]ksria.com

## 版权和许可：
Copyright 2012 [k-zone.cn](http://www.k-zone.cn/zblog)  
Licensed under MIT or GPL Version 2 licenses
