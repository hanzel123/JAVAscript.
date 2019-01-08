# activity 2
<!DOCTYPE html>
<html>
<head>
	<title>Javascript Activity 1 - [Hanzel]</title>
	<link rel="stylesheet" type="text/css" href="style.css">
	<link rel="stylesheet" type="text/css" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css">
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1"		>
</head>
<body bgcolor style="background-color:#FF5733">
<div class="container"
<label>Enter Grade:</label>
<input type="text" id='grd'>
<input type="button"value="GO!" onclick="search()">
<p>65-74:POOR</p>
<p>75-79:GREAT</p>
<p>80-84:GOOD</p>
<p>85-94:VERY GOOD</p>
<p>95-98:EXCELLENT</p>
<h3>Grade bracket belong to:</h3>
<h3 id="result">
</div>
<script>
                                                                                            
function search()
{
	var grd=Number(document.getElementById('grd').value);
		
		if(isNaN('grd')==false)
		var bracket=""
	{
		if(grd>94)
		{
		document.getElementById('result').innerHTML="EXCELLENT";
		}
		else if(grd>84)
		{
		document.getElementById('result').innerHTML="VERY GOOD";
		}
		else if(grd>79)
		{
		document.getElementById('result').innerHTML="GOOD";
		}
		else if(grd>74)
		{
		document.getElementById('result').innerHTML="NICE";
		}
		else if(grd<75)
		{
		document.getElementById('result').innerHTML="POOR";
		}	
		else 
		{
		document.getElementById('result').innerHTML="INVALID VALUE";
		}

	}

}


</script>
</body>
