```html
# 内嵌css : <style>元素,位于<head></head>标签中
<!DOCTYPE html>
<html>
   <head>
      <style type = "text/css" media = "all">
         body {
            background-color: linen;
         }
         h1 {
            color: maroon;
            margin-left: 40px;
         }
      </style>
   </head>   
   <body>
      <h1>This is a heading</h1>
      <p>This is a paragraph.</p>
   </body>
</html>
# type属性： text/css, 必选项
# media属性：可选项，默认值为all
screen

tty

tv

projection

handheld

print

braille

aural

all
```

```html
# 内联css: style属性
<h1 style = "color:#36C;"> 
```

```
# 外部链接css: <link>元素
<head>
   <link type = "text/css" href = "mystyle.css" media = " all" />
</head>
#href指向css的外部链接地址，另外两个属性同上
```

```
# 导入css: @import规则，与<link>类似
<head>
   @import "mystyle.css";
</head>
```

> 索引覆盖规则：
>
> 1.  内联样式具有最高优先级
> 2. \<style>标签定义的样式，覆盖外部链接的样式
> 3. 外部链接定义的样式具有最低优先级，只有上面两条规则没有适应的元素才会使用外部链接的样式

>  注释格式
>
> ```css
> /* 这是一行注释 */
> 
> /* 这是
> 
> 多行
> 
> 注释 */
> ```