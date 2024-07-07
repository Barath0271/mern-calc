CALCULATOR
### Index.html
```
<!DOCTYPE html>
<html lang = "en">
<head>
<title> JavaScript Calculator </title>

<style>
 h1 {
      text-align: center;
      padding: 23px;
      background-color: rgb(155, 193, 208);
      color: white;
    }


#clear{
width: 270px;
border: 3px solid rgb(218, 112, 112);
	border-radius: 3px;
	padding: 20px;
	background-color: rgb(241, 189, 189);
}

.formstyle
{
width: 350px;
height: 640px;
margin: auto;
border: 3px solid rgb(30, 122, 158);
border-radius: 10px;
padding: 20px;
}



input
{
width: 20px;
background-color:rgb(190, 141, 124);
color: black;
border: 3px solid rgb(169, 118, 118);
	border-radius: 10px;
	padding: 26px;
	margin: 5px;
	font-size: 15px;
}


#calc{
width: 250px;
border: 5px solid black;
	border-radius: 3px;
	padding: 20px;
	margin: auto;
}

</style>

</head>
<body>
<div class= "formstyle">
<form name = "form1">
	
  <input id = "calc" type ="text" name = "answer"> <br> <br>

  <input type = "button" value = "AC" onclick = "form1.answer.value += 'AC' ">
  <input type = "button" value = "DEL" onclick = "form1.answer.value += 'DEL' ">
  <input type = "button" value = "%" onclick = "form1.answer.value += '%' ">
  <input type = "button" value = "." onclick = "form1.answer.value += '.' ">
  <br> <br>

  <input type = "button" value = "1" onclick = "form1.answer.value += '1' ">
  <input type = "button" value = "2" onclick = "form1.answer.value += '2' ">
  <input type = "button" value = "3" onclick = "form1.answer.value += '3' ">
   <input type = "button" value = "+" onclick = "form1.answer.value += '+' ">
  <br> <br>
  
  <input type = "button" value = "4" onclick = "form1.answer.value += '4' ">
  <input type = "button" value = "5" onclick = "form1.answer.value += '5' ">
  <input type = "button" value = "6" onclick = "form1.answer.value += '6' ">
  <input type = "button" value = "-" onclick = "form1.answer.value += '-' ">
  <br> <br>
  
  <input type = "button" value = "7" onclick = "form1.answer.value += '7' ">
  <input type = "button" value = "8" onclick = "form1.answer.value += '8' ">
  <input type = "button" value = "9" onclick = "form1.answer.value += '9' ">
  <input type = "button" value = "*" onclick = "form1.answer.value += '*' ">
  <br> <br>
  
  
  <input type = "button" value = "/" onclick = "form1.answer.value += '/' ">
  <input type = "button" value = "0" onclick = "form1.answer.value += '0' ">
    <input type = "button" value = "." onclick = "form1.answer.value += '.' ">

  <input type = "button" value = "=" onclick = "form1.answer.value = eval(form1.answer.value) ">
  <br> 
 
  <input type = "button" value = "Clear All" onclick = "form1.answer.value = ' ' " id= "clear" >
  <br> 
  
</form>
</div>
</body>
</html>
```
### Styles.css
```

<style>
 h1 {
      text-align: center;
      padding: 23px;
      background-color: rgb(9, 157, 215);
      color: white;
    }


#clear{
width: 270px;
border: 3px solid rgb(192, 177, 177);
	border-radius: 3px;
	padding: 20px;
	background-color: rgb(240, 155, 155);
}

.formstyle
{
width: 300px;
height: 530px;
margin: auto;
border: 3px solid rgb(85, 139, 161);
border-radius: 5px;
padding: 20px;
}



input
{
width: 20px;
background-color: rgb(226, 242, 239);
color: white;
border: 3px solid rgb(232, 183, 183);
	border-radius: 5px;
	padding: 26px;
	margin: 5px;
	font-size: 15px;
}


#calc{
width: 250px;
border: 5px solid black;
	border-radius: 3px;
	padding: 20px;
	margin: auto;
}

</style>
```
### Output :
![Screenshot 2024-07-07 204322](https://github.com/Barath0271/mern-calc/assets/135820464/950f7316-1ea0-4ff4-a0be-147bb8b3780a)
