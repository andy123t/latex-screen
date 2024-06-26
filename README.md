# latex-screen

LaTeX Slides based on TeXPower

本模板是基于 TeXPower 制作的幻灯片

中文模板使用 XeLaTeX 编译运行
- article-screen-cn 是使用 ctexart 类的中文模板
- book-screen-cn 是使用 ctexbook 类的中文模板

英文模板使用 PDFLaTeX 编译运行
- article-screen-en 是使用 article 类的英文模板
- book-screen-en 是使用 book 类的英文模板

幻灯片的效果类似于 pdfscreen，但并未调用 pdfscreen 宏包。本模板直接使用 tikz 定义了多个背景颜色，通过循环这些颜色来设置每页的颜色。

使用者可以方便地将文章和书籍转换为幻灯片。幻灯片内容会根据页面大小自动换页，如果遇到处理不好的情况，可以使用 \clearpage 或 \newpage 手动调整。
