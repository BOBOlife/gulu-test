# Tears - 一个Vue UI组件
[![Build Status](https://travis-ci.org/BOBOlife/gulu-test.svg?branch=master)](https://travis-ci.org/BOBOlife/gulu-test)
## 介绍
这是我在学习Vue的过程中做的一个UI框架，希望对你有用
## 开始使用

1. 添加 CSS 样式
   使用本框架前，请在CSS中开启 border-box
   
   ```css
   *,*::before,*::after {box-sizing: border-box;}
   ```
   IE 8 及以上浏览器都支持此样式

2. 安装 tears-ui
```
npm i --save tears-ui
```
```
# 优先推荐yarn  
yarn add tears-ui
```

3.  引入 tears-ui
```
import {Button,ButtonGroup,Icon} from 'tears-ui'
import 'tears-ui/dist/index.css'

export default {
    name: 'app',
    components:{
        'g-button':Button,
        'g-icon': Icon
    }
}
```


## 文档

官方文档地址:

<a href="http://bobowanglife.gitee.io/gulu-test/">国内点击这里</a>
<br>
<a href="http://bobolife.xyz/gulu-test/">国外点击这里</a>


## 提问

## 变更记录

变更记录地址:

<a href="https://gitee.com/bobowanglife/gulu-test/commits/master">国内点击这里查看</a>
<br>
<a href="https://github.com/BOBOlife/gulu-test/commits/master">国外点击这里查看</a>



## 联系方式

邮箱: bbw1996@qq.com

微信: EternalBoBo

## 贡献代码

作者：塘主无鱼

