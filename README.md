<html>
	<head></head>

	<script type="text/javascript">
	
	function copy(){
		var a= document.getElementById("n1");
		var b= document.getElementById("n2");
		var c= document.getElementById("n3");
		var d= document.getElementById("n4");
		var e= document.getElementById("n5");
		
		b.value=a.value;
		c.value=a.value;
		d.value=a.value;
		d.value=a.value;
		e.value=a.value;
	}
	</script>
	<body>
	<center>
		<h3 style="background-color:#248f8f; padding:10px 20px; color:white; width:350px">Assignment</h3>
		<label>Input 1<br> </label><input type="text" name="textbox1" id="n1" oninput="copy();"/>
		<br><br>
		<label>Input 2<br> </label><input type="text" name="textbox2" id="n2"/>
		<br><br>
		<label>Input 3<br> </label><input type="text" name="textbox3" id="n3"/>
		<br><br>
		<label>Input 4<br> </label><input type="text" name="textbox4" id="n4"/>
		<br><br>
		<label>Input 5<br ></label><input type="text" name="textbox5" id="n5"/>
		<br><br>
	</center>
	</body>
</html>
