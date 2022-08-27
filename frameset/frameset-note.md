<!--
 * @Author: liusuxian 382185882@qq.com
 * @Date: 2022-08-26 14:34:40
 * @LastEditors: liusuxian 382185882@qq.com
 * @LastEditTime: 2022-08-26 17:05:33
 * @FilePath: /study-web-client/frameset/frameset-note.md
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
### 创建 frameset 框架网页的步骤
```
1、创建各个子窗口对应的html文件
2、创建整个框架文件，分别引用子窗口文件
```
### 创建 frameset 框架页面的基本语法
```html
<html>
  <frameset cols="25%,50%,*" rows="50%,*" border="5">
    <frame src="top.html" />
    ......
  </frameset>
</html>
```
```html
注意：<frameset>标签不能与<body>标签同时使用，除非你在<frameset>中使用<noframes>标签
```
### frameset 框架集标签中的常用属性
| 属性 | 值 | 描述 |
| :---: | :------: | :------: |
| cols | pixels、%、* | 定义框架集中列的数目和尺寸 |
| rows | pixels、%、* | 定义框架集中行的数目和尺寸 |