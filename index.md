# <center>韶翎裳 ♡ 桑小染</center>
##### <center>3479506443 - 1060802477</center>
###### <center>-----==-----==-----==-----==-----==-----==-----==-----==-----==-----</center>

#### <center><相恋于 2019年02月11日 19:55 星期一>

###### <center><2019ねん02がつ じゅういちにち 19:55 に恋する>

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
