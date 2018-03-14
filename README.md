# Arway 's Music
> 这是一款基于vue.js开发的音乐播放器

### 技术栈

> vue.js

---

### 功能介绍

- 推荐页面 
>采用轮播图的方式来展示当前热门歌曲和个人歌单

 ![](http://oz8x9vozq.bkt.clouddn.com/%E6%8E%A8%E8%8D%90.jpg)
- 歌手页面
>展示歌手和歌手详情页面

 ![](http://oz8x9vozq.bkt.clouddn.com/%E6%AD%8C%E6%89%8B%E9%A1%B5%E9%9D%A2.png)
 ![](http://oz8x9vozq.bkt.clouddn.com/%E6%AD%8C%E6%89%8B%E8%AF%A6%E6%83%85%E9%A1%B5.png)
- 排行榜页面
> 展示当前各个系列热门歌曲榜单

 ![](http://oz8x9vozq.bkt.clouddn.com/%E6%8E%92%E8%A1%8C.png)
 ![](http://oz8x9vozq.bkt.clouddn.com/%E6%8E%92%E8%A1%8C%E8%AF%A6%E6%83%85.png)
- 个人中心页面
> 展示自己听歌历史记录以及喜欢的歌曲

 ![](http://oz8x9vozq.bkt.clouddn.com/%E4%B8%AA%E4%BA%BA%E4%B8%AD%E5%BF%83.png)
- 搜索页面
> 可以搜索歌曲，添加歌曲到播放列表

 ![](http://oz8x9vozq.bkt.clouddn.com/%E6%90%9C%E7%B4%A2%E7%95%8C%E9%9D%A2.gif)
- 播放器页面
> 完成播放的上一首，下一首，播放模式，选择喜欢的歌曲

 ![](http://oz8x9vozq.bkt.clouddn.com/sx.gif)
 ![](http://oz8x9vozq.bkt.clouddn.com/l.gif)
> 播放器界面与歌词界面的切换

 ![](http://oz8x9vozq.bkt.clouddn.com/lyric.gif)
> 在播放列表界面往播放列表里面添加歌曲

 ![](http://oz8x9vozq.bkt.clouddn.com/%E6%92%AD%E6%94%BE%E5%88%97%E8%A1%A8%E6%B7%BB%E5%8A%A0%E6%AD%8C%E6%9B%B2.gif)

---

### 项目使用流程

1. 克隆源代码
> git clone git@github.com:ArwayQu/aWsMusic-vue.git
2. 安装项目开发依赖
> npm install
3. 编译源代码
> npm run dev

---

### 项目扩展

- 项目中组件中数据传输全部依赖于Vuex，包括三种播放模式的播放列表，喜欢的歌曲都有其自己的state

- 歌单，歌手，搜索数据全部来源于QQ音乐

- 项目中所用到的轮播，滚动等均来自于[better-scroll](https://ustbhuangyi.github.io/better-scroll/doc/)，有兴趣的同学可以学习一下文档，对以后的开发会有很大的帮助

