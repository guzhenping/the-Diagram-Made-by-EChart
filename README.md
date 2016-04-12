# the Diagram Made by EChart
------------------
It's a complete and executable demo of diagram. l used E-chart which a open source framework by Baidu.

这是一个完整的可运行的关系图Demo.我用了百度的开源框架EChart.

# Diagram 关系图
-------------------
Echart的关系图主要还是依赖gexf文件和gephi工程，百度自己做的东西倒是不多。所以，想用好关系图，需要从源头入手。特别是，你要展现的数据都将放在.GEXF文件中，必须单独去写入。可使用gephi来新建，也可使用Python脚本。

所以,不要想着echart能一步到位。

# .GEXF文件
-----------------
“.gexf”格式起源于gexf语言。GEXF(Grap Exchange XML Formate)是一种描述复杂网络的结构、关联数据和动态的语言。

更多介绍，可戳链接：https://gephi.org/gexf/format/

其语法规则入门：参见gexf入门手册

# dataTool.js文件
--------------------------------
我在js文件夹中，引入了三个js文件，缺一不可。其中，dataTool.js文件是一个“.gexf文件”读取脚本，提取出数据并展示。




