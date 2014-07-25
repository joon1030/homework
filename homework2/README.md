<h2> 과제 2 </h2>
<p>아래 요구사항을 만족하는 이미지 처럼 만들어보세요</p>
<ul>
    <li>1. 폰트 크기 변경하기 </li>
    <li>2. 폰트 종류 변경하기 </li>
</ul>
<img src="https://raw.githubusercontent.com/joon1030/homework/master/homework2/Second_HOMEWORK.png">

```html
<!DOCTYPE html>
<html>
<head lang="en">
    <meta charset="UTF-8">
    <title>Second HOMEWORK</title>
    <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css">

    <script type="application/javascript" src="http://code.jquery.com/jquery-1.11.1.js"></script>
    <script type="application/javascript" src="http://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>

    <style>
        .content{
            width : 500px;
            margin : 50px auto;
        }
        #p{
            font-family: verdana;
        }
    </style>
</head>
<body>
<div class="content">

    <h2>CHANGE FONT</h2>

    <blockquote>
        <p id="p">FONT!FONT!FONT!FONT!</p>
    </blockquote>
    <div class="form-inline">

        <select id="fontList" class="form-control">
            <option value="verdana">verdana</option>
            <option value="Helvetica">Helvetica</option>
            <option value="Serif">Serif</option>
            <option value="cursive">cursive</option>
        </select>

        <button type="button" class="btn btn-default" id="big">크게</button>
        <button type="button" class="btn btn-default" id="small">작게</button>

    </div>

    
</div>
<script type="text/javascript">
//스크립트를 작성하세요~!
</script>
</html>
```