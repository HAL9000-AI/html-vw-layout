# market-project-demo

移动端h5 vw 适配，基于webpack 打包多页面html demo，开箱即用。

适合小白哈，大佬看到点完小星星✨再绕路～小白也别忘记了点个星星！谢谢～

执行步骤： npm install

开发环境 npm run start http://localhost:8080 查看效果

生产打包 npm run build



<br/>
<br/>
<br/>
1、在这里很多人有疑问，为什么要用vw 单位来做适配？vw 和 我们常用rem适配方案有什么优缺点？
<br/>
2、现在对vw 的兼容性支持情况？
<p>
  在移动端 iOS 8 以上、 Android 4.4 以上、包括微信浏览器 新版x5 都支持vw。
  可以去 <a href="https://caniuse.com/#search=vw">Can I use</a> 或者 <a href="https://airen.github.io/css3test/css3test">css3test</a> 查看兼容情况
</p>
<p>
  想要适配低版本、低端机型也不是什么问题、也给出了解决方案。vw 之所以没有流行起来的原因，还是因为在当时兼容性不够，讲白了，就是坑多、大家都不愿意做第一个躺坑的人。<br/>
  几年时间过去，各大厂商对vw 对兼容、低端机型占比逐步减少，vw 的适配方案也慢慢的浮出了水面，大家重新对它有了新的认识。包括我们业界知名的大漠，他们在手淘已经对vw 适配方案有了一年多的实践时间。
</p>
<br/>

3、不支持vw 的浏览器的解决方案？
<br/>
配置方式参考大漠vw解决方案
<a href="https://www.w3cplus.com/mobile/vw-layout-in-vue.html">《如何在Vue项目中使用vw实现移动端适配》</a>
