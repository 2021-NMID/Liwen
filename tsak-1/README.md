# Typora 常用给语法

==（1）标题==

# 一级标题

## 二级标题

### 三级标题

#### 四级标题

##### 五级标题

###### 六级标题

==（2） 字体==

**加粗**
*倾斜*
***斜体加粗***
~~删除线~~

==亮亮==

我是^上标^

我是~下标~（注意用英文字符）



==（3） 列表==

+ 一二三四五
  + 上山打老虎
    + 老虎没达到
      + 达到小松鼠

1. 一二三四五
2. 上山打老虎
3. 老虎没达到
4. 打到小松鼠

==（4)  表格==

| MON    | TUE    | WED    | THU    | FRI    |
| ------ | ------ | ------ | ------ | ------ |
| 上山    | 上山   | 上山    | 上山    | 上山   |
| 到老虎  | 到老虎  | 到老虎  | 到老虎  | 到老虎  |

==（5） 引用==
> 一二三四五
> > 上山打老虎
> > >老虎没达到
> > >
> > >>打到小松鼠

==(6) 分割线==

---------

==（7） 代码
`我是代码`

```
这个代码框
可以用来画流程图什么的
```



# Github的使用

## 1. 目的

借助github 托管项目代码

## 2. 基本概念

==仓库（Repository）==
仓库用来存放项目代码，每个项目对应一个仓库，多个开源项目则有多个仓库

==收藏（Star）==

收藏项目，方便下次查看

==复制克隆项目（Fork）==

![image-20210529163953432](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210529163953432.png)

*注意* ：该fork的项目是独立存在的

==发起请求（Pull Request）==

![image-20210529164432407](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210529164432407.png)

==关注（Watch）==

关注项目，当项目更新可以接收到通知

==事务卡片（Issue）==

发现代码BUG，但是目前没有成型代码，需要讨论时用

==Github主页==

账号创建成功或点击网址导航栏github图标都可以进入github主页；该页面左侧主要显示用户动态以及关注用户或关注仓库的动态；右侧显示所有的git仓库

==仓库主页==
仓库主页主要显示项目的信息，如:项目代码，版本，收藏/关注/fork情况等

==个人主页==
个人信息:头像，个人简介，关注我的人，我关注的人，我关注的git库，我的开源项目，我贡献的开源项目等信息

*注意*  ：

1. 因为github,在国外服务器所以访问较慢或者无法访问，需要翻墙（Shadowsocks)

2. 私有仓库只能自己或者指定的朋友才有权限操作（私有仓库是收费的）
3. 新注册的用户必须验证邮箱后才可以创建git库仓库

##  3. 创建仓库/创建新的项目

####  3.1. 创建仓库

![image-20210529170500131](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210529170500131.png)



#### 3.2.仓库主页说明

![image-20210529170738993](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210529170738993.png)

## 4.仓库管理

#### 4.1.新建文件

![image-20210529171522428](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210529171522428.png)



![image-20210529172026033](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210529172026033.png)

![image-20210529172144229](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210529172144229.png)

#### 4.2. 编辑文件

![image-20210530142545696](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530142545696.png)

![image-20210530142738635](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530142738635.png)

![image-20210530142800909](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530142800909.png)

####  4.3.删除文件

![image-20210530143122277](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530143122277.png)

*思考* ：被删除的文件如何查看信息？

 答案：点击commits按钮查看

#### 4.4.上传文件

![image-20210530143534565](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530143534565.png)

#### 4.5.搜索仓库文件

![image-20210530144126442](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530144126442.png)

==仓库搜索的快捷键（t）==

#### 4.6.下载/检出项目

![image-20210530144622576](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530144622576.png)

## 5.Github Issues

作用：发现代码BUG，但是目前没有成型代码，需要讨论时用；或者使用开源项目出现问题时使用

情景:张三发现李四开源git库，则发提交了一个issue;李四隔天登录在github,主页看到通知并和张三交流，最后关闭issue



![image-20210530145131289](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530145131289.png)

![image-20210530145156463](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530145156463.png)

![image-20210530145303087](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530145303087.png)

![image-20210530145406058](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530145406058.png)

## 6.开源项目贡献流程

#### 1）新建Issue

提交使用问题或者建议或者想法

#### 2)Pull Request

步骤:

+ 1、fork项目
+ 2、修改自己仓库的项目代码
+ 3、新建pull request
+ 4、.等待作者操作审核

# Git的使用

==目的==： 通过git管理github,托管项目代码

## 1.Git的工作流程

#### 1.1.Git工作区域

![image-20210530163214847](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530163214847.png)

#### 1.2.向仓库中添加文件流程

![image-20210530163818377](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530163818377.png)

## 2.Git初始化及仓库创建和操作

#### 2.1.基本信息设置

1. 设置用户名
   git config --global user.name 'xiaobai200168'
2. 设置用户名邮箱
   git config --global user.email '935592918@qq.com'

==注意== ：该设置在github,仓库主页显示谁提交了该文件

#### 2.2.初始化一个新的Git仓库

###### 1).创建文件夹

![image-20210530165224762](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530165224762.png)

###### 2）.在文件内初始化git（创建git仓库）

cd   test

git   init

![image-20210530170120059](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530170120059.png)

#### 2.3. 向仓库添加文件

![image-20210530170346401](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530170346401.png)

![image-20210530170653862](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530170653862.png)

![image-20210530170848113](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530170848113.png)

#### 2.4.修改仓库文件

![image-20210530171928916](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530171928916.png)

![image-20210530172341409](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530172341409.png)

![image-20210530172440723](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530172440723.png)

#### 2.4.删除仓库文件

![image-20210530172646149](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530172646149.png)

## 3.Git管理远程仓库

#### 3.1. 管理远程仓库的目的

作用:  备份，实现代码共享集中化管理


![image-20210530184619242](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530184619242.png)

#### 3.2. Git克隆操作

==目的==: 将远程仓库（github对应的项目）复制到本地

==代码==：git  clone  仓库地址

![image-20210530185802199](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530185802199.png)

仓库地址的由来：

![image-20210530185253765](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530185253765.png)

#### 3.3.将本地仓库同步到git远程仓库中

==代码==： git  push

![image-20210530191511252](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\image-20210530191511252.png)

==思考==：为什么无法同步或没有权限
The requested URL returned error: 403 Forbidden while accessing
答案：私有项目，没有权限，输入用户名密码，或者远程地址采用这种类型:
vi .git/ config

#将

[ remote  "origin"]
       url = https:/ / github .com/用户名/仓库名.git

修改为:
[remote  "origin"]
          url = https://用户名:密码@github . com/用户名/仓库名.git

## 4.Github Pages 搭建网站

#### 4.1个人站点访问

https://用户名.github.io 

#### 4.2搭建步骤

1） 创建个人站点  ->  新建仓库（注：仓库名必须是【用户名.github.io】）

2） 在仓库下新建index.html的文件即可

![img](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\wps2.jpg)

![img](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\wps3.jpg)

![img](C:\Users\86157\Desktop\zuoye\Liwen\tsak-1\typora-user-images\wps4.jpg)

## 5.Project Pages 项目站点

#### 5.1.访问

https://用户名.github.io/仓库名  

#### 5.2.原理

gh-pages 用于构建和发布

#### 5.3.搭建步骤

1）进入项目主页，点击settings

2）在settings页面，点击【Launch automatic page generator 】来自动生成主题页面

3）新建站点基础信息设置

4）选择主题

5）生成网页
