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
<center>LOVE</center>

<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>倒计时</title>
    <style type="text/css">
        #box {
            width:400px;
            height: 200px;
            line-height: 200px;
            margin: 100px auto;
            color:red;
        }
    </style>
</head>
<body>
    <div id="box"></div>
</body>
<script type="text/javascript">
    var box = document.getElementById('box');
    setInterval(fun,1000);
    function fun(){
        var date = new Date();//得到当前时间
        // console.log(date);
        var endTime = new Date("2026/8/11");//设定终点时间
        // console.log(endTime);
        var ms = endTime.getTime()-date.getTime();//得到相差毫秒数
        // console.log(ms);
        var d = parseInt(ms/(1000*60*60*24)%30);//得到天数
        var h = parseInt(ms/(1000*60*60)%24);//得到小时数
        var min = parseInt(ms/(1000*60)%60);//得到分钟数
        var s = parseInt(ms/1000%60);//得到秒数
        m<10 ? m='0'+m : m;//如果月份数小于10,显示为0x,大于或等于则为原值
        d<10 ? d='0'+d : d;
        h<10 ? h='0'+h : h;
        min<10 ? min='0'+min : min;
        s<10 ? s='0'+s : s;
        box.innerHTML = "距离梦想时刻 "+"天"+h+"小时"+min+"分"+s+"秒";
    }
    
</script>
</html>
