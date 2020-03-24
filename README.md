# 鱼比价 | DzyUserscript
[在 GreasyFork 上安装](https://greasyfork.org/zh-CN/scripts/398609-%E9%B1%BC%E6%AF%94%E4%BB%B7)

A user script for duozhuayu.com, for price comparison.
Basically this is not supposed to be used by English users, so no translation provided for this.

提供 duozhuayu.com 的比价功能。数据来自豆瓣读书。

# 这是什么
显而易见的，这是为二手书店多抓鱼(duozhuayu.com)编写的一个比价脚本。在安装后，当您访问书籍详情页时，详情页下方将会出现其它商店的价格信息。

# 价格数据从哪里来的
价格数据都是直接访问**豆瓣读书**获取的，也就是说安装此脚本后您只会多出对 jQuery 库和豆瓣读书网站的网络请求。

同样的，**商品链接也来自豆瓣读书**，换言之里面会有返利链接——也就是说，这个**返利链接是豆瓣的**。我不会从这个脚本赚取一分钱，请不要对我口诛笔伐，谢谢。

## 为什么不去掉豆瓣的返利
数据是豆瓣的，我想我去掉别人的返利也不道德。况且这样会多出很多跨域请求，我也需要对许多网站进行适配。所以不。

如果你真的非常不爽豆瓣的话，我想应该会有相关去返利的方法，比如拦截请求之类的扩展。不过这与我无关。

都不容易，何必呢。

# 你写这个脚本的动机是什么
当然没必要揣测我的动机，无非就是买了一本书之后发现价格比 JD 全新的还贵，所以写了这个脚本，只是想省省仅有的生活费而已。