# BFC

## 什么是 BFC

在 CSS 中，BFC（Block Formatting Context，即块级格式化上下文）。它是一个独立的渲染区域，块级盒子按照移动的规则进行布局，并与外部的元素相互隔离。

## BFC 解决问题

- 元素开启 BFC 后，子元素不会产生 margin 塌陷问题。
- 元素开启 BFC 后，元素本身不会被其他浮动元素覆盖。
- 元素开启 BFC 后，即使子元素浮动，元素自身高度也不会塌陷。

## 开启 BFC

- 根元素，即 HTML 元素。
- 浮动元素。
- 绝对定位、固定定位的元素。
- 行内块元素。
- 表格元素，如 table、thead、tbody、tfoot、th、td、tr、caption。
- overflow 不为 visible 的块元素。
- 弹性盒子。
- 多列容器。
