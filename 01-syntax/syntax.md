```css
# 类型选择器 
h1 {
    color: #36cfff;
}
```

```css
# 全局选择器
 * {
 	color: #000000;
 }
```

```css
# 层级选择器 : 只有在ul下的em才会选中,包括孙子级别及以下
ul em {
	color: #000000;
}
```

```css
# 类选择器
.black {
	color: #000000;
}
# h1标签上有class包含black才能选中
h1.black {
	color: #000000;
}
```

```css
# id选择器
#black {
	color: #000000;
}
# h1标签id为black的才会选中
h1#black{
	color: #000000;
}
# blackid下的所有h2标签都会选中
#black h2{
	color: #000000;
}
```

```css
# 子选择器：p必须是body的直接子级
body > p {
	color: #000000;
}
```

```css
# 属性选择器
# input的type === text的元素选中
input[type = "text"] {
	color: #000000;
}
# p带有lang属性的元素选中
p[lang]
# p的lang属性值列表中含有"fr": 如 <p lang="en fr">non-direct child2</p>
p[lang~="fr"]
# p的lang属性值列表中某一项 === en，或者以"en-"开头，如<p lang="en-sub cn">non-direct child3</p>
p[lang|="en"]
```

```css
# 组选择器, h1，h2, h3都会选中，与定义顺序无关
h1, h2, h3 {
	 color: #36C;
}
```

