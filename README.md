YAAW-CN
====
Dreamy 汉化的 YAAW

YAAW - Yet Another Aria2 Web Frontend，又一个使用纯 HTML/CSS/Javascirpt 制作的 Aria2 网页前台。

无 HTTP 服务器、后台或者服务器端程序。所需的一切就是一个浏览器。

用法
-----
1. 以启用 RPC 的模式运行 aria2，命令如下：
> aria2c --enable-rpc --rpc-listen-all=true --rpc-allow-origin-all

 ***** 警告: 这个选项不会验证调用者的身份。所以地址要保密。 *****

2. 访问 **index.html**.

3. 如果发生 "Internal server error" 错误，更改 "JSON-RPC 路径"设置。


技巧提示
-----
* 在网络上所有你的设置都是临时的。 **在 aria2 重启后，设置将会丢失。**
* 任务(包括还未完成的部分)在 aria2 重启后将会丢失。使用 `--save-session=SOME/WHERE` 并使用 `--continue=true --input-file=SOME/WHERE` 重载可以继续。
* 使用 `$HOME/.aria2/aria2.conf` 保存你的选项。
* 要获得更多关于 aria2 的信息，访问[Aria2 手册](http://aria2.sourceforge.net/manual/en/html/)

组件
----------
+ [Bootstrap](http://twitter.github.com/bootstrap/)
+ [mustache.js](https://github.com/janl/mustache.js)
+ [jQuery](http://jquery.com/)
+ [jQuery Storage](http://archive.plugins.jquery.com/project/html5Storage)
+ [JSON RPC 2.0 jQuery Plugin](https://github.com/datagraph/jquery-jsonrpc)

许可
-------
yaaw 是以 GNU Lesser General Public License 许可授权的。
你可以获取 GNU Lesser General Public License 自 http://www.gnu.org/licenses/lgpl.txt

favicon.ico by [fangke](http://fangke.im/)
