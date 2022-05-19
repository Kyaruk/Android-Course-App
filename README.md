# Buaa Course

安卓课程作业，采用flutter框架，适用于Android和ios双平台。

## 写在前面

具体项目开发过程在另一团队人员GitHub仓库：https://github.com/cetlewa/buaaCourse

## 文件树结构

在android目录下：

* assets：存放图片和图标
* lib
  * jsons：对象的json结构
  * models：对象的类
  * screens：各个页面
    * course：有关课程列表的页面（含有http请求）
    * home：主页面（包含主页面导航）
      * home.dart、home_detail.dart、home_http.datr为首页代码
      * home_screen.dart是整体样式（底部导航）
      * user.dart是用户页面
    * login：登录和注册页面（含有http请求）
  * my_course：我的课表页面，现在有很大问题：数据为写死的展示数据
  * test：没用的测试文件，测试时直接新建，然后直接用在main里打开即可测试
  * constants：有各种全局常量（颜色等）
  * main：整个app的入口
* pubspec.yaml：依赖
* README：一个没什么用的说明文档，**阅读代码前必看**！

## 使用

Android：apk可从"Android-Course-App\Android app\build\app\outputs\apk\release\app-release.apk"处获取

ios：暂时没有apple的证书，所以实体机请连线进行调试
