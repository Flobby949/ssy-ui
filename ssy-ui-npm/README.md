# ssy-ui样式库

## 项目介绍

ssy-ui 是由松山院开发的UI样式库。微信关注松山院公众号，回复“ui”即可获得项目的预览地址。

![松山院](https://mqxu-upload.oss-cn-hangzhou.aliyuncs.com/2022-12-28-IMG_5854.JPG)

## 说明
> 本插件依赖font-awesome@4.7.0，安装本插件的同时也会安装font-awesome。在使用本UI样式库的时候可以直接引用对应的CSS文件：

```javascript
import 'font-awesome/css/font-awesome.min.css';
import 'ssy-ui/css/ssy-ui.min.css';
```


同时，本插件已经使用js文件打包了两个CSS文件，在支持CSS模块的项目里也可以像下面这样直接引用插件：

```javascript
import 'ssy-ui';
```


## 变更记录
0.1.1
- 【Initial】初始版本

0.1.2
- 【Bug Fix】修复发布信息

0.1.3
- 【Add】Panel组件的标题部分添加“查看更多”这种引导链接的样式

0.1.4
- 【Bug Fix】Search 组件指定 z-index，解决和有定位元素同时使用时的层级错乱问题

0.1.5
- 【Bug Fix】loading 组件修改单行加载文字样式

0.1.6
- 【Bug Fix】修复Article组件中图片不居中的问题