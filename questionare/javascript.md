## Engineer questionare

### what is this

```
指的是javascript嗎~~
HTML網頁上使用，用來增加動態功能 也可以寫網路伺服器
還是github
github 共享虛擬主機服務
可以 存取程式碼 分享  可以同步合作專案用
.
.
.
.
.
.
.
.
.
.
.
.
```

### what difference are apply, call, bind?

```
.apply 和call 相似  call(this, arg1, arg2)只是apply 第二個傳的是是陣列:apply(this, [arg1, arg2]) 
.bind 生成一個值綁定  不會像apply call 馬上調變
.
.
.
.
.
.
.
.
.
.
.
```

### please write a function can execute like

```js
console.log(add(2,3)); // logs 5
console.log(add(2)(3)); // logs 5
```


       
       
        function add(x,y) {
            return x + y;

        }
        console.log(add(2, 3));
    
.
.

.
.
.
.
.
.
.
.
```



### please explain css style priority

```
.CSS可用來改網頁外觀、格式 
 用選擇器的方式指定 
.
.
.
.
.
.
.
.
.
.
.
.
.
```

### please explain inline mode, block mode of css

inline mode
.inline level 不會跳行 設定左右距離用
 
.

.
.block mode   
css 由內往外content padding border margin組成 
.content是內容   padding 空白  border 框線 margin 邊界  
.css可以修改這幾個寬度 來排版上下分隔距離 
.
.
.
.
.
.
.
.
.
.
.
```

### please introduce ORM, what is different between SQL select?

```
.orm 物件導向
.
.sql  關聯式資料庫
.
.
.
.
.
.
.
.
.
.
.
```

### please explain right join, left join and inner join.

```
合併資料表用 
inner join  兩個資料表合併

 right join-> 以右邊資料表為主  
 
SELECT column_name(s) FROM table1
RIGHT JOIN table2 ON table1.column_name=table2.column_name; 以table2為主  

 left join->  以左邊資料表為主
.
.
.
.
.
.
.
.
.
.
.
.
.
```

### what is your favorite SQL and why?

```
.sql sever 學校教過 
SELECT "欄位名" FROM "表格名
查詢
比較常用 

.
.
.
.
.
.
.
.
.
.
.
.
.
```

### how will you implement a API server? and if it should be connect via facebook, twitter data, how will you do?

```
.
.
.
.
.
.
.
.
.
.
.
.
.
.

```

### do you code for test? how do you feel test?

``

考過微軟MTA證照 ，蠻順利取的證照，很開心能拿到第一張證照
.
.
.
.
.
.
.
.
.
.
.
.
.
.

```

### a layout like that below, how will you implement it and tag naming, please explain 

![](http://i.stack.imgur.com/GXLMT.png)

```
.
.
.用表格分割(td)   然後用CSS加邊框跟大小比例

.
.
.<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <title></title>
    <style type="text/css">

            html,body { height: 100%; width: 100%; }



        .auto-table {
            width: 100%;
            height: 100%;
        }
        .leftrightarea {
            width: 20%;
            height: 90%;
        }
        .center {
            height: 100%;

        }


        .centerup {
         height:33%;
         margin-top:8px;
          margin-right:8px;
           margin-bottom:8px;
            margin-left:8px;
        }
         .centermeddle {
            height:20%;
        }

           .centerdown {
            height:40%;
            width:100%;
        }





    </style>
</head>
<body>
    <table class="auto-table">

        <tr>

            <td class="leftrightarea" style="border: 15px solid #FFFFCC; background-color: #FFCC99; "></td>

            <td class="cente" style="border: 15px solid #FFFFCC; background-color: #FFCC99">

                <div class="centerup" style="background-color: #00FF00 ">
                </div>



                <div class="centermeddle" style="border: thick solid #00FFFF; background-color: #C0C0C0">
                </div>


                <textarea id="TextArea1" class="centerdown" style="border: thick solid #00FFFF; background-color: #800080" rows="20" cols="40">


                    SCROLL AREA
                </textarea>






            </td>
            <td class="leftrightarea" style="border: 15px solid #FFFFCC; background-color: #FFCC99; "></td>
        </tr>
    </table>


</body>
</html>

```

## Person: 張博文_____________

## Date: 7/27______________
