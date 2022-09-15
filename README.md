# Linear-Algebra-and-Matrix-From-Students-Perspective  

## 介绍  

&emsp;&emsp;这是一本线性代数与矩阵分析的快速入门书，致力于40小时内，贯穿线性代数与矩阵分析的核心内容。作者目前是华中师范大学AI专业在读本科生，正在复习线性代数，学习矩阵论，最优化，机器学习等课程。深知数学公共课远不满足专业课的数学要求，故以开源的方式著此书。尽可能以小白的视角来帮助本科生理解线性代数与矩阵分析。  

### 本书的目录结构：
     -Chapter各章节文件夹
     -assets(存放图片)
     -前言.md/preface.md
     -book.md
     -README.md  

### 注意事项  

&emsp;&emsp;book.md作为启动文件，里面有配置信息与各章节文件的导入代码。你需要在vscode里安装插件Markdown Preview Enhance和Markdownlint。其中配置Markdown Preview Enhance 要取消live update功能（因为文件大，实时预览会很卡），Math Rendering Option 使用Mathjax，Puppeteer Wait For Timeout至少设置为3000,以解决右键预览界面使用Puppeteer 输出PDF时,latex代码加载不出来句号。对于markdownlint,是为了统一排版，你应该在VScode的setting.json文件中添加```"markdownlint.config": {
        "MD001": false,
        "MD003": false,
        "MD022": false,
        "MD026": false,
        "MD041": false
    },```代码，以屏蔽这5条规则。
至于插件不懂的地方，可以去在插件管理里，找到对应插件的官方文档链接，进行查看。  

&emsp;&emsp;我希望有更多的人来帮助我完成这本书，你可以在Github上的Linear-Algebra-and-Matrix-From-Students-Perspective仓库克隆代码，然后推送你修改或补充的代码到项目仓库里。  

&emsp;&emsp;你可以帮助我进行内容编写，但是在此之前请先向我发送邮件，告诉我你的思路。
你还可以帮助我美化内容，目前使用markdown来进行快速编写，后期将会发布纯latex版本。

&emsp;&emsp;我的邮箱是2314181884@qq.com，如果你有任何关于内容上的问题，不论是排版还是构思，可以向我发送邮件。期待与你的相遇，让更多的人进入线性世界的殿堂。  

## Introduction  

&emsp;This is a quick start book *Linear Algebra and Matrix From Students' Perspective* for linear algebra and matrix analysis Learning by li yi jia(Eternal-night-blip at github) at Central China Normal University.  

&emsp;I want more people to assist me to finish the book to help helpless undergraduate students in linear algebra course, the student major in AI and Data Science to make a solide foundation of linear algebra and matrix analysis,then for optimization, machine learning, computer graphics and so on.  

&emsp;What can you help me? There are two ways:  
1.assist me in content writing, if you do this, please first send me emails with your ieads then push your markdown codes.  
2.beautify the content, you  need to fork then push. If you have some constructive suggestions, for instance, the rule of layout, please send me an email.  

**My email is `2314181884@qq.com`.**
