# IDoRemember.github.io
新的一年，新的开始。
https://idoremember.github.io/


#  **不打算在这个IDoRemember.github.io里面写blog了，看起来太麻烦，以后都写issues里面啦~~**

 

 



 




























 

### 2018.02.26 草莓AI微信小程序页面跳转的时候发现了一些知识点，具体看[当天摘抄](https://idoremember.github.io/%E5%BE%AE%E4%BF%A1%E5%B0%8F%E7%A8%8B%E5%BA%8F%E9%A1%B5%E9%9D%A2%E8%B7%B3%E8%BD%AC%E4%B8%89%E7%A7%8D%E6%96%B9%E5%BC%8F%E7%9A%84%E5%8C%BA%E5%88%AB/).
### 2018.02.27 做小程序的时候发现小程序不会像WEB那样进入该页面的时候重新加载初始化，通过小程序的生命周期函数解决了这个问题
[好东西](https://segmentfault.com/a/1190000013331105?utm_source=index-hottest#articleHeader20)
### 2018.02.27 node一些基础知识点 具体看[当天摘抄](https://idoremember.github.io/Node.js%E7%9A%84%E4%B8%80%E4%BA%9B%E5%9F%BA%E7%A1%80%E6%A6%82%E5%BF%B5/). 组件和模块的关系？模块化的诉求解耦，组件化的诉求是好用
### 2018.02.28 词法作用域和动态作用域的区别？词法作用域是函数的作用域在函数定义的时候就决定了，动态作用域的函数作用域是在函数调用的时候才决定的。
### 2018.03.01 js深入学习
### 2018.03.02 微信小程序的裁剪功能（等我文章更新，一堆坑）
### 2018.03.03 js中构造函数、实例原型、实例之间的关系及原型链是什么
### 2018.03.04-07 公司又想做安卓版本了，使用webview，所以我又要写页面了，这几天全部做小程序转react了。 首先我使用wepy安装了wepy-web的依赖 ，然后使用wepy build --output web 指令生成导出 web文件，甚是欢喜以为不要重写了，但其实并不能在web上真正使用，只能看看它的样式，不过可以利用他的结构。之后遇到一个使用fetch上传图片的问题，死活报400错误，后来发现要去掉content-type才有用。如果服务器返回的是一个text类型，需要调用一下reponse.text（）才有用。。。
### 2018.03.08-2018.03.09  过了半天妇女节 然后写了几个小程序页面，练习了一下组件化的wepy 听说美团出mpvue了
### 2018.03.12 使用wepy下的框架版本比较落后，需要更新node，发现windows下无法使用n模块更新，不得不去node官网重新下载node进行更新。。。。。。
### 2018.03.13-14 最近忙着锻炼，今天学了个css3动画，如何做网易云音乐的光盘匀速滚动效果。看flutter ，学着搭了个环境。
```
    animation: fucks 2s infinite linear;
    @keyframes fucks {

    from {

        transform: rotate(0deg);

    }

    to {

        transform: rotate(360deg);

    }

    }
```
### 2018.03.15 利用微信小程序写出了一个自定义样式的音乐播放器，结合的是wepy 待文章更新

### 2018.03.26 react结合百度地图使用的一些问题（写文章中了）
