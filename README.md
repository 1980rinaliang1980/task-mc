# 任务： 制作网页贺卡

## 项目指引

### step1:  新建文件夹 task-mc
并在文件夹里，新建以下文件：
index.html
index.css
将图片下载下来，放到文件夹里。下载地址![https://github.com/doingcity/task-mc/blob/master/logo.png](https://github.com/doingcity/task-mc/blob/master/logo.png)


### step2: 写头文件。
用sublime打开index.html , 并将下面代码粘贴上去
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>task2</title>
  <link rel="stylesheet" href="index.css">
</head>
<body>

</body>
</html>
```

### step3: 写HTML
在`<body> 和 </body>`标签中写下面的代码。
```html
<div class="card">

  <div class="text">
    <h1>Merry Christmas</h1>
  </div>

  <div class="image">
    <img src="logo.png" alt="logo">
  </div>

</div>
```

### step4: 先看一看
在文件里用chrome浏览器打开index.html，看看是什么样。

### step5: 写CSS
将下面代码写到index.css文件。
```css
.card {
  width: 550px;
  height: 700px;
  margin: 0 auto;
  background-color: #C1272E;
  font-family: Helvetica, Tahoma, Arial;
  box-sizing: border-box;
}

.card .text h1 {
  margin: 0;
  padding: 20px 10px;
  color: white;
  font-size: 72px;
  font-weight: bold;
}

.card .image {
  margin-top: 120px;
}

.card .image img {
  width: 70%;
}
```

### step6: 再看一下吧
重新用浏览器打开index.html，是不是大变样了呢。

## 基础知识
### HMML基础
标签： html, body, div, p, h1, img  
属性： class, src, alt
### CSS基础
选择器： 元素选择器，类选择器
属性：width, height, margin, padding, color， font-size, ....
