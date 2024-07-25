---
layout:       post
title:        "Animate.css动画库下载、安装、使用与解析"
author:       "jaggf"
header-img: "img/post-bg-infinity.jpg"
header-mask: 0.3
mathjax: true
tags:
    - 动画库
    - Animate.css
    - css教程
---
![avatar](https://upload-bbs.miyoushe.com/upload/2024/07/25/192840027/526eaeebaaa97440b4916193fb682fdd_4428561152603494998.png?x-oss-process=image/resize,s_600/quality,q_80/auto-orient,0/interlace,1/format,png)
> 下载、安装、使用与解析[Animate.css动画库](https://animate.style/)。

### 引入插件

```ts
animate动画库的cdn地址：
 
<link href="https://cdn.bootcss.com/animate.css/3.7.2/animate.min.css" rel="stylesheet">

```

简单粗暴的下载方法：复制cdn地址，对源码直接复制，保存到记事本，并更改文件名称为animate.css

![avatar](https://upload-bbs.miyoushe.com/upload/2024/07/25/192840027/c1b995464fe5919c00555565e4e6c5ab_300265911436270335.png?x-oss-process=image/resize,s_600/quality,q_80/auto-orient,0/interlace,1/format,png)

#### 将下载好的animate动画文件添加到自己的项目中，并全局配置使用（common 是自定义文件夹）

```ts
/*引入自定义动画库 animate.css*/
	@import "/common/animate.min.css";
```

#### 使用animate动画库 ： animated + 动画

```ts
<view style="line-height: 25px;" class="animated rotateInUpRight" hover-class="fadeInUp">哈萨克激动啥肯定会进口的哈萨克记得哈卡斯</view>
<view style="line-height: 25px;" class="animated rotateInUpLeft" hover-class="flip">肯定会进口的哈萨克记得哈卡斯</view>
```
![avatar](https://upload-bbs.miyoushe.com/upload/2024/07/25/192840027/e0e70e0c0775da8d215870f8eb7026fb_2479498575733105155.png?x-oss-process=image/resize,s_600/quality,q_80/auto-orient,0/interlace,1/format,png)

效果展示：
![avatar](https://upload-bbs.miyoushe.com/upload/2024/07/25/192840027/f77a362b330c97148d3b58cf56a1fc87_1177515063123573529.png?x-oss-process=image/resize,s_600/quality,q_80/auto-orient,0/interlace,1/format,png)

#### 宝典秘籍：Animate动画库所有动画样式
![avatar](https://upload-bbs.miyoushe.com/upload/2024/07/25/192840027/fd3daf0915b824ce23819d3bac77e9e7_4699581641489456923.png?x-oss-process=image/resize,s_600/quality,q_80/auto-orient,0/interlace,1/format,png)




| Class Name  | 效果  | Class Name  | 效果  |
|-------------|---|---|---|
| bounce      | 上下弹跳 | flash | 闪烁 |
| pulse       | 脉冲  | rubberBand | 橡皮筋式拉动 |
| shake       | 摇晃  | headShake  | 也是摇动   |
| Swing       | 摆动  | tada       | 缩放后晃动 |
| wobble      | 左右晃动 | jello     | 果冻弹弹   |
| bounceIn    | 缩放后弹入 | bounceInDown | 下拉弹入 |
| bounceInLeft| 左侧弹出 | bounceInRight | 右侧弹出 |
| bounceInUp  | 向上弹出 | bounceOut | 弹跳之后隐藏 |
| bounceOutDown| 弹跳之后向下隐藏 | bounceOutLeft | 弹跳之后向左隐藏 |
| bounceOutRight | 弹跳之后向右隐藏 | bounceOutUp | 弹跳之后向上隐藏 |
| fadeIn      | 淡出  | fadeInDown | 下侧淡出拉出 |
| fadeInDownBig | 下拉直接呈现 | fadeInLeft | 左侧淡出拉出 |
| fadeInLeftBig | 左侧拉出 | fadeInRight | 右侧淡出拉出 |
| fadeInRightBig | 右侧拉出 | fadeInUp | 向上淡出拉出 |
| fadeInUpBig | 向上拉出 | fadeOut | 淡入  |
| fadeOutDown | 向下淡出隐藏 | fadeOutDownBig | 向下隐藏 |
| fadeOutLeft | 向左淡出隐藏 | fadeOutLeftBig | 向左隐藏 |
| fadeOutRight | 向右淡出隐藏 | fadeOutRightBig | 向右隐藏 |
| fadeOutUp   | 向上淡出隐藏 | fadeOutUpBig | 向上隐藏 |
| flipInX     | x轴弹出 | flipInY   | y轴弹出 |
| flipOutX    | x轴弹入 | flipOutY  | y轴弹入 |
| lightSpeedIn | 快速拉出(附带菱形效果) | lightSpeedOut | 快速拉入(附带芾菱形效果) |
| rotateIn    | 旋转弹出 | rotateInDownLeft | 上至下左侧旋转弹入 |
| rotateInDownRight | 上至下右侧旋转弹入 | rotateInUpLeft | 下至上左侧旋转弹入 |
| rotateInUpRight | 下至上右侧旋转弹入 | rotateOut | 旋转弹出 |
| rotateOutDownLeft | 上至下左侧旋转弹出 | rotateOutDownRight | 上至下右侧旋转弹出 |
| rotateOutUpLeft | 下至上左侧旋转弹出 | rotateOutUpRight | 下至上右侧旋转弹出 |
| hinge       | 落叶式弹出 | jackInTheBox | 侧身弹出 |
| rolIn       | 左侧向右滚入 | rollOut   | 向右滚出 |
| zoomIn      | 缓慢弹入 | zoomInDown | 下拐弯弹入(赞个) |
| zoomInLeft  | 左拐弯弹入 | zoomInRight | 右拐弯弹入 |
| zoomInUp    | 上拐弯弹入 | zoomOut   | 弹出 |
| zoomOutDown | 下拐弯弹出 | zoomOutLeft | 左拐弯弹出 |
| zoomOutRight | 右拐弯弹出 | zoomOutUp | 上拐弯弹出 |
| slideInDown | 向下侧拉入 | slideInLeft | 左侧拉入 |
| slideInRight | 右侧拉入 | slideInUp | 向上拉入 |
| slideOutDown | 向下拉出 | slideOutLeft | 向左拉出 |
| slideOutRight | 向右拉出 | sideoutUp | 向上拉出 |



[官方演示地址：http://www.jq22.com/yanshi819](http://www.jq22.com/yanshi819)

![avatar](https://upload-bbs.miyoushe.com/upload/2024/07/25/192840027/711b2372944cd4bffea40eb1541db1c7_8864906656129679878.png?x-oss-process=image/resize,s_600/quality,q_80/auto-orient,0/interlace,1/format,png)

&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;*—2024-07-25，jaggf摘录*
