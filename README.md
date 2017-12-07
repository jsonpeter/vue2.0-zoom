# vue2.0-zoom

> 基于vue的图片放大镜效果插件

## Build Setup

``` bash
# 安装
npm install vue2.0-zoom

# 引入
import imgZoom from 'imgZoom';

# 标签
  <img-zoom src="img-samll.jpg" width="450" height="250" bigsrc="img-big.jpg" :configs="configs"></img-zoom>

#配置参数
    configs: {
             width:650,
             height:350,
             maskWidth:100,
             maskHeight:100,
             maskColor:'red',
             maskOpacity:0.2
           }
```

有问题欢迎留言、star，详细参数说明：[vue2.0-zoom github] (https://github.com/jsonpeter/vue2.0-zoom)
