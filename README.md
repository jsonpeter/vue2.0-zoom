
# vue2.0-zoom
![](https://img.shields.io/github/stars/pandao/editor.md.svg) ![](https://img.shields.io/github/forks/pandao/editor.md.svg) ![](https://img.shields.io/github/tag/vue2.0-zoom/editor.md.svg) ![](https://img.shields.io/github/release/pandao/editor.md.svg) ![](https://img.shields.io/github/issues/vue2.0-zoom/editor.md.svg) ![](https://img.shields.io/bower/v/editor.md.svg)

#### 基于vue的图片放大镜效果插件

> [演示地址](http://jsrun.net/nmiKp/show)

#### 安装
``` npm install vue2.0-zoom ```

#### 引入
``` import imgZoom from 'vue2.0-zoom' ```
### 组件
```  components: { imgZoom } ```
#### 标签
 ```
 <img-zoom src="img-samll.jpg" width="450" height="250" bigsrc="img-big.jpg" :configs="configs"></img-zoom>
 ```

#### 配置参数
```
    configs: {
             width:650,
             height:350,
             maskWidth:100,
             maskHeight:100,
             maskColor:'red',
             maskOpacity:0.2
           }
```
有问题欢迎留言、star，详细参数说明
> [Github地址](https://github.com/jsonpeter/vue2.0-zoom)
