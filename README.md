# handlock

# 手势密码demo

# 效果图

![效果图](https://github.com/SCNUchenzhiwen/vue-handLock/blob/master/draw.jpg)
![效果图](https://github.com/SCNUchenzhiwen/vue-handLock/blob/master/error.jpg)
![效果图](https://github.com/SCNUchenzhiwen/vue-handLock/blob/master/empty.jpg)

### 造轮子

内容宽高默认为屏幕宽度70%
** 手势密码组件 @auth chenzhiwen
* @prop {String} [normalColor='#A0AAAD'] - 未激活状态的圆环颜色
* @prop {String} [pointBgColor='rgba(111, 122, 126, .7)'] - 未激活状态的圆的背景色
* @prop {String} [pointActiveColor='#ffffff'] - 激活的圆点颜色
* @prop {String} [lineActiveColor='rgba(255, 255, 255, .3)'] - 激活的连接线的颜色
* @prop {String} [errorColor='#FF3F3F'] - 显示手势密码错误的时候的颜色
* @prop {String} [errorLineColor='rgba(255, 63, 63, .3)'] - 显示错误的时候的连接线的颜色
* @prop {String} [errorTime='3000'] - 手势密码错误显示时间
* @prop {Number} [canWRatio=0.7] - 手势密码区域占屏幕宽度的比例
* @emit getHandLock - 传递手势密码出来 ex: [0, 1, 3]
* @emit clear - 清空绘制的
* @methods errorDraw - 绘制手势密码错误状态

使用直接下载components/handLock文件即可


> handlock

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
