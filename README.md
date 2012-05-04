##Pagination JavaScript Library
�������JavaScript��ҳ���

### ʹ�÷�����  
���룺  
<pre>
&lt;script src=&quot;javascripts/js-pagination.min.js&quot;&gt;&lt;/script&gt;
</pre>

ʹ�ã�  
<pre>
total      : ����
page       : ��ǰҳ
pagesize   : ÿҳ����������
offset     : ƫ����������1 2 3 4 5 6�����6ʱ������4 5 6 7 8 9������ 7 8 9 10 11 12��
length     : ���� ��һҳ 2 3 4 5 6 ��һҳ���򲽳�Ϊ5

var pv = pagination.build( total, page, pagesize, offset, length );
</pre>

���������  
<pre>
pv.total      //����
pv.page       //��ǰҳ
pv.pagesize   //ÿҳ��������
pv.lastpage   //���һҳ
pv.loopcount  //���ƶ��ٷ�ҳ
pv.previous   //ǰһҳ
pv.next       //��һҳ
pv.isprevious //�Ƿ���ʾǰһҳ
pv.isnext     //�Ƿ���ʾ��һҳ
pv.begin      //��ʼ
pv.end        //����
pv.length     //ԭʼ�Ĳ�����������Ĳ�����Ҳ��begin -> endʱ�Ĳ�����
pv.step       //��������ʵ�Ĳ�����
pv.isforward  //�Ƿ����ǰ����ָ&quot;&gt;&gt;&quot;
pv.isback     //�Ƿ���Ժ��ˣ�ָ&quot;&lt;&lt;&quot;
pv.forward    //ǰ�����ڼ�ҳ
pv.back       //���˵��ڼ�ҳ
pv.offset     //ƫ����
</pre>


## ������־��
version 1.0 [2012-05-04]
* �ʺ�����֧��JavaScript�������
* ֧�ָ��ӷ�ҳ

## ��ϵ��ʽ��
* ���ͣ�[k-zone.cn](http://www.k-zone.cn/zblog)
* ΢����[����΢��](http://weibo.com/23784148)
