# PictureSnowflakesFalling
基于threejs的图片雪花飘落效果，不需要安装额外插件。

点击[这里](https://kaluojushi.github.io/PictureSnowflakesFalling)查看效果。

## 目录结构

```
PictureSnowflakesFalling
│  index.html	//主页面
│  README.md	//说明文档
├─img	//图片文件夹
│      bg.png	//背景图
│      cake.png	//飘落图片
├─js	//JavaScript
│      Snow.js
│      ThreeCanvas.js
└─resources	//其他资源
       bg.jpg
       ParticleSmoke.png
```

## 使用方法

直接运行`index.html`即可，不要更改文件目录结构。

- 修改背景图：修改`index.html`第12行代码：

  ```css
  background: url(img/bg.png) repeat-x;
  ```

  可以更改`repeat`方式。

- 修改飘落图片：修改`index.html`第49行代码：

  ```javascript
  particleImage.src = 'img/cake.png';
  ```

  建议使用透明背景的png图片，并调整好大小（建议在100*100以内）。

- 修改网页标题：修改`title`标签（`index.html`第7行代码）：

  ```html
  <title>图片雪花飘落特效</title>
  ```

## 原版效果

将背景和飘落图片更改为`resources/bg.jpg`和`resources/ParticleSmoke.png`，即为原版雪花飘落效果。

## 参考

- <http://www.jqueryfuns.com/resource/270>
- <https://github.com/Swapnil1898/Enterprises/tree/bee4ca9c1de702d8b9a51a9f7cd82a7bdd7ad5e1/daksha%20enterprises1/js/snow>

