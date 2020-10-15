## HTML常用标签
 <br> 

## （一）a标签的用法
<br>
 1、属性
    
    href 跳转到外部页面
    target 跳转到内部锚点
    download 下载页面（很多浏览器不支持）
    ref=noopener 跳转到邮箱或电话等

2、a 的 href 取值

    （1）网址：http://baidu.com
              https://baidu.com
              //baidu.com
     (2) 路径：/a/b/c以及a/b/c
              index.html以及./index.html
     (3)伪协议：javascript:alert(1);
               mailto:邮箱
               tel:手机号
     (4)id: href=#xxx

3、a 的 target 取值

    内置    
    _blank 空白窗口打开
    _top 窗口打开
    _parent 父级窗口打开
    _self 当前窗口打开

## （二）img 标签的用法
作用：发出get请求展示一张图片

    属性：alt/height/width/src
    事件：onload/onerror 成功/失败
    响应式：max-width:100% 图片等比缩放
 
 ## （三）table 标签的用法

    <table>只能包含这三个元素
    <thead></thead> 表头
    <tbody></tbody> 表的身体
    <tfoot></tfoot> 表尾
    </table>

    <tr></tr> table row表里的一行
    <td></td> table data 表里的数据
    <th></th> table header 表头单元格

table样式

    table-layout: auto; 自动调节表格大小
    border-collapse: collapse; 合并th,td间的距离
    border-spacing:; 指定相邻单元格边框之间的距离（只适用于边框分离模式 ）

## （四）form标签
作用：发出get请求或post请求，刷新页面

    <form action="yyy" method="GET或者POST" autocomplete="off或者on" target="a"></form>

    属性：action 控制请求yyy页面
         method 控制用get或者post请求
         autocomplete 自动检测
         target 规定再a窗口打开档前表单
    事件：onsubmit 当用户点击提交时触发

## （五）input标签
作用：让用户输入内容

    属性：type:button/checkbox/file/hidden/number/password/radio/search/submit/tel/email/text
    其他：name/autofocus/checked/disabled/maxlength/pattern/value/placeholder

    事件：onchange 改变输入内容触发
         onfocus 鼠标聚焦触发
         onblur 鼠标移出触发

## （六）其他标签

    <label></label>
    <select >
    <option ></option>
    </select> 下拉框选择输入

    textarea 表示一个多行纯文本编辑控件

## 注意：

    1. 一般不见监听input的click事件
    2. form里的input要有name
    3. form里面放一个type="submit"才能触发submit事件
   
## 感想：标签和属性好多，感觉记不过来



