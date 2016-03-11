html 
## catogary
* [link](#html_links)
* [title](#header)
* [paragraph](#p)
* [image](#img)
* [list](#list)
* [lable](#label)
* [table](#table)
* [form](#form)
* [div](#div)
* [span](#span)

## <a name="html_links">link</a>
link defines as `<a>`    

* `href` some types:
	* `https://gusouk.com/`
	* `/a.html`
	* `#aaa` to block name or id as`aaa` ; usually set initial value as `###`
	* `javascript:void(0);` is combined a click event not a page 
* `title` 
* `target` 
	* default is current page 
	* `_blank` new window
	* value set as name of iframe, open in iframe



## <a name="header">title</a>
from `<h1>` to `<h6>`    
## <a name="p">paragraph</a>
 `<p>` 

## <a name="img">image</a>
`<img>` 
* `src` location
* `alt` show text when load image fails

## <a name="list">list</a>
ordered list `<ol>`，list items `<li>` eg:
```
<h3>最热单曲</h3>
<ol>
	<li>时间都去哪儿了</li>
	<li>泡沫</li>
	<li>卷珠帘</li>
</ol>
```

unordered list `<ul>` , eg:
```
<h3>a attributes</h3>
<ul>
	<li>href</li>
	<li>title</li>
	<li>name</li>
	<li>target</li>
</ul>
```

## <a name="label">lable</a>
`<label>`
* `for`

## <a name="table">table </a>
`<table>` , eg:
```
<table>
	<thead>
		<tr>
			<th>姓名</th>
			<th>性别</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>路飞</td>
			<td>男</td>
		</tr>
		<tr>
		<td>索隆</td>
			<td>男</td>
		</tr>
		<tr>
			<td>香吉士</td>
			<td>男</td>
		</tr>
	</tbody>
</table>
```

## <a name="form">form</a>
`<form>` will send input to backend    
* `action` submit location/file。
* `method` submit method, default is GET
* add name attributes of element to distingulish different items
eg:   
```
<form action="" method="POST">
	<div>
		<label for="">名称</label>
		<input name="name" type="text" placeholder="请输入名称">
	</div>
	<div>
		<label for="">介绍</label>
		<textarea name="des"></textarea>
	</div>
	<button type="reset">重置</button>
	<button type="submit">提交</button>
</form>
```
form element types:
* input
  * text `<input type="text">` 
	  * `placeholder`
	  *`value`
	  * `maxlength` 
	* password  `<input type="password">`, field is masked
	* submit  `<input type="submit">`, value will be send to action location/file
  * radio `<input type="radio" name="gendar">` 
  * checkbox `<input type="checkbox" name="gendar">`
  * button `<input type="button">` 
  
  * number  `<input type="number">` do not support `maxlength`
	  * `min` 
	  * `max`
	  
	HTML5 added several new input types:
color
date
datetime
datetime-local
email
month
number
range
search
tel
time
url
week
	  
* textarea `<textarea></textarea>` more characters than text type 
	  * `placeholder`
	  * `value`
	  * `maxlength` >IE9 supports	  
* select `<select><option value="1">苹果</option><option value="2">橘子</option></select>`

* button
  * submit  `<button type="submit">提交</button>` 点击
  * reset `<button type="reset">重置</button>`


## <a name="div">div</a>
`<div>`组合文档中的块级元素

## <a name="span">span</a>
`<span>`组合文档中的行内元素

## <a name="comment">注释</a>
注释由`<!-- 注释内容 -->`来定义

## <a name="more">更多标签</a>
* `strong` 强调
* `pre` 预定义
* `code` 代码
* `blockquote` 引用
* `small` 补充说明
* `i` 图标或改变的语义
* `dl`
	* `dt`
	* `dd`

