因为比较喜欢简书的黑夜模式色调，因此动手适配了掘金/简书/CSDN/公众号/玩Android这些站点文章的黑夜模式，去除广告，专注文章内容，给你不一样的阅读体验。

### 具体适配
- 简书：黑夜模式，去除折叠，直接展开全文，去除头部尾部，去广告
- 掘金：黑夜模式，去头部尾部
- 玩Android：黑夜模式，去除头部，右边工具栏，每日一问cookie同步，点赞功能
- CSND：黑夜模式，去除折叠，去广告，去头部尾部
- 公众号：黑夜模式

### 项目地址
[https://github.com/iamyours/Wandroid](https://github.com/iamyours/Wandroid)<br/>
[下载地址v1.0.0](https://github.com/iamyours/Wandroid/releases/download/v1.0.0/wanandroid-v1.0.0.apk)<br/>
[历史版本](https://github.com/iamyours/Wandroid/releases)<br/>

### Flutter版本
[https://github.com/iamyours/flutter_wandroid](https://github.com/iamyours/flutter_wandroid)
- [WebView](https://github.com/iamyours/webview_flutter)基于官方`webview_flutter`改造，添加支持`加载离线资源`，`进度监听`等功能

### 效果图
#### 掘金/简书/CSDN
![掘金](https://github.com/iamyours/Wandroid/raw/master/screen/juejin.gif)
![简书](https://github.com/iamyours/Wandroid/blob/master/screen/jianshu.gif)
![CSDN](https://github.com/iamyours/Wandroid/raw/master/screen/csdn.gif)
#### 玩Android每日问答，项目文章
![每日一问](https://github.com/iamyours/Wandroid/raw/master/screen/wenda.gif)
![项目文章](https://github.com/iamyours/Wandroid/raw/master/screen/project.gif)
#### 公众号
![鸿洋](https://github.com/iamyours/Wandroid/raw/master/screen/wx-hongyang.gif)
![郭霖](https://github.com/iamyours/Wandroid/raw/master/screen/wx-guolin.gif)
![玉刚](https://github.com/iamyours/Wandroid/raw/master/screen/wx-yugang.gif)
![code小生](https://github.com/iamyours/Wandroid/raw/master/screen/wx-code.gif)
![Android群英传](https://github.com/iamyours/Wandroid/raw/master/screen/wx-qunyingzhuan.gif)

### 项目架构
MVVM+Room实现<br/>
网络使用[LiveData+Retrofit](https://juejin.im/post/5d56497f518825107c565d88)(无RxJava),<br/>
路由为[SimpleRouter](https://github.com/iamyours/SimpleRouter)（基于Transform实现，无反射，回调解藕）<br/>
使用`ViewModel`+`DataBinding`解藕业务逻辑。<br/>

### 相关文章整理
- [WebView文章黑夜模式适配](https://juejin.im/post/5d8655535188253f74438ae9)<br/>
- [MVVM模式封装实践](https://juejin.im/post/5d764e54e51d4561d044cd4b)<br/>
- [LiveData+Retrofit网络请求实战](https://juejin.im/post/5d56497f518825107c565d88)<br/>
- [基于Transform实现更高效的组件化路由框架](https://juejin.im/post/5cf35bde6fb9a07ed440e99a)<br/>
- [打造一个简易版ARouter框架](https://juejin.im/post/5cecce216fb9a07f04202904)<br/>