


<html>

<head>

	<meta charset="utf-8">

	<meta name="viewport" content="width=device-width, initial-scale=1">

	<title>Square Pia</title>

</head>

<body>

<table align="center">

	<tr>

		<td>

<h2 align="center">JavaScript Square Generator</h2>



<p>Please input a number:</p>



<input id="num">



<button type="button" onclick="myFunction()">Submit</button>



<p id="demo" style=""></p>

</td>

</tr>

</table>

<script>

function myFunction() {

  // Get the value of the input field with id="numb"

  let x = document.getElementById("num").value;

  // If x is Not a Number or less than one or greater than 10

  let text;

  if (isNaN(x)) {

    text = "Input not valid";

  } else {

    text = "Input Valid, Squared value of inputted number: " + Math.pow(x,2);

  }

  document.getElementById("demo").innerHTML = text;

}

</script>

</body>

</html>
