# ResearchProject
科研过程中若干的小程序

## 生成比赛结果
### 需求
我实验需要用到SV-COMP21的比赛结构，官方给的网站根本无法下载（速度太慢），还超级大，总是失败。
于是我使用Ctrl+s把网页保存到本地，检查了html文件，发现里面有一个data的json变量。
单独保存该变量为result.json文件。我的目的就是解析这个文件，然后把需要的数据保存在xlsx文件中
### 操作思路
1. 保存出一个json文件
2. 使用python加载文件
3. 把文本内容转化成json对象
4. 分析json格式，输出前4条数据，和原数据对比。正确后准备存入xlsx文件中
5. 从网上找一个生成xlsx方法
6. 先运行网上的demo，然后依样画葫芦，存入数据
### 说明
json文件太大，无法上传，SV-COMP21网站结果如下：

https://sv-comp.sosy-lab.org/2021/results/results-verified/META_Overall.table.html#/
