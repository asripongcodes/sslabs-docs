# 介绍 </ins>

## 入门

SCB开发人员平台通过其内置的基础架构配置和测试框架使 DevOps 自动化，从而使开发人员能够在零停机时间内部署代码。本文档提供了该平台，其功能和当前可用的代码模板的快速概述

SCB开发人员平台为数字项目部署提供了两种类型的代码模板：API（可用Node.JS，Java，Python 语言）和 Web（可用React和 Angular 语言）。

注册后，您成为BETA用户。在不久的将来，我们将开放 NON-BETA 版本。

**Step 1: 报名**

请按照以下说明开始使用 SCB Developer Platform。

1.访问[SS Labs网站]（https://www.sslabs.sh/）
2.单击 “GitHub 入门”
3.登录您的GitHub帐户：输入您的 GitHub 登录信息：用户名或电子邮件地址和密码以登录。如果您没有GitHub帐户，请单击“创建帐户”链接以创建一个。

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/Sign+in+with+GitHub.png)

4.通过 GitHub 登录后，您将看到以下登录页面。

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/accept+email.png)

5.检查与您的GitHub帐户关联的电子邮件地址，以获取 SS Labs 邀请加入 SS Labs 的 GitHub 存储库的邀请。

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/GitHub.png)

6.返回到 SS Labs 网站上的同一邀请页面。点击“开始您的旅程！”纽扣

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/accept+email.png)

7. 通过输入团队名称和描述（可选）来设置您的团队。

请注意，目前只能手动将团队成员添加到每个团队。请通过小组成员的电子邮件与 SSLabs /创新实验室小组联系，以将成员添加到您的小组中。

完成后，点击“让我们的代码”按钮。

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/team+setup.png)

8.您将被重定向到 Project Dashboard 页面。

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/team+setup.png)

### 对于那些使用 SCB Developer Platform 部署数字项目的人：

**第2步：创建第一个项目**

1.单击右上角的“创建项目”按钮，或者对于没有任何项目的用户，单击“项目仪表板”标题下的“创建您的第一个项目以开始编码”链接。

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/dashboard.png)

2.从项目仪表板屏幕上的弹出窗口中，选择“创建项目模板”选项（右）。

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/dashboard_+create+project+template.png)

3.从下面的选项卡中选择是创建API还是创建Web模板

### API 模板标签：

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/create+project.png)

### Web 模板选项卡:

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/create+project-1.png)

4.填写：项目名称，项目描述（可选）。请注意，“所有者”字段已经预先填充了您的团队名称，并且只能使用英语和特殊字符“-”。如果您想返回，请单击“返回项目”。 到“项目仪表板”页面。 （这将取消创建新项目。）
5.完成后，点击“代码”按钮。
6.出现“设置”页面。 SCB Developer平台正在为您的项目准备以下内容：
	*  GitHub 上的代码存储库
	*  CI/CD 管道
	*  映像存储库
	*  微服务部署

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/project+provisioning.png)

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/project+provisioning-1.png)

设置完成后，每个方框的圆圈将显示一个勾号。

7. 显示“项目仪表盘”页面

	* 项目数：当前项目数
	* 对于每个项目，在其自己的行中（从左到右）：
	* 对于每个项目，在其自己的行中（从左到右）
	* 类型（API或Web应用程序）
	* 单击“查看项目”的按钮，该按钮会将您带到其“项目详细信息”页面

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/dashboard_+project+list.png)


8. 每个项目的“项目详细信息”页面显示以下内容：

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/project+detail_+project+template.png)

* 项目端点的基本 URL
* 当前部署版本（单击文本右侧的链接将刷新，以在链接和“部署历史记录”中显示最新的部署版本）
* 应用程序日志（重定向到 DataDog）
* “转到 GitHub ”（重定向到项目的 GitHub 代码存储库）
* 克隆（单击以查看并复制项目的 GitHub URL ）
* 来自master分支的部署历史记录（状态可以为“进行中”，“成功”）

DataDog 中的示例应用程序日志如下所示：

示例项目的GitHub页面如下所示：

### 对于那些使用 SCB Developer Platform 托管 GitHub 存储库的人：

**步骤2：创建您的第一个代码存储库**

1. 单击右上角的“创建项目”按钮，或者对于没有任何项目的用户，单击“项目仪表板”标题下的“创建您的第一个项目以开始编码”链接。

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/dashboard.png)

2. 从 Project Dashboard 屏幕上的弹出窗口中，选择“创建代码存储库”选项（右）。

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/dashboard_+create+blank+project.png)

3. 填写项目名称，项目描述（可选）。

*请注意，“所有者”字段已经预先填充了您的团队名称，并且只能使用英语和特殊字符“-”。如果您想返回到“项目仪表板”页面，请单击“返回项目”。 （这将取消创建新项目。）

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/create+blank+project.png)

4. 完成后，点击“让我们的代码”按钮。

5. 您将被重定向回到Project Dashboard页面。请注意，“项目仪表板”页面上的“空白”项目行显示“已完成”而不是“正在运行”状态，并重定向到“ GitHub”（代码存储库）而不是Web或 API。

6. 单击“查看项目”（最右边的按钮）以查看GitHub历史记录。请注意，项目详细信息未显示“基本URL”或“当前部署”。 “ GitHub历史记录”标题右侧没有“应用程序日志”按钮。

![Github](https://sslabs-utility.s3-ap-southeast-1.amazonaws.com/docs_image/project+first+detail+blank+project.png)

**步骤 3：检查当前平台限制**

另请参阅：发行说明[链接]

当前，SCB Developer Platform 允许您使用以下语言创建项目：

1. API 项目
	* Node.JS
	* Java
	* Python

2. 网络项目
	* React
	* Angular