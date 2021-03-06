Author: xin  
Date: 2018-3-30

**《CSS网站布局实录》** 是一本中国人写的书，针对web 标准开发，讲解CSS如何做为一个工具来实现web 标准开发的，总体来说还可以，侧重技术的实现，很多实例，实用性很强。

**内容安排:**   
    首先介绍web标准开发是什么，指由之前的table布局转为html+css+js网页实现，秉承内容和样式分离的原则；  
    然后，介绍一下html+css基础知识并针对web网页中的元素，包括一个网页上面常用的布局，导航，内容等介绍CSS实现，  
    除了根据web 标准元素分类介绍之外，还从效果分类层面介绍了常用效果的实现（这一部分和css mastery的内容相似）以及一些高级技巧；  
    最后一部分是browser, edit tool等相关内容，最主要是后面有对一些网站的CSS设计分析，这块内容是很重要的，共有两个，  
    一个是flashempire.com闪客帝国，国内第一个实现web标准网络重构的网站；另一个是国外的adobe-micromedia网站。  
    文中对网站的总体设计，CSS文件架构，核心技术实现进行了介绍，还是比较有用的，这一部分实例的介绍比CSS mastery要好一些。
    
   这本书的内容布局是很不错，但具体内容上总感觉有些不明晰，没有循序渐进的感觉，而且没有全局的意识，侧重实现细节。可以适当参考chapter4-5两章的内容，了解常用的web 元素是如何使用CSS实现的。本书一个优点是，会给出大量的实例，比如某种实现方法都有哪些知名网站在使用等等。

**关于web标准：**  
从技术实现上面指由之前的table布局样式转变为html+css+javascript实现；理念上则是转变为 内容和表现之间的分离。
严格来说，web标准是指为了实现大量HTML信息向XML标准的过渡，W3C和ECMA指定的一系列的技术规范，因此 不仅仅是一个规范，而是一系列规范的总称，  
目前包括XHTML1.0， CSS2.0，ECMA javascript（这是本书成书时间的现状）。

**DIV+CSS：**   
因为CSS中会大量使用DIV，所以CSS又称为DIV+CSS布局。  

**关于网络重构：**  
就是使用html+css+javascript实现之前用table实现的网页站点；  

**关于XHTML：**  
各行各业都有一些“标准”，因为有标准的存在，才使得信息的交流和分享成为现实，如果没有统一的标准，所有的信息都是孤立的，不可分享，不可重用的，因此标准很重要，可以理解为中国的“普通话”。而XML就是我们现有的标准。可以将XML理解为“有规定格式的文档”，只要我们的设备或系统产生的数据都遵守这种格式，就可以实现数据的互相交换和分享。我们目前的网站大多都是使用HTML制作的，而HTML并不符合XML标准，因此这些网页信息很难适应各种设备数据共享的要求，为了解决这个问题，W3C就在 HTML的基础上，按照XML的格式制订了XHTML1.0，只要通过简单的改变，就能将HTML转为XHTML，从而实现向XML的过渡，所以，XHTML就是按照XML规范重新定义的HTML，基本都是格式上更规范了一些，其他没有太大的改变。
