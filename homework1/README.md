<h2> 과제 1 </h2>

<ul>
    <li>1. 인풋창에 글을 입력하면 아래의 ul에 목록 추가하기</li>
    <li>2. 엔터키를 눌러도 입력되게 하기</li>
</ul>

```html
<html>
<head lang="en">
    <meta charset="UTF-8">
    <title>First HOMEWORK</title>
    <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css">

    <script type="application/javascript" src="http://code.jquery.com/jquery-1.11.1.js"></script>
    <script type="application/javascript" src="http://underscorejs.org/underscore.js"></script>
    <script type="application/javascript" src="http://backbonejs.org/backbone.js"></script>
    <script type="application/javascript" src="http://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>

    <style>
        .content{
            width : 500px;
            margin : 50px auto;
        }

        .list{
            margin-top:20px;
        }

        #enterNewWork{
            width:400px;
        }

    </style>
</head>
<body>
    <div class="content">

        <h2>WORK LIST</h2>

        <div class="form-inline">
            <div class="form-group">
                <input type="text" class="form-control" id="enterNewWork" placeholder="Enter NEW WORK"  autocomplete="off">
            </div>
            <button type="button" class="btn btn-default" id="addButton">Add</button>
        </div>

        <ul class="list"></ul>

    </div>
    <script type="text/javascript">
// 스크립트를 작성하세요!!
    </script>
</body>
</html>
```