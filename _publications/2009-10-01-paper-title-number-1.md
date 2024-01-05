A data-driven personal website：一个数据驱动的个人网站
======

与许多其他基于 Jekyll 的 GitHub Pages 模板一样，academicpages 使您可以将网站的内容与其形式分开。 您网站的内容和元数据在结构化的 Markdown 文件中，而其他各种文件构成主题，指定如何将该内容和元数据转换为 HTML 页面。 您将这些各种 Markdown (.md)、YAML (.yml)、HTML 和 CSS 文件保存在公共 GitHub 存储库中。 每次提交并向存储库推送更新时，[GitHub pages](https://pages.github.com/) 服务会根据这些文件创建静态 HTML 页面，这些页面免费托管在 GitHub 的服务器上。


动态内容管理系统（如 Wordpress）的许多功能都可以通过这种方式实现，使用一小部分计算资源，并且对黑客和 DDoSing 的脆弱性要小得多。 您还可以将主题修改为您喜欢的内容，而无需触及您网站的内容。 如果你在 Jekyll/HTML/CSS 中损坏了一些无法修复的东西，那么描述你的演讲、出版物等的 Markdown 文件是安全的。 您可以回滚更改，甚至删除存储库并重新开始——只需确保保存markdown文件！ 最后，您还可以编写处理站点上结构化数据的脚本，例如分析元数据的[this one](https://github.com/zhoulvbang/zhoulvbang.github.io/blob/master/talkmap.ipynb) 在有关演讲的页面中显示[a map of every location you've given a talk](https://zhoulvbang.github.io/talkmap.html)。
