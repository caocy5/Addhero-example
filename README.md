# Addhero-example
an add hero example

<!doctype html>
<html>
<head>
<script type="text/javascript ">
<!--
function addhero(){

for (var i=0;i<mytab.rows.length;i++){

var eachRow=mytab.rows[i];
if(eachRow.cells[0].innerText==num.value){
window.alert("编号不能重复");
return;

}

}

var newTableRow=mytab.insertRow(mytab.rows.length);
newTableRow.insertCell(0).innerText=num.value;
newTableRow.insertCell(1).innerText=username.value;
newTableRow.insertCell(2).innerText=nickname.value;


}

//-->
</script>
</head>

<body>

<h1>英雄排行榜</h1>
<table id="mytab" border="1px">
<tr><td> 排名</td><td>姓名</td><td>外号</td></tr>
<tr><td>1 </td><td>宋江</td><td>及时雨</td></tr>
<tr><td> 2</td><td>卢俊义</td><td>玉麒麟</td></tr>
</table>
<h1>请输入新的好汉</h1>
编号<input type="text" id="num"/><br>
姓名<input type="text" id="username"/><br>
外号<input type="text" id="nickname"/><br>
<input type="button" onclick="addhero()" value="添加英雄"/>
</body>
</html>
