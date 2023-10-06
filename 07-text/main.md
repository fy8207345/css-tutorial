> color：设置文本的颜色。
>
> ```css
> <p style = "color: blueviolet;">
>          Color Name
>       </p>
>       <p style = "color:#ff00ff;">
>          Hexadecimal value
>       </p>
>       <p style = "color: rgb(255,124,100);">
>          RGB value
>       </p>
> ```
>
> text-align 设置文本的对齐方式：水平方向的对其方式
>
> ```css
> 1. left: 通过left-margin定位
> 2. right: 通过right-margin定位
> 3. start: 如果是从左向右，与left一样，如果是从右向左，与right一样
> 4. end：同start
> 5. center: 水平居中
> 6. justify: 计算两边的margin后，确定位置
> 7. justify-all：同justify, 使最后一行也justify
> 8. match-parent：与inherit类似，start 和 right 的值取自父级的值并替换为 left 和 right。
> <h2>Setting Text Alignment using CSS</h2>
>       <p style="text-align: left;">Text Left Alignment.</p>
>       <p style="text-align: right;">Text Right Alignment.</p>
>       <p style="text-align: center;">Text Center Alignment.</p>
>       <p style="text-align: justify; border: 2px solid red; width: 200px; height: 100px;">
>          Text Justify Alignment. This alignment aligns the text based on both the margins, left and right.
>       </p>
> </h2>
> ```
>
> vertical-align 属性设置内联、内联块或表格单元格框的垂直对齐方式
>
> ```css
> baseline：元素的基线与其父元素的基线对齐。
> 
> sub：元素的基线降低到适合下标文本的点。
> 
> super：元素的基线升高到适合上标文本的点。
> 
> top：元素框的顶部与行框的顶部对齐（在内联内容的上下文中），或者与表格上下文中的表格单元格的顶部对齐。
> 
> text-top：元素框的顶部与行中最高行内框的顶部对齐。
> 
> middle：在内联内容的上下文中，元素的基线与父元素的基线加上父元素字体的 x 高度的一半定义的点对齐。
> 
> bottom：元素框的底部与行框的底部对齐（在内联内容的上下文中），或者与表格上下文中的表格单元格的底部对齐。
> 
> text-bottom：元素框的底部与行中最低行内框的底部对齐。
> 
> percentage：元素的基线升高或降低属性 line-height 值的给定百分比。
> 
> length：元素的基线升高或降低给定的长度值。该属性允许使用负长度值。此属性的长度值为 0 与值基线具有相同的效果。
> <table>
>    <tr>
>       <td style="vertical-align: baseline">baseline</td>
>       <td style="vertical-align: top">top</td>
>       <td style="vertical-align: middle">middle</td>
>       <td style="vertical-align: bottom">bottom</td>
>       <td><p>No vertical alignment </p></td>
>    </tr>
>    </table>
> ```
>
> text-align-last：设置文本块最后一行的对齐方式。
>
> direction：设置元素文本的方向。
>
> ```css
> <p style = "direction: rtl;">
>       Right to Left
>    </p>
>    <p style = "direction: ltr;">
>       Left to Right
>    </p>
>    <p style="direction: rtl;unicode-bidi: bidi-override;">Check for the text direction.</p>
> ```
>
> text-indent：设置文本第一行的缩进。
>
> ```html
> <p style="text-indent: 2cm;">Text indentation at 2 cm.</p>
>    <p style="text-indent: 2in;">Text indentation at 2 inches.</p>
>    <p style="text-indent: 20%;">Text indentation at 20%.</p>
> ```
>
> letter-spacing：指定组成单词或文本的字母或字符之间的间距。
>
> ```html
>  <p style="letter-spacing: normal;">Letter spacing normal.</p>
>    <p style="letter-spacing: 5px;">Letter spacing increased.</p>
>    <p style="letter-spacing: -1px;">Letter spacing decreased.</p>
> ```
>
> word-spacing：指定文本中单词之间的间距。
>
> ```html
> <p style="word-spacing: normal;">Word spacing normal.</p>
>    <p style="word-spacing: 15pt;">Word spacing increased.</p>
>    <p style="word-spacing: -1px;">Word spacing decreased.</p>
> ```
>
> white-space：控制元素文本内的空白流。
>
> ```html
> <div>
>       <p style="white-space: normal;">white space refers to any empty space or characters that do not display
>       a visible symbol or have any effect on the text's meaning</p>
>    </div>
>    <h4>pre</h4>
>    <div>
>       <p style="white-space: pre;">white space refers to any empty space or characters that do not display
>       a visible symbol or have any effect on the text's meaning</p>
>    </div>
>    <h4>nowrap</h4>
>    <div>
>       <p style="white-space: nowrap;">white space refers to any empty space or characters that do not display
>       a visible symbol or have any effect on the text's meaning</p>
>    </div>
>    <h4>pre-wrap</h4>
>    <div>
>       <p style="white-space: pre-wrap;">white space refers to any empty space or characters that do not display
>    a visible symbol or have any effect on the text's meaning</p>
>    </div>
>    <h4>pre-line</h4>
>    <div>
>       <p style="white-space: pre-line;">white space refers to any empty space or characters that do not display
>       a visible symbol or have any effect on the text's meaning</p>
>    </div>
>    <h4>break-spaces</h4>
>    <div>
>       <p style="white-space: break-spaces;">white space refers to any empty space or characters that do not display
>       a visible symbol or have any effect on the text's meaning</p>
>    </div>
> ```
>
> text-decoration：在一段文本上添加下划线、上划线和删除线。
>
> ```html
> text-decoration-line: Sets the type of decoration line (underline, strikethrough or overline).
> 
> text-decoration-color: Sets the color to the text decoration.
> 
> text-decoration-style: Sets the style to the text decoration (dotted, dashed, solid, wavy, double, etc.)
> 
> text-decoration-thickness: Sets the thickness to the text decoration.
> <html>
> <head>
> <style>
>    .overline{
>       text-decoration: overline solid red 5px;
>    }
>    .line-through{
>       text-decoration: line-through solid green 1px;
>    }
>    .underline{
>       text-decoration: underline dashed 2pt blue;
>    }
> </style>
> </head>
> <body>
>    <h2>Text Decoration using CSS</h2>
>       <p class="overline">Overline text decoration.</p>
>       <p class="line-through">Line-through text decoration.</p>
>       <p class="underline">Underline text decoration.</p>
> </body>
> </html>
> ```
>
> text-decoration-skip：确定需要跳过元素内容中受文本装饰影响的部分。
>
> ```
> 只有safari支持text-decoration-skip
> ```
>
> text-decoration-skip-ink：指定如何在字形上升部和下降部周围绘制上划线和下划线文本装饰线。
>
> text-transform：将文本转换为大写或小写字母。
>
> ```html
> <p style="text-transform: capitalize;">This text will be capitalized.</p>
> 
>    <p style="text-transform: lowercase;">This text will be in lowercase.</p>
> 
>    <p style="text-transform: uppercase;">This text will be in upercase.</p>
> 
>    <p style="text-transform: none;">This text will not have any transformation.</p>
> 
>    <p style="text-transform: full-width;">TRANSFORMATION OF TEXT AS FULL-WIDTH.</p>
> ```
>
> text-emphasis：对文本应用强调标记（空格和控制字符除外）。
>
> ```html
> <p style="text-emphasis: dot;">The emphasis is a dot.</p>
>    <p style="text-emphasis: circle red;">The emphasis is a circle.</p>
>    <p style="text-emphasis: triangle;">The emphasis is a triangle.</p>
>    <p style="text-emphasis: none;">No emphasis to the text.</p>
>    <p style="text-emphasis: double-circle green;">The emphasis is a double-circle.</p>
>    <p style="text-emphasis: open;">The emphasis is open.</p>
>    <p style="text-emphasis: sesame;">The emphasis is a sesame.</p>
>    <p style="text-emphasis: 'u' #00ff00;">The emphasis is a string.</p>
> ```
>
> text-shadow：为文本添加阴影。
>
> ```html
> /* offset-x | offset-y | blur-radius | color */
> text-shadow: 1px 1px 2px black;
> 
> /* color | offset-x | offset-y | blur-radius */
> text-shadow: #fc0 1px 0 10px;
> 
> /* offset-x | offset-y | color */
> text-shadow: 5px 5px #558abb;
> 
> /* color | offset-x | offset-y */
> text-shadow: white 2px 5px;
> 
> /* offset-x | offset-y
> /* Use defaults for color and blur-radius */
> text-shadow: 5px 10px;
> 
> <p style="text-shadow: 2px 5px yellow;"> Simple Text shadow </p>
>       <p style="text-shadow: 5px 5px 2px #ff00ff;">Text shadow with blur radius</p>
>       <p style="text-shadow: 1px 1px 2px green, 0 0 1em yellow, 0 0 0.2em red;">Multiple shadows</p>
>       <p style="text-shadow: 0px 0px 10px rgb(26, 69, 105); ">Text shadow with RGB colors</p>
> ```
>
> line-break：控制如何设置换行规则。
>
> word-break：控制如何设置断词规则。