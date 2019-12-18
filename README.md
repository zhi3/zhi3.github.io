# zhi3.github.io

* Jekyll是什么？

### [jekyll](https://jekyllrb.com): Transform your plain text into static websites and blogs.

* Static: Markdown, Liquid, HTML & CSS go in. Static sites come out ready for deployment.
* Blog-aware: Permalinks, categories, pages, posts, and custom layouts are all first-class citizens here.

```
$ gem install bundler jekyll
$ jekyll new my-awesome-site
$ cd my-awesome-site
/my-awesome-site $ bundle exec jekyll serve
# => Now browse to http://localhost:4000
```


是一个简单的免费的Blog生成工具,将纯文本转化为静态网站和博客;由于咱们的GitHub Pages生成的是静态页面,每次更新博客都需要手动更改HTML,这就使得每次写博客都变得很麻烦,而用了这个工具以后,它会根据预先设置好的格式来生成博客内容,你就无需关心html代码,只需要把重心放在博客的写作上.


[Liquid](https://jekyllrb.com/docs/liquid/): Jekyll uses the Liquid templating language to process templates.

[Liquid](https://github.com/Shopify/liquid/wiki) is a template engine which was crafted for very specific requirements
* It has to have simple markup and beautiful results. Template engines which don't produce good looking results are no fun to use.
* It needs to be non-evaling and secure. Liquid templates are made so that users can edit them. You don't want your server running code that your users wrote.
* It has to be stateless. The compile and render steps have to be separate, so that the expensive parsing and compiling can be done once; later on, you can just render it by passing in a hash with local variables and objects.
* It needs to be able to style emails as well as HTML.



* Liquid是什么?
Liquid是一种模板语言,可以在HTML页面中使用它;而他的作用就是使用标记、对象和过滤器的组合来加载一些动态内容.

### [Step by Step Tutorial](https://jekyllrb.com/docs/step-by-step/02-liquid/)
 
Liquid is where Jekyll starts to get more interesting. Liquid is a templating language which has three main parts: objects, tags and filters.

