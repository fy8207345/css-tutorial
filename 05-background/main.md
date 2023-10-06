> https://www.tutorialspoint.com/css/css_backgrounds.htm
>
> **background-color** ：设置元素的背景色
>
> ```css
> background-color: #cccccc;
> ```
>
> **background-image** ：设置元素背景图片
>
> ```css
> background-image: url("/css/images/css.jpg");
> ```
>
> **background-repeat** ：用于控制背景中图像的重复, 默认值repeat
>
> ```css
> # 横向纵向均重复
> background-repeat: repeat;
> # 纵向方向重复，横向不重复
> background-repeat: repeat-y;
> background-repeat: repeat-x;
> ```
>
> **background-position** ：用于控制图像在背景中的位置
>
> ```css
> # 背景图从图片从左侧向右100px后开始算起
> background-position:100px;
> # 背景图从图片从左侧向右100px，顶部向下200px后开始算起
> background-position:100px 200px;
> ```
>
> **background-attachment** ：用于控制背景中图像的滚动
>
> ```css
> # 内容过长时，内容产生滚动条后，内容滚动时，背景图片不跟随内容滚动
> background-repeat: no-repeat;
> background-attachment: fixed;
> # 内容过长时，内容产生滚动条后，内容滚动时，背景图片跟随内容滚动
> background-repeat: no-repeat;
> background-attachment: fixed;
> background-attachment:scroll;
> ```
>
> **background** ：是上述属性的缩写形式
>
> ```css
> <p style = "background:url(/images/pattern1.gif) repeat fixed;">
>    This parapgraph has fixed repeated background image.
> </p>
> ```

