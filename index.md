# <center>韶翎裳 ♡ 桑小染</center>
##### <center>3479506443 - 1060802477</center>
#### <center><相恋于 2019年02月11日 19:55 星期一>

###### <center><2019ねん02がつ じゅういちにち 19:55 に恋する>

###### <center>-----==-----==-----==-----==-----==-----==-----==-----==-----==-----</center>
	
### <center>思念你的此时此刻是<center>
<center>
<html>
<head>
<meta charset="utf-8">
<title>js setInterVal()实时显示时间、日期</title>
<script>
window.onload = displayDate;	
function displayDate(){
	var date = new Date();
	var year = date.getFullYear();
	
	var month = date.getMonth()+1;
	month = ((month < 10)?"0":"") + month;
	var day = date.getDate();
	day = ((day < 10)?"0":"") + day;
	
	var hours = date.getHours();
	hours = ((hours < 10)?"0":"") + hours;
	
	var minutes  = date.getMinutes();
	minutes = ((minutes < 10)?"0":"") + minutes;
	
	var seconds = date.getSeconds();
	seconds = ((seconds<10)?"0":"") + seconds;
	
	var a = new Array("星期日にちようび","星期一げつようび","星期二かようび","星期三すいようび","星期四もくようび","星期五きんようび","星期六どようび");
	var day1 = date.getDay();
	day1 = a[day1];
	
	var currenttime = "<" + year + "年ねん" + month + "月がつ" + day + "日 " + hours + ":" + minutes + ":" + seconds + " " + day1 + ">";
	document.getElementById("demo").innerHTML = currenttime;
	
}
var  timer = window.setInterval(displayDate,1000);
function stopTimer(){
	window.clearInterval(timer);
}
</script>
</head>
<body>
 
<p id="demo"></p>

	
</body>
</html>
</center>
###### <center>-----==-----==-----==-----==-----==-----==-----==-----==-----==-----</center>
<center>我爱你</center>
<center>
<html>
    <head>
        <meta http-equiv=" "Content-Type" "content=" "text/html;charset=UTF-8" ">
        <title>倒计时</title>
    </head>
    <body>
      <input type=" "text" " value=" " id="input" size=" "500" ">
 
    <script>    
    var txt= document.getElementById("input");
    setInterval(function () {
        //获取系统当前时间
        var now = new Date();
        //实例化今年跨年时间   2019/1/1  这里的0表示1月份
        var targDate = new Date(now.getFullYear() + 1, 0, 1);
        //跨年时间与此时此刻时间差（毫秒）
        var long = targDate - now;
        var leftDay = parseInt(long/ 1000 / 60 / 60 / 24);
        long = long % (1000 * 60 * 60 * 24);
        var leftHour =parseInt(long / 1000 / 60 / 60);
        long = long % (1000 * 60 * 60);
        var leftMinute = parseInt(long / 1000 / 60) ;
        long = long % (1000 * 60 );
        var leftSeconde = parseInt(long / 1000);
        txt.value= now.getFullYear() +"爱情列车到达下一年还剩" + leftDay
                + "天" +leftHour + "时"+leftMinute+"分"+leftSeconde+"秒";
    }, 1000);
 
</script> 
    </body>
</html>
</center>
