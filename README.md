# Skeu-Example
SKEU DESIGN OF THIS REPO
### 源代码
```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>拟物化按钮</title>
    <style>
        *{
            user-select: none;
            margin: 0px;
        }
        button{
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%,-50%);
            width: 180px;
            height: 50px;
            border-radius: 15px;
            border: none;
            background: linear-gradient(180deg,rgb(0,200,255),rgb(0,50,255));
            color: white;
            font-size: 20px;
            box-shadow: inset 0 0 5px black,
            0 0 10px black;
            text-shadow: 0 0 5px black,
            0 0 10px black;
        }
        button:hover{
            background: linear-gradient(180deg,rgb(0,200,255),rgb(0,0,255));
        }
        button:active{
            background: linear-gradient(180deg,rgb(0,50,255),rgb(0,200,255));
        }
    </style>
</head>
<body>
    <button>按钮</button>
    <script>
        document.addEventListener("contextmenu",(e) => {
            e.preventDefault();
        })
    </script>
</body>
</html>
```
*新建文件，复制代码，然后把后缀改为“html”格式然后双击打开即可（建议使用Chrome、Edge、Firefox等浏览器，Internet Explorer效果不佳）*