# My-Typora-Themes

模版基于 https://github.com/Theigrams/My-Typora-Themes，做出了以下更改：

缩短了标题行和段落文字的行间距：
- 将 h2 标题的上下边距从 2em auto 1.4em 改为 1.4em auto 1em

- 将 h2 的行高从 1.4 减小到 1.2

- 将段落的行高从 1.8rem 减小到 1.5rem

- 为段落添加了更小的上下边距：margin-top: 0.5em; margin-bottom: 0.5em;

- 将所有块级元素（p、blockquote、ul、ol、dl、table）的边距从 0.8em 0 减小到 0.5em 0

添加了使文本默认靠左放置的代码：

- 在CSS文件末尾添加了 #write { text-align: left; }，确保所有文本默认左对齐

- 在编辑模式下缩短图片和段落文字的行间距：

- 添加了 .md-image { margin: 0.5em 0; } 来减小图片的上下边距

- 添加了 #write p + .md-image, .md-image + p { margin-top: 0.3em; } 来特别减小图片和段落之间的间距

- 添加了源码模式下的调整 .cm-s-inner .cm-image { margin: 0.3em 0; }

- 添加了所见即所得模式下的调整 .cm-s-typora-default .cm-paragraph { margin: 0.3em 0; }

