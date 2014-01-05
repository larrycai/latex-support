## latex-support ##

This is the book generated from markdown, it needs support for latex issues

Follow command is used to generate PDF, so far it is ok to use [CTEX](http://www.ctex.org/) full version to compile it.

	$ xelatex main.tex

And I want to have minor packages to make it work in Windows, so I prefer to use [miktex-portable](www.miktex.org/portable) version.

While so far it doesn't work for miktex portable version, I guess there are latex syntex error somewhere.

**Issue 1** how to use [miktex-portable](www.miktex.org/portable) to make it compilable

Since it is written in Chinese, it will be nice to use ctex/xeCJK as template

**Issue 2** update `main.tex` to use ctex/xeCJK as new template

Thanks