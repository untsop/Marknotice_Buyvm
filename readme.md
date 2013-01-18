### Buyvm 有货通知 Chrome 拓展

#### 简介

由于我最近开始投资白银，希望视野内有一个实时价格，于是就基于 Chrome 的书签 API 做了一个非常粗糙的实时价格书签拓展。

昨天看到 V2EX 上有一个帖子是问如何获得 Buyvm 的库存通知的，我觉得这个通知也适合用同样的方式来展示，所以就收拾了一下代码，改出了一个 Buyvm 库存实时提醒：

![Buyvm 库存实时提醒](https://raw.github.com/unstop/Marknotice_Buyvm/master/assets/buyvm.png)

欢迎基于我的代码开发其他的通知提醒插件~

#### 一些不足

* 由于 Chrome Bookmarks API 限制，拓展无法直接创建一个根目录书签，插件会在“其他书签”文件夹中创建一个书签，需要用户手动把它拖动到书签栏上，像这样：

![手动拖拽到标签栏](https://raw.github.com/unstop/Marknotice_Buyvm/master/assets/drag_and_drop.png)

* 刷新频率的限制：目前 Chrome 浏览器对书签更新的频率有限制，所以无法做到真正的实时刷新。

* 缺少设置项：其实可以搞一个设置页面，允许修改刷新频率，自定义提示信息之类的。不过我比较懒，就没有做。 

#### License

The Marknotice - Buyvm Chrome Extension is under MIT license. You can freely to use or distribute for your project as long as declaring the original copyright information.