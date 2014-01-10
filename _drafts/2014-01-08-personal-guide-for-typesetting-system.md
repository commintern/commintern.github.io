---
layout: post
title: Personal Guide for Scientific Typesetting, Presentation and Something Else
description: Personal Guide for Typesetting System and something else
categories: 
- article
- en
tags: Typsetting, TeX
---

This is a personal and self-guided article for softwares related scientific typesetting. It is not informative for everyone, perhaps, but I hope it is a worthy sharing.

# Typesetting System

## [WYSIWYG](http://en.wikipedia.org/wiki/WYSIWYG)
Almost everyone (in China) in my age started to learn Microsoft Office Word as a document processor. WYSIWYG typesetting is just simple clicks.  Next sections describe my personal experience with those softwares.

### Word in Miscrosoft Office

Of course, Word as well as other softwares in Office is excellent without considering its price. However, when I began to write scientific documents in university, it became a nightmare. 

1. Previous version of Word does not support math equation. After 2010, the function is finally added. However, the cilck-style writing is slow and hard to maintain.

2. [Mathtype](http://www.dessci.com/en/products/MathType/). One advantage is it supprots \\( \LaTex \\) syntax. However, it is hard to use sometimes and inefficient. If I try to copy one equation to another Word file or Powerpoint file, it becomes a picture. It means I can not fix mistakes any furthur.

3. The functions of markup style typesetting actually are supported well by Word. But most of they are somehow hidden from users. I tried to learn so called "80% unkown functions". I found a (chinese) [book](http://book.douban.com/subject/1193565/) about automatic typesetting in word. The book introduces great solutions with VBA. Unfortunately, I was lazy at that time and though that I'd better spent that time on learning LaTeX if I had to learn VBA. 

4. Many people also report disadvantages of Word such as 'hard to generating TOC', 'not easy to manage reference'.

As a research student now, I spend little time on Word. I mainly writing something on other typesetting system.

But I have to say, probably, Word is a better solution for non-scientfic writing. I wrote a long Chinese [report](https://docs.google.com/file/d/0B-p98azZDmMrc083T3ZJMnlGeU0/edit) invloveing complex typesetting, citations, footnotes. It was done smoothly with Word. If no need to deal with formulas or publish articles, Word really saves life.

### Write in Libreoffice
I only tried Write a few times. I cannot tell the differences from Word.

# Document Markup Languages
 
## \\( \TeX \\)

\\( \TeX \\) is a well-known and popular document markup language. The creation  of it almost becomes a legend in computing science history. It is designed for academic typesetting. However, few people really use it directlly now. I know little about it.

Online Resources

* [Wiki page](http://en.wikipedia.org/wiki/TeX "Wiki page")
 
## \\( \LaTeX \\)
\\( \LaTeX \\) is a typesetting system based on \\( \TeX \\). It is widely used in academia.

The philosophy of \\( \LaTeX \\) is  

> authors should be able to focus on the content of what they are writing without being distracted by its visual presentation

So, the markups in LaTeX are mostly `\section`, `\table` and so on. Writers are forced to focus on logic structrue other than text styles.

Online Resources

* [LaTeX: an Introduction](http://www.techscribe.co.uk/ta/latex-introduction.pdf). One-page high-level overview of LaTeX
* [The Not So Short Introduction to LATEX 2ε](http://tobi.oetiker.ch/lshort/lshort.pdf). Famous introduction document. It is enough for beginners.

## Editors
It is hard for me to remeber all commands. Plain text is also hard to read. Many editors are developed.

### On Windows Platform
To use LaTex in Windows, users can choose distribution packages such as [TeXLive](http://www.tug.org/texlive/). For chinese, [CTeX](http://www.ctex.org/HomePage) is highly recommended by some people. It includes [WinEdit](http://www.winedt.com/) as editor.

### Linux, Max OS or Cross-platform
There are many cross-platform editors. One can referrs to this [wiki comparision page](http://en.wikipedia.org/wiki/Comparison_of_TeX_editors).


###LyX
#### What you see is what you want

However, for people who are familar with Microsoft Office, the philosophy of those software may confuse them. Ultimately typesetting should be evaluated by its finaly visual apperaence. The markups languages can guarantee typesetting is tidy and beautiful but requires much time to learn. I am glad if 'What you see is what you want' (WYSIWYW) alternative is provided.

I began to use LyX as suggestions in [Xie Yihui's blog](http://yihui.name). He highly recommended this sofware as a WYSIWYW tool for LaTeX. LaTeX guarantees quality of typesetting, on the other hand WYSIWYW makes mathematical writing straightforward and intuitive. Many short-cuts accelerate typing speed. Yet, Xie Yihui also warned one should not try LyX before knowing advanced knowledge in LaTex. But, anyway, it is WYSIWYW and free. What's more, GUI of LyX guides users to write math formulas without bothering to remerber all commands in LateX.

Online resources

* [LyX official page](http://www.lyx.org/) You can download LyX there.
* [Documentation](http://wiki.lyx.org/LyX/Documentation) Even though the users guides are embedded in LyX, you may want to download PDF files.

# Presenation


 