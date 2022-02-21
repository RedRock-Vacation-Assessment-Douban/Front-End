# 豆瓣前端
##  仓库地址：https://github.com/RedRock-Vacation-Assessment-Douban/-.git
## 项目线上地址：http://42.192.155.29/
## 项目说明文档：https://www.yuque.com/llance24/ooxl27/vs5lq0
## 项目成员
前端：张益波，后端：袁鑫浩
##  项目的整体结构
主页、登录界面、电影详细页面、影评讨论页面、个人主页、影人页面、热门推荐页面、排行榜、搜索、分类找电影、影评讨论详细页面。
## 项目的亮点、难点
### 亮点
 1、针对电影的功能齐全：短评、影评、讨论、评分、点赞、回复

 2、登录界面的密保和找回密码

 3、搜索采用模糊搜索，输入关键字即可查找相关电影

 4、采用组件化、模块化思想，复用性强，面向对象的编程思想

 5、性能优化：分类区电影较多采用图片懒加载

 6、轮播图做过节流，提高用户体验感

 7、页面重复处采用webpack封装继承
 ### 难点
1、多页面之间交流复杂无法引库搭建路由，通过sessionstorage动态传递参数

2、采用媒体查询进行多页面移动端适配

3、四个轮播图模式各不相同，寻找相似的状态逻辑并且抽象出来进行复用，原生js手写可复用组件

4、评分功能不用框架的前提下在同一页面上实现组件间的通讯

5、点赞功能不用框架的前提下实现同步状态更新并且对接数据库。

6、请求参数复杂，param一一对应困难

