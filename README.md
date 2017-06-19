# kumiao-music

# Vuejs实现酷狗音乐web版 

主要技术栈：
* 1 vue2.0
* 2 vue-router
* 3 vue-resource
* 4 vuex
* 4 mint-ui
* 5 VueAwesomeSwiper Vue-lazyload...

## 写在前面
由于酷狗音乐某些接口并没有开放，所以导致整个项目写起来比较恶心，最后是将百度音乐跟酷狗音乐的api结合起来完成了整个项目，所以在store上对数据的处理会多了点，如百度音乐的MP3文件不能本地播放，只能借助 "歌手+歌名" 调用酷狗搜索接口然后拿到文件播放。一些两边都拿不到数据的只能用本地数据模拟，如歌手列表。可以调用接口的都尽量调，也做了分页功能。
底部音乐盒对比原版的做了随停随关的优化，用rem做了移动端自适应，页面过渡及其他优化也用上了mint-ui、vue-lazyload等组件。

## 项目截图
![](https://ooo.0o0.ooo/2017/06/16/5943a36a80ad9.png)

![](https://ooo.0o0.ooo/2017/06/16/5943a3adc908c.png)

![](https://ooo.0o0.ooo/2017/06/16/5943a3f981287.png)

![](https://ooo.0o0.ooo/2017/06/16/5943a416516a5.png)

![](https://ooo.0o0.ooo/2017/06/16/5943a428c00ac.png)

![](https://ooo.0o0.ooo/2017/06/16/5943a444da58e.png)



## 如何使用

1. 载本项目到本地
2. install下载依赖
3. npm run dev 

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
