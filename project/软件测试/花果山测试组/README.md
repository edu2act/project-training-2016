<img src="../../../image/logo.png"  height="50" />

# 2016级项目实训成果展示 

## 《花果山测试组》 - 软件测试方向

###  测试简介

本次项目实训过程中分为两部分，分别为对《小小猿》App进行自动化测试、对《BugFree》网站进行性能测试。下面对这两个部分分别进行展示。

### 团队成员

- 刘琪（测试经理、测试负责人、测试工程师）
  - Email：[1138322644@qq.com](mailto:1138322644@qq.com) 
  - Github：
- 卢丹琦（测试架构师、测试工程师）
  - Email：[531603273@qq.com](mailto:531603273@qq.com)
  - Github：
- 廉千慧（测试工程师）
  - Email：[597909747@qq.com](mailto:597909747@qq.com)
  - Github：
- 杨斯媛（测试工程师）
  - Email：[437895852@qq.com](mailto:437895852@qq.com)
  - Github：
- 沈梦琪（测试工程师）
  - Email：[shenmq163@163.com](mailto:shenmq163@163.com)
  - Github：
- 范丽梅（测试工程师）
  - Email：[907385640@qq.com ](mailto:907385640@qq.com )
  - Github：
- 黄瑾然（测试工程师）
  - Email：[3029923422@qq.com](mailto:3029923422@qq.com)
  - Github：

### 《小小猿》- 软件测试

#### 项目简介

一款“儿童编程学习App”——让8岁到13岁的孩子初步认识计算机编程，了解儿童计算机编程，锻炼儿童的逻辑思维能力，跟上现代科技的步伐。

使用java+appium进行自动化测试用例的编写，包括：页面对象模式，数据驱动模式。使用uiautomator进行自动化测试用例的编写。使用jenkins+testNG实现持续性集成。并进行压力测试。

#### 项目地址

