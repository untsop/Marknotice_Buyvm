### Buyvm 有货通知 Chrome 插件

#### 简介

这是一个直接在书签栏显示通知的插件，由于我最近开始投资白银，希望视野内有一个实时价格，所以想到了可以在浏览器的书签栏展示这个信息。

展示 Buyvm 的库存情况也是一种应用，实际上还可以用来展示很多其他的信息。

#### 一些不足

1. 由于 Chrome 的 API 限制，拓展无法直接创建一个根目录书签，插件会在“其他书签”文件夹中创建一个书签，需要用户手动把它拖动到书签栏上，像这样：

	![手动拖拽到标签栏](https://raw.github.com/unstop/Marknotice_Buyvm/master/assets/drag_and_drop.png)

2. 刷新频率的限制

	目前 Chrome 浏览器对书签更新的频率有限制，所以无法做到真正的实时刷新。

3. 缺少设置项
	
	其实可以搞一个设置页面，允许修改刷新频率，自定义提示信息之类的。不过我比较懒，就没有做。 

#### License

The Marknotice - Buyvm Chrome Extension is under MIT license. You can freely to use or distribute for your project as long as declaring the original copyright information.