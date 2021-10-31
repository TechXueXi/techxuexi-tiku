# techxuexi-tiku

这是 techxuexi 的专用题库，只存放techxuexi无法自动解决的题目。

**[交流群地址及说明（点击查看）](https://github.com/TechXueXi/TechXueXi/issues/14)**

**我们随时删库跑路，请加交流群防失联。**

官方网站： https://techxuexi.js.org/

**解决每日答题，每周答题，专项答题部分不正常题目无法答题的问题** 

![](https://raw.githubusercontent.com/TechXueXi/TechXueXi/master/img_folder/kjqg.png)  

### [👨‍👨‍👦‍👦   直接参与贡献](https://github.com/TechXueXi/TechXueXi/blob/dev/CONTRIBUTING.md)(内附提交方法)  
如您开发了其他“科技强 guo ”项目，也可以加入本组织，相互交流，共同维护生态。     

20211031管理员补充题库增加方法：

新题库是 techxuexi.json 文件，建议同志们直接提交 pr ，在文件最下面追加。 pr 方法 https://github.com/TechXueXi/TechXueXi/blob/developing/CONTRIBUTING.md

实在不会pr，在下面跟留言。已处理内容会被标记为 resolved 折叠。

格式：

```
{"id":1,"category":"多选","quiz_type":"","question":"古田会议决议规定，新分子的入党条件是：（）；（）；（）；（）；不吃鸦片，不赌博。","tips":['政治观念没有错误的（包括阶级觉悟）', '忠实', '有牺牲精神，能积极工作', '没有发洋财的观念'],"raw_answer":[],"raw_wrongAnswer":[],"answer":"ABCD","wrongAnswer":null,"option":null},

id 序号 必填
category 单选 多选 填空 必填
quiz_type 每日 每周 专项 必填
question 问题 必填
tips 题目提示 必填
raw_answer 原始正确答案 选择题去掉 每个选项 前面的 ABCD 必填 全选可不填
answer 选择题正确选项 选择题必填
填空题 答案写 raw_answer 里 格式 ['一','二']
raw_wrongAnswer,  wrongAnswer 格式同正确答案。
```
