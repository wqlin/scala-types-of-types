如何贡献？
========

这很简单？

你可以选择在 github 上开一个 issue，写下你想要添加或者改变的（或者想要更深入讨论的）。或者你可以马上创建一个 pull request 记录你的修改建议。


在提交之前请确保这个项目可以正常编译！你可以通过允许 `make` 命令编译这个项目。
如果你想了解更多有关这个文档使用的语言和工具（asciidoctor），请阅读下一小节。

PS: 请_不_要将 `index.html` 包含在你的 pull requests 中，因为当你的 pull request 被接受后它会 *.adoc 文件自动生成。:-)

我应该安装什么软件才能贡献
=========================

* Ruby >= 1.9.3
* bundle (通过 `gem install bundler` 安装)
* Make 
* Asciidoctor (通过 `bundle install` 安装) 

asciidoctor 的语法是什么？
==================================
请使用这个语法参考网站：http://asciidoctor.org/docs/asciidoc-syntax-quick-reference/


我如何能构建 index.html？
==========================

这篇文档使用了一个叫做 "ASCIIDoctor" 的 ASCIIDoc - 这是他们的网站：
http://asciidoctor.org/

简单来说，它和 markdown 非常类似，所以你只要看看文件就可以用直觉理解了;-)

要构建这篇文档，你可以：

```
cd scala-types-of-types

bundle install
make
```

这就可以了。这会产生所有的目标文件。

许可
=========

通过贡献文本/项目/图片/任何东西到这个项目，表示你同意这个仓库的许可（creative commons），详情请查看这个仓库的 LICENSE 文件。