# simple-calculator-with-html-javascript
calculator using java script and html
<!doctype html>
<html>
<head>
<title>Calculator</title>
<script type="text/javascript">
	   function dis (x){
frm.txt.value=frm.txt.value+x;
}
// CE
      function ce (){
       frm.txt.value ='';
}
//backspace
      function bs(){
	   frm.txt.value = frm.value.slice(0,frm.txt.value.length-1);
}
</script>
<style type="text/css">
	 #textbox{
	 	margin-top: 10px;
	 	margin-bottom: 10px;
	 	margin-left: 3px;
	 	text-align: right;
	 	width: 285px;
	 }

#container{
	border: 3px solid black;
	width: 300px;
	border-radius: 5px;
	background-color: #38195f;

}
.btn{
	width: 60px;
	height: 60px;
    border-radius: 50px;
    margin-right: 12px;

}
</style>
</head>
<body>
	<div id="container">
    <form name="frm">
    	<input id="textbox"type="textbox" name="txt"><br>
    	<input class="btn" id="" type="button" value="CE" onclick="ce()">
    	<input class="btn" id="" type="button" value="Backspace" onclick="bs()" > 
    	<input class="btn" type="button" name="btnleft" value="(" onclick="dis(btnleft.value)">
    	<input class="btn" type="button" name="btnright" value=")" onclick="dis(btnright.value)"><br>
    	<input class="btn" type="button" name="btn9" value="9" onclick="dis(btn9.value)">
        <input class="btn" type="button" name="btn8" value="8" onclick="dis(btn8.value)">
        <input class="btn" type="button" name="btn7" value="7" onclick="dis(btn7.value)">
        <input class="btn" type="button" name="btnd" value="/" onclick="dis(btnd.value)">
        <br>

        <input class="btn" type="button" name="btn6" value="6" onclick="dis(btn6.value)">
        <input class="btn" type="button" name="btn5" value="5" onclick="dis(btn5.value)">
        <input class="btn" type="button" name="btn4" value="4" onclick="dis(btn4.value)">
        <input class="btn" type="button" name="btnm" value="*" onclick="dis(btnm.value)">
        <br>
        <input class="btn" type="button" name="btn3" value="3" onclick="dis(btn3.value)">
        <input class="btn" type="button" name="btn2" value="2" onclick="dis(btn2.value)">
        <input class="btn" type="button" name="btn2" value="2" onclick="dis(btn2.value)">
        <input class="btn" type="button" name="btn1" value="1" onclick="dis(btn1.value)"> <br>
        <input class="btn" type="button" name="btns" value="-" onclick="dis(btns.value)">
        <input class="btn" type="button" name="btndot" value="." onclick="dis(btndot.value)">
        <input class="btn" type="button" name="btneql" value="=" onclick="txt.value=eval(txt.value)">
        <input class="btn" type="button" name="btnp" value="+" onclick="dis(btnp.value)">
</form>
</div>
</body>


    
</html>
