<html>
<head>
<title>pop</title>
<meta charset="utf-8"/>

</head>
<body>
<center>
<form>
<p></p>
<input type="E-mail" id="11"/>
<br>
<input type="password" id="22"/>
<input type="checkbox" id="33" onclick="pop()"/>
</form>
<style>
form{
width:30px;
height:40px;
background-color:#ffffff;
}
body{
background-color:gray;
}
</style>
</center>
<script>
function pop(){
if(33 == true){
document.getElementById("22").type="text";
}else{
document.getElementById("22").type="password";
}
</script>
</body>
</html>
