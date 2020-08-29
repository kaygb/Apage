Apage 一款静态单页html个人模板。

![](https://cdn.jsdelivr.net/gh/kaygb/picplus-images/20200620200708135236.png)

## 下载

只需要下载index.html即可

## 个性化修改

修改标题名称之后，需要在head标签内的< style>标签内修改`h1::bofore`

~~~css
h1::before{
    content: 'KAYGB\'S HOME'; //修改此处
    position: absolute;
    color: #b2bec348;
    z-index: -1;
    left: 10px;
    top: 10px;
}

~~~

[![](https://img.shields.io/github/license/kaygb/kaygb)](https://github.com/kaygb/Apage/blob/master/LICENSE)