- Github：[https://github.com/gaya0214/XiaoxiaoYuan_HuaGuoShan](https://github.com/gaya0214/XiaoxiaoYuan_HuaGuoShan)

## # 项目截图

##### Appium-页面对象模式

- 该模式下，创建四个包：base、pages、testcases、utils，在base包中放入BasePrepare类，实现启动和关闭App的功能。utils包中放入操作动作的Action类（例如拖拽、滑动等）。

<p>
<img src="./image/Java测试框架.png" width=120/>
<img src="./image/BaseProp.png" width=330 height=300 />
<img src="./image/Action类.png" width=300 height=300 />
</p>

- pages中根据各页面进行分类，写入每个页面元素的获取和对应的操作，以简化测试用例的编写。

<p>
<img src="./image/Page页面元素.png" width=121 height=300 />
<img src="./image/loginPage.png" width=303 height=300 />
<img src="./image/createPage.png" width=338 height=300 />
</p>

<p>
<img src="./image/模块_xxy.png" width=250 />
<img src="./image/login_xxy.png" width=250 />
<img src="./image/create_xxy.png" width=250 />
</p>

- testcases中存放测试用例，根据系统的功能模块划分，实现具体的业务操作。

<p>
<img src="./image/testcases.png" width=120 height=300 />
<img src="./image/loginTest.png" width=300 height=300 />
<img src="./image/createTest.png" width=300 height=300 />
</p>

##### Appium-数据驱动模式

- 该模式下，创建四个包：bases、pages、testCases、utils，在bases包中放入BaseTest类，实现启动和关闭App的功能。

<p>
<img src="./image/D_测试框架.png" width=200 height=300 />
<img src="./image/D_BaseTest.png" width=352 height=300 />
</p>

- pages包中包括：ElementFinder类和WebDriverEngine类，简化页面元素的查找和元素操作。

<p>
<img src="./image/D_元素查找.png" width=254 height=511 />
<img src="./image/D_webdriver引擎.png" width=478 height=511 />
</p>

- testCases包中存放测试用例，实现具体的业务操作。

<p>
<img src="./image/D_注册Test.png" width=311 height=300 />
<img src="./image/D_MeTest.png" width=149 height=300 />
<img src="./image/D_rankTest.png" width=263 height=300 />
</p>

<p>
<img src="./image/register_xxy.png" width=250  />
<img src="./image/Me_xxy.png" width=250  />
<img src="./image/rank_xxy.png" width=250 />
</p>

- utils包中存放数据驱动类(txt格式和excel格式)以实现大量数据进行测试，使用testNg实现测试失败则截屏并发送邮件的功能。

<p>
<img src="./image/D_txt.png" width=250  />
<img src="./image/D_excel.png" width=250 />
<img src="./image/D_数据驱动.png" width=250 />
</p>

<p>
<img src="./image/testng监听器.png" width=250 />
<img src="./image/D_截屏.png"  width=250 />
<img src="./image/testng发送邮件.png"  width=250 />
</p>

##### uiautomator

- 该测试框架中，BaseTest类中实现App的启动和关闭操作；Action类中实现各页面元素的获取和页面操作；Test类中实现具体的测试用例。

<p>
<img src="./image/ui_BaseTest.png" width=377 height=400 />
<img src="./image/ui_Action_获取页面元素.png" width=407 height=400 />
</p>

<p>
<img src="./image/ui_Action_页面操作.png" width=396 height=400 />
<img src="./image/ui_Testcase.png" width=262 height=400 />
</p>

##### 使用JMeter进行压力测试

- 使用Badboy录制测试脚本，并使用JMeter对脚本进行修改，设计场景，对小小猿APP进行压力测试。

<p>
<img src="./image/Jm1.jpg" width=450 height=253 />
<img src="./image/Jm2.jpg" width=450 height=253 />
</p>

<p>
<img src="./image/Jm3.jpg" width=450 height=253 />
<img src="./image/Jm4.jpg" width=450 height=253 />
</p>


---------------------------------------------------

### 《BugFree3.0.3》 - 软件测试

### 项目简介

BugFree是一个对bug进行在线管理的网站

该次项目是使用LoadRunner和JMeter对BugFree3.0.3进行性能测试，压力测试。通过两款性能测试软件和大量的大并发量的测试用例全面地对BugFree3.0.3进行性能评估。并且使用不同的系统，Windows2003和Windows10，对BugFree3.0.3的适应性和资源利用率进行评估和分析。使用Badboy进行脚本的录制，并且对两大主要事务：新建bug和新建case着重进行测试。

### 项目截图

- bugfree3.0.3登录界面
- bugfree.3.0.3的bug管理界面
<p>
<img src="./image/bugfree3.0.3登录界面.png" width=350 height=250 />
<img src="./image/bugfree3.0.3的bug管理界面.png" width=350 height=250 />
</p>

- bugfree3.0.3的新建bug界面
- bugfree.3.0.3的case管理界面

<p>
<img src="./image/bugfree3.0.3新建bug界面.png" width=350 height=250 />
<img src="./image/bugfree3.0.3的case界面.png" width=350 height=250 />
</p>

- bugfree3.0.3新建case界面 
- bugfree.3.0.3的result管理界面

<p>
<img src="./image/bugfree3.0.3新建case界面.png" width=350 height=250 />
<img src="./image/bugfree3.0.3的result界面.png" width=350 height=250 />
</p>

- LoadRunner的主界面
- LoadRunner中new bug脚本,通过VuGen录制
- LoadRunner中new case脚本，通过VuGen录制

<p>
<img src="./image/LR主界面.png" width=250 height=250 />
<img src="./image/LR的new bug脚本.png" width=250 height=250 />
<img src="./image/LR的new case脚本.png" width=250 height=250 />
</p>

- LoadRunner的Controller界面用于场景设计 
- LoadRunner中new case脚本，30并发量得到的压力测试报告中错误率的图表，是通过LoadRunner中Analysis组件实现的

<p>
<img src="./image/LR的Controller.png" width=350 height=250 />
<img src="./image/new case错误率.png" width=350 height=250 />
</p>

- LoadRunner中new case脚本，30并发量得到的压力测试报告中点击率的图表，是通过LoadRunner中Analysis组件实现的
- LoadRunner中new case脚本，30并发量得到的压力测试报告中吞吐量的图表，是通过LoadRunner中Analysis组件实现的

<p>
<img src="./image/new case30点击率.png" width=350 height=250 />
<img src="./image/new case30吞吐量.png" width=350 height=250 />
</p>

- Badboy脚本录制1 
- Badboy脚本录制2

<p>
<img src="./image/Badboy脚本录制.png" width=350 height=250 />
<img src="./image/Badboy脚本录制2.png" width=350 height=250 />
</p>

- JMeter的场景设计界面 
- JMeter登录脚本界面

<p>
<img src="./image/JMeter场景设计.png" width=350 height=250 />
<img src="./image/JMeter登录脚本.png" width=350 height=250 />
</p>

- JMeter的new bug脚本界面 
- JMeter的new case脚本界面

<p>
<img src="./image/JMeter的new bug脚本.png" width=350 height=250 />
<img src="./image/JMeter的new case脚本.png" width=350 height=250 />
</p>

- 使用JMeter对脚本进行并发执行，并发量为100，事务为50%用户登录，30%写影评，20%做回复

<p>
<img src="./image/JMeter并发100.jpg"/>
</p>

- 使用JMeter对脚本进行并发执行，并发量为100，事务为50%用户登录，30%写影评，20%做回复

<img src="./image/JMeter并发200.jpg" width=800 height=200/>

