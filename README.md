# latex-screen

LaTeX Slides based on TeXPower

这是基于 TeXPower 制作的幻灯片

幻灯片的效果类似于 pdfscreen，但并未调用 pdfscreen 宏包。本模板直接使用 tikz 定义了多个背景颜色，通过循环这些颜色来设置每页的颜色。

本模板在 ctexart 和 ctexbook 文档类下实现，需要使用 XeLaTeX 编译运行。使用者可以方便地将 article 和 book 转换为幻灯片。幻灯片内容会根据页面大小自动换页，如果遇到处理不佳的情况，可以使用 \clearpage 或 \newpage 手动调整。
