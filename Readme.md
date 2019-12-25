# 这是厦门大学信息学院的手机APP（测试版） #
__严禁复制本项目__
### 基本介绍 ###
实验中心管理平台。
该应用旨在帮助同学们更加方便、快捷地查询实验室信息，并实现审批流程自动化。
### 更新日志 ###
#### Ver2.2.4.20191225 ####
* 现在日期选择组件不会导致控制台错误了
* 释放实验室和机位后，界面实时刷新

#### Ver2.2.3.20191224 ####
* 系统
- 修正了一个BUG，该BUG曾导致使用POST请求可以无视后台权限验证

* 实验室和机位申请
- 现在，用户可以通过首页的“实验室列表”区域，选择对应的实验室进入申请
- 现在，如果用户因为在该实验室中有正在申请的机位而无法继续申请机位，系统会予以提示，告知哪个机位正在申请中，以便用户查询和释放
- 修改了一个BUG，该BUG曾导致实验室和机位的无法正确释放
- 修改了一个BUG，该BUG曾导致所有用户都可以使用 释放机位和实验室 功能
- 修改了一个BUG，该BUG曾导致实验室申请和机位申请的表单，默认提示词显示错误
- 修改了一个BUG，该BUG曾导致实验室的机位无法全部显示
- 为了使测试过程更加简单，我现将释放权限给予“学生”角色。如何配置已经和@张延坤 说过了

* 重新整理了个人中心，不再允许用户直接申请机位和实验室
* 首页上的通知公告已经正确绑定并且可以使用了
* 我的参与页面增加了“个人申请实验室”查询

#### Ver2.2.2.20191223 ####
* 增加机位申请页面
* 解决个人中心背景图刷新延迟问题
* 增加错误信息提示功能
* 表单样式改进，表单操作按钮样式改进

#### Ver2.2.1.20191220 ####
* 更新获取流程的时机

#### Ver2.2.0.20191218 ####
* 更换个人中心页面

#### Ver2.1.1.20191215 ####
* 删除第一版流程，加快编译速度
* 解决实验室详情卡片不显示信息学院图标的问题
* 更改实验室详细页面，使其可以应对不同种类的实验室

#### Ver2.1.0.20191214 ####
* 修复若干严重bug

#### Ver2.1.0.20191211 ####
* 新闻列表、新闻详细页实现动态绑定

#### Ver2.0.0.20191211 ####
* 更换工作流引擎，实现可配置的工作流
* 各流程页面合并

#### Ver1.1.1.20191209 ####
* 增加权限控制功能

#### Ver1.1.1.20191204 ####
* 修复跳转错误
* 当没有数据时显示“暂无数据”

#### Ver1.1.0.20191202 ####
* 增加“待办事项”组件
* 增加“我的申请”“我的参与”页面
* 更换首页轮播图
* 增加通知公告的轮播功能
* 更换时间日期选择组件
* 完善底部导航栏

#### Ver1.0.2.20191201 ####
* 更改待办事项的显示方式

#### Ver1.0.1.20191130 alpha ####
* 实验室信息组件更新

#### Ver1.0.0.20191128 alpha ####
* 主题风格更换为“学院棕”

#### 历史版本 ####
