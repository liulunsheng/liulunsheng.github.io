# 实验一 在Github上用Markdown创建技术博客

## 一、实验目的

1. 熟悉Github网站
2. 掌握Markdown语法

## 二、实验任务

1. 注册Github账号
2. 创建Gihub Pages repository
3. 发布第一篇博客
4. 学习Markdown
5. 利用Hexo生成博客并部署到Github

## 三、实验步骤与结果

1. 注册Github账号

   账号：**liulunsheng**

2. 创建Gihub Pages repository

   Repository名：**liulunsheng.github.io**

3. 发布第一篇博客，如下图所示

   ![img](http://i1.piimg.com/4851/314c43c27ce0ab1f.png)			

   共同协作修改如下图所示：

![img](http://i1.piimg.com/4851/21cf1fa407ac641e.png)

4.  学习Markdown

5. 利用Hexo生成博客并部署到Github

   - 安装**node-v7.7.1-x86**以及**Git-2.12.0-32-bi**

   - 打开[https://npm.taobao.org/](https://npm.taobao.org/)，复制npm指令。

   - **Windows+R**，输入`cmd`,调出窗口，输入之前复制的npm指令。

   - 创建hexo目录，窗口输入

     `cnpm install –g hexo-cli`

   - 路径定位到D盘DM文件下，输入`hexoinit hexo`，进入到hexo文件，

   - 输入`cnpm install`以完成相关配置。                              

   - 窗口输入`hexo server`，运行本地测试，打开[http://localhost:4000/](http://localhost:4000/)。

   - 在github中创建一个repository，名称为**liulunsheng.github.io**。修改hexo文件根目录下的_config.yml文件。

   - 新建博客。输入`hexo new testMyBlog` 生成一片新的文章，将repository中的md文件复制到_posts文件夹下。

   - 生成博客。窗口输入`hexo generate` 指令对原有Html文件进行重新生成；输入`hexo server` 本地预览，输入`hexo deploy` 指令将Html文件发布到Github Pages服务器中。

6. 实验结果

   ![img](http://i1.piimg.com/4851/aa70b88d94ff814e.png)

## 四、实验小结

​	通过学习github以及markdown语言，学会了如何创建自己的博客，也了解了关于markdown语言的一些知识。但还是不够深入，缺乏实践，往后需更加努力。
