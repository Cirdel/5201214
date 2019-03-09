# <center>韶翎裳 💗 桑小染</center>
##### <center>3479506443 - 1060802477</center>
### <center>相恋于2019年02月11日19点55分过几秒</center>
### <center>思念你的此时此刻是北京时间<center>
<center>
<html>

<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<title>现在时间</title>
<script type="text/javascript">
var attime;
function clock() {
var time = new Date();
attime = " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + " " + time.getHours() + ":" + time.getMinutes() + ":" + time.getSeconds() ;
document.getElementById("clock").value = attime;
            }
//          setInterval()计时器来显示动态时间。
            setInterval(clock,100);
        </script>
    </head>

<body>
<form>
<input type="text" id="clock" size="99" />
</form>       
</body>

</html>
</center>
Love
<html>
function showtime(){
 
var today,hour,second,minute,year,month,date;
 
var strDate ;
 
today=new Date();
 
var n_day = today.getDay();
 
switch (n_day){

case 0:{

strDate = "星期日"
 
}break;
 
case 1:{
 
strDate = "星期一"
 
}break;
 
 case 2:{
 
strDate ="星期二"
 
}break;
 
case 3:{
 
strDate = "星期三"
 
}break;
 
case 4:{
 
strDate = "星期四"
 
}break;
 
case 5:{
 
strDate = "星期五"
 
}break;
 
case 6:{
 
strDate = "星期六"
 
}break;
 
case 7:{
 
strDate = "星期日"
 
}break;
 
}
 
year = today.getFullYear();
 
month = today.getMonth()+1;
 
date = today.getDate();
 
hour = today.getHours();
 
minute =today.getMinutes();
 
second = today.getSeconds();
 
 
 
if (month >= 1 && month <= 9) {
 
month = "0" + month;
 
}
 
if (date >= 0 && date <= 9) {
 
date = "0" + date;
 
}
 
if (hour >= 0 && hour <= 9) {
 
hour = "0" + hour;
 
}
 
if (minute >= 0 && minute <= 9) {
 
minute = "0" + minute;
 
}
 
if (second >= 0 && second <= 9) {
 
second = "0" + second;
 
     
document.getElementById('current-time').innerHTML ="当前时间："+ year + "年" + month + "月" + date + "日" +"  "+ strDate +"   " + hour + ":" + minute + ":" + second; //显示时间
 
setTimeout("showtime();", 1000); //设定函数自动执行时间为 1000 ms(1 s)
 
}
<div class="col-xs-12 col-sm-6">
 
<i class="fa fa-plus-square-o" aria-hidden="true"></i>
 
<span id="current-time"></span>
</div>
</html>
