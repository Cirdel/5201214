# <center>韶翎裳 💗 桑小染</center>
##### <center>3479506443 - 1060802477</center>
### <center>相恋于2019年02月11日19点55分过几秒</center>
### <center>思念你的此时此刻是北京时间<center>
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
	
var a = new Array("日","一","二","三","四","五","六");
var day1 = date.getDay();
day1 = "星期" + a[day1];
	
var currenttime = year + "年" + month + "月" + day + "日 " + hours + ":" + minutes + ":" + seconds + " " + day1;
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
<button onclick="stopTimer();" style="width:240px;">我不想看现在什么时候了!</button>
	
</body>
</html>
</center>
233
