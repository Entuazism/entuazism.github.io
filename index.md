---
layout: default
title: Start
---


## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Entuazism/entuazism.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Entuazism/entuazism.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.


'''
<!DOCTYPE HTML>
<html>
 <head>
  <meta charset="utf-8">
  <title>Тег CODE</title>
 </head>  
 <body> 

  <p>Код программы</p>
  <p><code>
    function checkParent (src, dest) {<Br>
     while (src != null) {<Br>
       if (src.tagName == dest) return src<Br>
        src = src.parentElement<Br>
     }<Br>
     return null<Br>
    }</code></p>

 </body>
</html>
'''

Тег <code> предназначен для отображения одной или нескольких строк текста, который представляет собой программный код. Сюда относятся имена переменных, ключевые слова, тексты функции и т.д. Браузеры обычно отображают содержимое контейнера <code> как моноширинный текст уменьшенного размера.

В отличие от тега <pre> дополнительные пробелы внутри контейнера <code> не учитываются, так же, как и переносы текста. Поэтому используйте тег <br> или <p> для создания переносов.
