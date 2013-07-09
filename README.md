wizcalendar
===========

chinese calendar （重构寿星天文万年历）

许剑伟先生(福建莆田第十中学)的“寿星”天文万年历，是一款真正精确的万年历，它提供西元-4712年到西元9999年的西历及农历日期查询。

寿星万年历采用先进的天文算法，使用javascript实现，可以说是目前为止最好的万年历实现版本。但是许先生毕竟不是专业的程序员，所以程序代码写的很杂乱，非常不符合程序规范，也不符合程序库的规范，也不符合W3C的标准。

在各种浏览器中的兼容性极差，极大地影响了这套代码的复用，枉费了许先生艰辛地研究天文算法的一翻心血。

我在网上等了，很久希望有高人能把这套优秀的代码，整理成为优秀的程序库。但是几年过去了，依然如此。

我只好亲自操刀了，把全部代码进行重构。

第一步，以许先生的早期1.1版本（ 寿星万年历：http://www.fjptsz.com/xxjs/xjw/rj/113.htm  设计:许剑伟），做为蓝本，因为这个是早期最简版本，容易下手。
    主要工作是提取一些基础类。如：Angle（角）、JDate（儒略日）、Coord（坐标）
第二步、对天文算法进行重构
    主要工作是坐标换、岁差、光行差、章动、地球位置和月球位置计算。
第三步、农历计算

第四步、重构寿星天文万年历（5.05）版

第五步、开发JQuery和Mootools插件

第六步、开发Java、C#等版本