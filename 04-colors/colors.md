> ```
> CSS 使用颜色值来指定颜色。通常，它们用于设置元素的前景（即其文本）或元素的背景颜色。它们还可以用于影响边框的颜色和其他装饰效果。
> ```

```css
# 通过使用命名好的颜色来设置颜色： 140种标准颜色
color: blue; 
border: 1px solid red;
background: aliceblue;

# RGB 16进制颜色：6位16进制数字（RRGGBB），也可为3位16进制（RGB）;大小写均可。
color: #f09;
border: 1px solid #ff0099;
background: #eee;

# RGB颜色: 并非所有浏览器都支持，不建议使用
color: rgb(255 0 153);
border: 1px solid rgb(255 0 153);
background: rgb(255 0 153 / 80%);

# HSL（色相、饱和度、亮度）颜色
color: hsl(150 30% 60%);
border: 1px solid hsl(150 30% 60%);
background: hsl(150 30% 60% / 0.8);

# HWB（色调、白度、黑度）颜色
color: hwb(12 50% 0%); 
border: 1px solid hwb(12 50% 0%); 
background: hwb(194 0% 0% / 0.5);

# LAB（亮度、A 轴、B 轴）颜色
color: lab(50% 40 59.5);
border: 1px solid lab(50% 40 59.5);
background: lab(50% 40 59.5 / 0.5);

# LCH（亮度、色度、色调）颜色
color: lch(52.2% 72.2 50);
border: 1px solid lch(52.2% 72.2 50);
background: lch(52.2% 72.2 50 / 0.5);

# Oklab（亮度、A 轴、B 轴）颜色
color: oklab(59% 0.1 0.1);
border: 1px solid oklab(59% 0.1 0.1);
background: oklab(59% 0.1 0.1 / 0.5);

# Oklch（亮度、色度、色调）颜色
color: oklch(60% 0.15 50);
border: 1px solid oklch(60% 0.15 50);
background: oklch(60% 0.15 50 / 0.5);
```

> 颜色构建器
>
> https://www.tutorialspoint.com/html5/html5_color_code_builder.htm

> 浏览器安全颜色：216种安全色，与电脑硬件无关的
>
> | 000000 | 000033 | 000066 | 000099 | 0000CC | 0000FF |
> | :----: | ------ | ------ | ------ | ------ | ------ |
> | 003300 | 003333 | 003366 | 003399 | 0033CC | 0033FF |
> | 006600 | 006633 | 006666 | 006699 | 0066CC | 0066FF |
> | 009900 | 009933 | 009966 | 009999 | 0099CC | 0099FF |
> | 00CC00 | 00CC33 | 00CC66 | 00CC99 | 00CCCC | 00CCFF |
> | 00FF00 | 00FF33 | 00FF66 | 00FF99 | 00FFCC | 00FFFF |
> | 330000 | 330033 | 330066 | 330099 | 3300CC | 3300FF |
> | 333300 | 333333 | 333366 | 333399 | 3333CC | 3333FF |
> | 336600 | 336633 | 336666 | 336699 | 3366CC | 3366FF |
> | 339900 | 339933 | 339966 | 339999 | 3399CC | 3399FF |
> | 33CC00 | 33CC33 | 33CC66 | 33CC99 | 33CCCC | 33CCFF |
> | 33FF00 | 33FF33 | 33FF66 | 33FF99 | 33FFCC | 33FFFF |
> | 660000 | 660033 | 660066 | 660099 | 6600CC | 6600FF |
> | 663300 | 663333 | 663366 | 663399 | 6633CC | 6633FF |
> | 666600 | 666633 | 666666 | 666699 | 6666CC | 6666FF |
> | 669900 | 669933 | 669966 | 669999 | 6699CC | 6699FF |
> | 66CC00 | 66CC33 | 66CC66 | 66CC99 | 66CCCC | 66CCFF |
> | 66FF00 | 66FF33 | 66FF66 | 66FF99 | 66FFCC | 66FFFF |
> | 990000 | 990033 | 990066 | 990099 | 9900CC | 9900FF |
> | 993300 | 993333 | 993366 | 993399 | 9933CC | 9933FF |
> | 996600 | 996633 | 996666 | 996699 | 9966CC | 9966FF |
> | 999900 | 999933 | 999966 | 999999 | 9999CC | 9999FF |
> | 99CC00 | 99CC33 | 99CC66 | 99CC99 | 99CCCC | 99CCFF |
> | 99FF00 | 99FF33 | 99FF66 | 99FF99 | 99FFCC | 99FFFF |
> | CC0000 | CC0033 | CC0066 | CC0099 | CC00CC | CC00FF |
> | CC3300 | CC3333 | CC3366 | CC3399 | CC33CC | CC33FF |
> | CC6600 | CC6633 | CC6666 | CC6699 | CC66CC | CC66FF |
> | CC9900 | CC9933 | CC9966 | CC9999 | CC99CC | CC99FF |
> | CCCC00 | CCCC33 | CCCC66 | CCCC99 | CCCCCC | CCCCFF |
> | CCFF00 | CCFF33 | CCFF66 | CCFF99 | CCFFCC | CCFFFF |
> | FF0000 | FF0033 | FF0066 | FF0099 | FF00CC | FF00FF |
> | FF3300 | FF3333 | FF3366 | FF3399 | FF33CC | FF33FF |
> | FF6600 | FF6633 | FF6666 | FF6699 | FF66CC | FF66FF |
> | FF9900 | FF9933 | FF9966 | FF9999 | FF99CC | FF99FF |
> | FFCC00 | FFCC33 | FFCC66 | FFCC99 | FFCCCC | FFCCFF |
> | FFFF00 | FFFF33 | FFFF66 | FFFF99 | FFFFCC | FFFFFF |