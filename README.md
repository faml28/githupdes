GitHub的强大搜索功能简介
1. 常用词含义
watch：会持续收到该项目的动态
fork：复制某个项目到自己的Github仓库中
star：可以理解为点赞
clone：将项目下载至本地
follow：关注你感兴趣的作者，会收到他们的动态
2. in关键词
公式
xxx关键词 in:name 或 description 或 readme

xxx in:name 项目名包含xxx的
xxx in:description 项目描述包含xxx的
xxx in:readme项目的readme文件中包含xxx的
组合使用
搜索项目名或readme中包含秒杀的项目：seckill in:name,readme
3. start或fork数量的关键词查找
1）公式
(1）xxx关键词 stars 通配符 (:> 或者 :>=)
(2）区间范围数字：数字1..数字2
2）示例
(1) 查找stars数大于等于5000的springboot项目: springboot stars :>=5000
(2) 查找forks数大于500的springcloud项目: springcloud forks:>500
3）组合使用
(1) 查找fork在100到200之间并且stars数在80到100之间的springboot项目：springboot forks:100..200 starts:80..100
4. awesome加强搜索
1）公式
(1）awesome 关键字
awesome系列，一般是用来收集学习、工具、书籍类相关的项目

2）示例
(1) 搜索优秀的redis相关的项目，包括框架、教程等：awesome redis

5. 高亮显示某一行代码
(1) 指定某一行：地址 + #L + 行号: url + #L13
(2) 指定范围行：地址 + #L开始行号-L结整行号：url + #L13-L23
6. 项目内搜索
(1) 英文t
(2) https://help.github.com/en/articles/using-keyboard-shortcuts
7. 搜索区域活跃用户
1）公式
(1）location:地区
location:beijing 

(2）language:语言
language:java

2）示例
(1) 北京地区JAVA方向的用户：location:beijing  language:java
