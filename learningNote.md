# Basics for html
<h1 id="title">
    html标签：
</h1>
<p>
    h1 tittle 
    p paragraph
    hr 分隔横线
    br 换行
    button 按钮
</p>

<h1>
    CSS 更改按钮样式
</h1>
<p>
   <style>
        /* id不重复 */
        #title{
           color:rgb(70, 112, 176);
        }
        button{
            color:rgb(187, 207, 149);
            background-color: aliceblue;
            width: 60px;
            height: 36px;
            border-radius: 18px;
            border-style:none;
            cursor:pointer; 
            /* <!-- 鼠标放到按钮变色 --> */
        }
        /* <!-- 设置变色颜色 --> */
        button:hover{
            background-color:rgb(rgb(41, 124, 180))
        }
        .subscribe-button{
            background-color: rgb(113, 118, 135);
        }
    </style>
</p>

<button class="subscribe-button">订阅

</button>

# Add a new page named Misc
1.add the page in  _config.yml- default and collection
2._config.yml-default define the layout
2.create a file named misc edit markdown file
4.change _layout/
<!-- 3._pages/misc.html edit feature -->