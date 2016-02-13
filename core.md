# 前端技术核心知识

### Html -- HyperText Markup Language

* 各种Html标签构成： div、p、h1~6、span、table、svg等等

* html5新引入的标签：section、nav、header、footer、canvas等等

* 为了更好的管理整个Html，定义了一个标准-- HTML DOM，来提供各种接口。

### Css -- Cascading Style Sheets

* css就是对html的一种排版，是一种表现设计语言，主要为了展示html在浏览器中的表现形式。

* 现在一般分为2和3， 3有很大提升和扩展，提升了很大的交互能力。

* 主要是各种属性：display、font、position、float、background、text、color等等

* css的一大特性就是分散，体系不是很规整，灵活，所以产生大量的hack的东西，也由此催生了css预编译器--less，sass，stylus。

### Javascript

* 网络的脚本语言，主要跑在浏览器端，为了给html添加各种动效和交互。最早是一种简单的html扩展表现形式的扩充语言，后来随着浏览器性能的极大提升，整个语言的可操作性大大提高，在前端的重要性与日俱增。

* 最早对html和css的操作主要基于浏览器提供的各种Api--也就是dom(Document Object Model)，由于dom的简单和不易用性，加上网站的复杂性大大上升，产生了各种类库和框架。

* 后面扩展到服务器端，产生了Nodejs这个服务端语言。

### 浏览器

* 最早是Netscape和微软发明，推广，第一次浏览器大战以微软的绑定策略和免费策略获胜。

* 第二次浏览器大战-- google的v8js引擎性能上大大超越微软和其他浏览器，完美胜利，最近苹果和google的分家，以及其他的浏览器厂商目前造成的格局是：Firefox--Gecko引擎，--v8引擎，Safari--webkit引擎，chrome--Blink引擎，IE--Trident内核引擎，Edge--EdgeHTML引擎

* 目前移动端智能手机普及，移动端手机浏览器也有不少-- android、ios、window phone 各不一样。

* 国内的情况更加复杂，因为国内很多互联网厂商自己会封装浏览器--其实方式都是一样，采用chrome开源内核+ie的内核，作为双核主要渲染引擎，然后进行一系列自己的公司认为不错的各种上层封装和优化。

* 由于浏览器众多，造成了一项前端的基本技能--兼容浏览器，js的兼容可以使用开源库： jquery、vue、angular等，css使用hack来兼容。

### 网络

* 整个网页跑在网络的基础上的，所以网络基础知识还是很重要的，包括 http、tcp、ip、udp协议，CDN加速，数据包解析等等。

* 网络是个公共的平台，所以所有人都可以访问，安全性尤为重要，如何防止攻击也是需要掌握的。

* 现在的网络分为弱网络和强网络，以及移动和PC，每个网络的情况不同，针对使用场景是需要做网络性能优化的。