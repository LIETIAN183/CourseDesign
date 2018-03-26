# 无纸化办公系统

### 可行性分析报告

日期：2018.3.25

项目组成员：王奔、褚一凡



---



目录

1. [问题定义](#definition)
2. [候选解决方案](#solution)
3. [可行性分析](#analysis)
	* (1). [技术可行性分析](#analysis_tech)
	* (2). [经济可行性分析](#analysis_eco)
	* (3). [操作可行性分析](#analysis_operate)
	* (4). [社会可行性分析](#analysis_society)
4. [开发计划](#plan)
	* (1). [资源需求](#resource_require)
	* (2). [进度计划](#schedule)
5. [风险分析](#risk)


---



### <a id = definition>1.问题定义</a>

&emsp;&emsp;传统的公文流转方式繁杂费时，无纸化办公系统大大简化了类似的公文流转处理过程

&emsp;&emsp;该系统也集合了许多其他的办公所需功能：包括人员与职责管理、站内短信、任务提醒等

### <a id = solution>2.候选解决方案</a>

&emsp;&emsp;设计一个后台用于存储用户数据，并编写一个网页供用户在pc以及手机上进行便捷的无纸化办公

<div align = center><img src="https://github.com/LIETIAN183/CourseDesign/blob/master/pics/FlowChart.jpg" width = "300" height = "300" alt = "系统流程图"/></div>


### <a id = analysis>3.可行性分析</a>

##### <a id = analysis_tech> (1).技术可行性分析</a>

&emsp;&emsp;无纸化办公系统许多功能需要后台数据库支撑，可用MySQL、SQL server实现，用户的操作输入由网页的方式获取，可由.NET实现后台数据的提取，由HTML，CSS呈现页面内容

##### <a id = analysis_eco>	(2).经济可行性分析</a>

&emsp;&emsp;无额外硬件成本，人力无需成本

##### <a id = analysis_operate>	(3).操作可行性分析</a>

&emsp;&emsp;无纸化办公系统操作方便，用户只需进行点击、输入文字信息之类的简单操作，即可完成复杂任务

##### <a id = analysis_society>	(4).社会可行性分析</a>

&emsp;&emsp;无纸化办公有助于保护环境，大大减少了办公对纸的需求，自动化的文件流转过程节省了大量的时间，提高办公效率，促进社会进步

### <a id = plan>4.开发计划</a>

##### <a id = resource_require>	(1).资源需求</a>

&emsp;&emsp;需要一台电脑开发以及运行服务器，需要两名学生完成编程任务

##### <a id = schedule>	(2).进度计划</a>

&emsp;&emsp;初步规划如下：

| 周次  |                             任务                             |
| :---: | :----------------------------------------------------------: |
|   3   |                     确定题目、可行性分析                     |
|  4~6  | 设计后台基础服务框架（实现注册登陆等基础功能）与基础前端页面 |
|  7~8  |            完善框架，添加功能，实现人员与职责管理            |
| 10~12 |        继续完善功能，实现任务提醒，站内短信与公文流转        |
| 13~15 |                        页面美化，调试                        |



### <a id = risk>5.风险分析</a>

* 进度可能落后于计划
* 对策：严格按照计划进行项目进程
