<!DOCTYPE html>
<html>
<head>
	<title> quiz</title>

</head>


<body style="background-color:lightblue">
<style >
	th, td { padding: 30px }
	{ width: 50px heigh:50px }

	fieldset{
  display: block;
  margin-left: 20px;
  margin-right:600px;
  padding-top: 0.35em;
  padding-bottom: 0.625em;
  padding-left: 0.75em;
  padding-right: 0.75em;
  border:2px groove (internal value);
	}
</style>
<fieldset>
<table>
	<form>
	
<legend><h1>Registration Details:</h1></legend>

<tr>
<td>
 <label for="fname"> uniersity:</label>
 <input  type="text" name="fname" value="">
</td>	

</tr>

<tr>
	<td>
		<label for="insitute"> Address:</label>
<input type="text" name="insitute" value="">

	</td>

</tr>

<tr>
	<td>	
 <label for="cars">Branch:</label>
<style #Branch>{
	color: white
}
</style>
  <select id="Branch" name="Branch">
    <option value="Comunication">comunication</option>
    <option value="Civil">civil</option>
    <option value="Archric">Archric</option>
    <option value="Mechan">Mechan</option>
  </select>
	</td>
</tr>



<tr>
	<td>	
		<label for="degree">Degree:</label>
<select name=" degree" value= "degree" >
  <option value="1">1</option>
  <option value="2">2</option>
  <option value="3">3</option>
  <option value="4">4</option>
</select>
 <input type="radio" id="pursuing" name="state" value="pursuing">
  <label for="pursuing">pursuing</label>
  <input type="radio" id="completed" name="gender" value="completed">
  <label for="completed">completed</label>
	</td>
</tr>

<tr>
	<td>
		 <label for="aver">Average CPL:</label>
  <select id="aver" name="aver" size="2" >
    <option value="four">4</option>
    <option value="three">3</option>
    <option value="two">2</option>
    <option value="one">1</option>
  </select>

  	 <label for="UPto">UPto:</label>
  <select id="UPto" name="UPto" size="2" >
    <option value="two">2</option>
    <option value="three">3</option>
    <option value="fourr">4</option>
    <option value="fife">5</option>
  <option value="six">6</option>
    <option value="seven">7</option>
      <option value="eight">8</option>
  </select>
 Th symester
	</td>
</tr>
<tr>
	<td>
		
<label for="exper">Experience:</label>
  <select id="exper" name="exper" size="2" >
    <option value="1y">from 1 to 2</option>
    <option value="2y">more than 3</option>
    <option value="3y">more than 5</option>
  </select>
Years
	</td>
</tr>

<tr>
	<td>
		
<label for=" fyour webite"> your webite or blog:</label>
<input type="url" name="fyour webite" value="http://">

	</td>
</tr>

</form>
</table>
</fieldset>
</body>
</html>
