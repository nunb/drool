# drool

Since it is said that the source of a markdown can be read as easily as visual document does, so why do we compile it before showing it? Based on this consideration, I designed a kind of LML named *drool*. You cannot make something bold or italic with it, which is why drool is different from markdown. You can retract and align right something to express the structure of a document and can still insert media elements and links. Compared with markdown, drool is minimal without signals like `[` or `!`. Drool will not make a literary article look like programming codes.

[See more on a demo](https://dou4cc.github.io/drool/demo.html?./demo.en.drool) which requires supports on async function, WebP, WebM, fetch API, CSS variable, sticky position, and full of ECMAScript 6. I recommend you use Chromium or Chrome Canary with the proper flags on. I was sorry to use a lot of unstable features and not to give the project a version. If you are unable to open the demo, you can refer to [the screenshot](https://dou4cc.github.io/drool/screenshot.en.png).

There is a UTF-8 BOM in the head of every text file except this file and I use `\r\n` to break lines.

既然markdown自称源码的可读性堪比可视化编辑，为什么我们还要编译？于是，我设计了*drool*。它没有加粗、斜体之类的功能，但可用“智能”缩进和右对齐表达文档结构，图片、链接仍可插入。相比markdown，drool是极简的，不使用`[`、`!`之类的标识。drool不会像markdown那样让一篇文学文章看上去布满代码。

详见[demo](https://dou4cc.github.io/drool/demo.html?./demo.han.drool)。你的浏览器得支持async function、WebP、WebM、fetch API、CSS variable、sticky position和完整的ECMAScript 6，我推荐使用开启了恰当实验选项的Chromium或Chrome Canary。抱歉使用了太多草案级别的特性，如果你打不开demo，请参考[其截图](https://dou4cc.github.io/drool.screenshot.han.png)。

因为使用了微软的编辑器，本仓库的每个文本文件（除了本文件）头都有UTF-8的BOM，使用`\r\n`换行。

## License
MIT
