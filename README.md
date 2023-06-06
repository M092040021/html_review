# html_review
<!DOCTYPE html>
<html>
    <head>
        //放網頁資訊
    </head>
    <body>
        //放網頁內容
    </body>
</html>

放網頁資訊
<meta charset="UTF-8"/>
<title>陳柏勳的履歷</title>

放網頁內容
標題 : <h1>標題</h1> ##1(大，重要)~6(小，不重要)
文章內容 : <p>文章內容</p>
粗體 : <b>...</b>
斜體 : <i>...</i>
換行 : </br>
水平線 : </hr>
連結 : <a href = 網址、html(本地)、jpg(本地)>名稱</a>
<a href="https://www.google.com.tw/?hl=zh_TW">google</a>
<a href="page2.html">page2</a>
<a href="dir/page3.html">page3</a>
<a href="籃球1.jpg">basketball</a>
圖片 : <img src=新分頁開啟圖片之網址/>
	<img src=".jpg" width="200" (height="400")/> ##括號處不寫就等比縮放
	<video src=".mp4" controls width="300">無法載入</video>>  ## controls 為控制音量、暫停、開始
	youtube嵌入就會有:<iframe...>

列表
(<!--ol有排序-->，<!--ul沒有排序-->)
<ul>
<li>google</li>
<li>facebook</li>
<li>ig</li>
</ul>

表格  
<table width="400">
<tr>  ##第一row
<td>1</td>
<td>2</td>
<td>3</td>
</tr>
<tr>  ##第二row
<td>99</td>
<td>4</td>
<td>6</td>
</tr>
</table>

容器div(一起行動 or 排版用、直接換行)
<div style="color:blue;">
    <ul>
        <li>google</li>
        <li>facebook</li>
        <li>ig</li>
    </ul>

    <table width="400">
        <tr>
            <td>1</td>
            <td>2</td>
            <td>3</td>
        </tr>
        <tr>
            <td>1</td>
            <td>2</td>
            <td>3</td>
        </tr>
    </table>
</div>

<div>div1</div>
<div>div2</div>

span(向右排滿)
<span>span1</span>
<span>span2</span>
        
輸入
<input type="text" placeholder="帳號"/>
<input type="password" placeholder="密碼"/>
<input type="date" />
<input type="range" />
<input type="file" />
<input type="checkbox" />

<textarea>
我是神嗎
</textarea>

JavaScript(不熟)
<script src="script.js"></script> <!--盡量放最後-->
