- <!DOCTYPE html>
<html>
<head>
<title> Makine llogaritese ne HTML CSS JavaScript </title>
<style>
  
body {
 
background-repeat:no-repeat;
background-position:center;
background-size:cover;
}
#button {
font-size:20px;
width:60px;
height:60px;
border-radius:5px;
box-shadow:0px 0px 30px black;
margin:3px;
border-color:red green;
}
#reset {
color:white;
background-color:red;
font-size:20px;
width:60px;
height:60px;
border-radius:5px;
box-shadow:0px 0px 5px white;
margin:3px;
border-color:red green;
}
.button {
font-size:20px;
width:60px;
height:60px;
border-radius:5px;
margin:3px;
color:white;
background-color:black;
box-shadow:0px 0px 30px black;
margin:3px;
border-color:red green;
}
#button:hover, #reset:hover, .button:hover {
background-color:darkred;
}
#display {
text-align:center;
padding:5px;
margin-bottom:20px;
font-size:20px;
width:30%;
height:40px;
border-radius:5px;
color:darkred;
box-shadow:0px 0px 50px green;
border-color:red green;
}
fieldset {
width:75%;
height:500px;
border-radius:10px;
box-shadow:0px 0px 100px green;
background-color:teal, opacity:0.5;
 
background-size:contain;
border-color:red green; 
}
  
</style>
</head>
<body bgcolor="black">
  
  
<br /><br /><br /><br /><br /><br />
<center>
<fieldset>
<br /><br /><br /><br />
<form name="llogarites">
<input id="display" type="text" name="shadow" readonly="readonly">
<br />
<input id="button" type="button" value="1" onclick="llogarites.shadow.value += '1'">
<input id="button" type="button" value="2" onclick="llogarites.shadow.value += '2'">
<input id="button" type="button" value="3" onclick="llogarites.shadow.value += '3'">&nbsp&nbsp
<input class="button" type="button" value="+" onclick="llogarites.shadow.value += '+'">
<input class="button" type="button" value=">" onclick="llogarites.shadow.value += '>'">
<input class="button" type="button" value="." onclick="llogarites.shadow.value += '.'">
<br />
<input id="button" type="button" value="4" onclick="llogarites.shadow.value += '4'">
<input id="button" type="button" value="5" onclick="llogarites.shadow.value += '5'">
<input id="button" type="button" value="6" onclick="llogarites.shadow.value += '6'">&nbsp&nbsp
<input class="button" type="button" value="-" onclick="llogarites.shadow.value += '-'">
<input class="button" type="button" value="<" onclick="llogarites.shadow.value += '<'">
<input class="button" type="button" value="^" onclick="llogarites.shadow.value += '^'">
<br />
<input id="button" type="button" value="7" onclick="llogarites.shadow.value += '7'">
<input id="button" type="button" value="8" onclick="llogarites.shadow.value += '8'">
<input id="button" type="button" value="9" onclick="llogarites.shadow.value += '9'">&nbsp&nbsp
<input class="button" type="button" value="*" onclick="llogarites.shadow.value += '*'">
<input class="button" type="button" value=">=" onclick="llogarites.shadow.value += '>='">
<input class="button" type="button" value="===" onclick="llogarites.shadow.value += '==='">
<br />
<input id="button" type="button" value="0" onclick="llogarites.shadow.value += '0'">
<input id="reset" type="reset" value="C" onclick="llogarites.shadow.value += ' '">
<input class="button" type="button" value="=" onclick="llogarites.shadow.value =eval(llogarites.shadow.value)">&nbsp&nbsp
<input class="button" type="button" value="/" onclick="llogarites.shadow.value += '/'">
<input class="button" type="button" value="<=" onclick="llogarites.shadow.value += '<='">
<input class="button" type="button" value="%" onclick="llogarites.shadow.value += '%'">
</form>
</fieldset>
</center>
</body>
</html>
