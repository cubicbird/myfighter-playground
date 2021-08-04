 


> 在 [https://cubicbird.github.io/myfighter-playground/](https://cubicbird.github.io/myfighter-playground/) 打开此页面

## 本项目是myfighter的 角色 开发基础程序

此仓库可以作为 程序模版 进行使用

* 打开 [https://arcade.makecode.com/](https://arcade.makecode.com/)
* 点击 **Import / 导入**
* 选择 from URL
* 黏贴  **https://github.com/cubicbird/myfighter-playground** 并导入、

## 开发过程

请参照模版项目代码进行参照，默认项目中带有一个未命名角色，预设⬇️+A的技能

## 集成

* 切换Javascript
* 将main.ts中所有代码包在 namespace myfighter\_[id]\_dlc.[character_name]()方法中
* **要去掉项目中对playgame.characterMenu()的调用**
* 发布项目获取arcade url
* 利用该url在目标项目中作为extension引入
* 在集成项目调用上述步骤中export的函数


## 编辑此项目 ![构建状态标志](https://github.com/cubicbird/myfighter-playground/workflows/MakeCode/badge.svg)

在 MakeCode 中编辑此仓库。

* 打开 [https://arcade.makecode.com/](https://arcade.makecode.com/)
* 点击 **导入**，然后点击 **导入 URL**
* 粘贴 **https://github.com/cubicbird/myfighter-playground** 并点击导入

## 积木块预览

此图像显示主分支中最后一次提交的块代码。
此图像可能需要几分钟才能刷新。

![块的渲染视图](https://github.com/cubicbird/myfighter-playground/raw/master/.github/makecode/blocks.png)

#### 元数据（用于搜索、渲染）

* for PXT/arcade
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
