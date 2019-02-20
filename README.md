# 从零打造Echarts ——序言
我是一个标题党，也不是。
## 前言
不知道有没有童鞋和我一样，学习了`canvas`基础用法之后只能画几个图形和文字，对如何实现想要的动画仍然无从下手，看着别人家`canvas`酷炫的效果只能徒生艳羡。而我接触`Echarts`后更是想知道其如何做到的。几番搜索只能找到如何实现粒子动画这样的教程，或者介绍一些流行的`canvas`库和其用法，离实现`echarts`以及其它`canvas`库或引擎相去甚远，没有诸如**自己实现vue**、**自己打造react**这样的东西。而搜索`Echarts`源码解析也结果寥寥。我想了想可能有这样几个原因。
- 和`react`等解析不同，`canvas`库解析需要用到很多数学或图形学知识，门槛较高，写起来费时费力别人还不一定懂。
- 对此感兴趣的人可能并不多。
- 我不会搜索。
- 待定。

总之，在这方面，前人提供的经验和教学，我能找到的比较少，只有自己干了！
## 目的
但是本文并不是`echarts`源码解析，而是而是尝试理解并照着`echarts`的设计过程，自己实现一个简易版的`echarts`，即自己的可视化库，。
### 最终目标
- 根据数据输入生成对应的图表，当然只会实现几种，并保留可扩展性。
- 实现`tootip`等基础功能。
- 可个性化。
- 有动画。
### 但是
虽然目标看起来还算简单，也许不用深入`echarts`源码，自己瞎写也能实现。但是这只是代码要实现的目标，而不是我，或者作为本文读者的你的目标。我的目的是深入理解`canvas`库的实现原理以及其软件架构，熟悉`canvas`和涉及到的多方面知识，做到知其然也知其所以然，更能自己随便然。
## 适合读者
- 已有`js`和`canvas`基础。
- 懂一点点`ts`即可，我也不太会，只是为了方便类型提示，所以很多地方写得并不规范，且个人认为不影响阅读。
- 对`canvas`库和细节感兴趣。
- 不浮躁愿意慢慢探究。
- 待定。
## 关于我
能看到这里说明你对本文有一点兴趣，在继续下去之前想先说一下我的情况，避免你看了之后大呼上当。
- 前端码农。
- 非计算机专业，计算机基础不佳，更别提图形学了。
- 18年毕业，工作经验不多，接触的项目也不大，但是类型挺多的。
- 前端相关技能和知识掌握程度还可以，杂七杂八的都知道一些。
- 开源贡献暂无，源码阅读方面只深入了解过`vue`。参考[这里](https://github.com/webbillion/vue-notes)。
- 写作本文时还没开始看`echarts`源码。

以上就是我的基础情况，如果你愿意尝试从一个半吊子笔下发现一些闪光点，欢迎继续。
## 那么
[开始吧！](./Version1.md)
