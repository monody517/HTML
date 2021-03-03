# 《HTML重难点》
## a标签
### a标签的属性
#### herf
链接到一个网址
herf的取值：
* 网址：//google.com
* 路径：/HTML重难点/b/c.html HTML重难点/b/c.html
* 伪协议：javascript:;代码 mailto:邮箱 tel:电话
* 链接到id：跳转到指定的id
#### target
指定在哪个窗口打开超链接
target的取值：
* _black：在新的页面打开
* _top：在所有层级的顶层打开
* _parent：在该链接所在层级的上一层打开
* _self：在该链接所在的层级 打开
* 窗口的name：所有新开的页面都在这个窗口打开
* iframe的name：新开的页面在这个iframe打开
### 作用
* 跳转到外部页面
* 链接到内部锚点
* 发邮件，打电话

## table标签
### 语法
```JavaScript
    <table>
      <thead>
        <tr> //table row
            <th></th>
            <td></td>
            <td></td>
        </tr> 
      </thead>
      <tbody>
        <tr> //table row
            <th></th>
            <td></td>
            <td></td>
        </tr> 
        </tbody>
      <tfoot></tfoot>
    </table>
```
### 属性
* table-layout:规定表格宽度
* border-collapse:规定表格空隙样式

## img标签
### 作用
发出get请求，展示一张图片
### 属性
* src：图片的地址
* alt：图片加载失败时的展示
* width,height：设置图片的宽高
### 事件
* onload：加载成功事件
* onerror：加载失败事件
### 响应式
`max-width: 100%;`

## form标签
form中必须有一个`<input type="submit">`

form里的input要有name
### 属性
* action：请求的地址
* method：GET/POST请求
* autocomplete:打开后有建议输入框
* target：将哪个页面变为请求的地址
  
`<input type="submit" value="111"/>`和`<button type="submit">111</button>`有什么区别？
button中还可以添加任意的标签