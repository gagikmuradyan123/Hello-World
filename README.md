# Hello-World
my fist site



<! DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Best klick</title>
<link rel="stylesheet" href="style14725.css">
</head>
<body>
<input type="text" id="myText" placeholder="Search">

<button onclick="myFunction()"><a href="https://www.youtube.com/results?search_query=javasr">test</a></button>
<p id="my"></p>

<script>
function myFunction()
{
var x =document.getElementById("myText").value;


if(x == "privet")
{
document.getElementById("my").innerHTML = "Hello Gag";
}

else 
{
document.getElementById("my").innerHTML = "Eror 606";
}

}
</script>

	   


</body>
</html>
