<!doctype html>
<html>
<head>
<meta charset="utf-8">
<h1 align="center">ACE Engineering College </h1>
<h2 align="center"> An Autonomous institute</h2>
<hr/>
<title>Student Registration Form</title>
<style type="text/css">
th {
color: #FFF;
font-size: 24px;
font-weight: bold;
text-align: left;
}
body {
background-color:#37b8a2;
color:white;
font-family:verdana;
}
</style>
</head>
<body>
<form>
<table width="700" border="0" align="center" cellpadding="0"
cellspacing="5">
<tr>
<th width="25%" height="60">&nbsp;</th>
<th><p>Student Registration Form</p></th>
<th width="10%">&nbsp;</th>
</tr>
<tr>
<td><strong>Name:</strong></td>
<td><input name="name" type="text" size="35" required/></td>
<td>&nbsp;</td>
</tr>
<tr><td><strong>DOB:</strong></td>
<td><input type="date" type="number" size="35"
required/></td>
<td>&nbsp;</td>
</tr>
<tr><td><strong>Sex:</strong></td>
<td><input type="radio" name="gender" value="male"
required>Male
<input type="radio" name="gender"
value="female">Female</td>
<td>&nbsp;</td>
</tr>
<tr>
<td><strong>Email:</strong></td>
<td><input name="Email" type="email" size="35"
required/></td>
<td>&nbsp;</td>
</tr>
<tr>
<td><strong>Address:</strong></td>
<td><input name="name2" type="text" size="35"
required/></td><td>&nbsp;</td>
</tr>
<tr>
<td><strong>Year:</strong></td>
<td><select id="slct1" name="slct1" onchange= "
populate(this.id,'slct2')" >
<option>Select..</option>
<option value="CSE1">CSE 1st Year</option>
<option value="CSE2">CSE 2nd Year</option>
<option value="CSE3">CSE 3rd Year</option>
<option value="CSE4">CSE 4th Year</option>
</select></td>
<td>&nbsp;</td></tr>
<tr>
<td><strong>Mobile Number:</strong></td>
<td><input name="Mobile no. name3" type="text"
size="35"/></td>
<td>&nbsp;</td>
</tr>
<tr><td></td>
<td><input type="reset" /><input type="submit"
value="Submit" onsubmit= "alert('your details have been
submitted!')"/></td>
<td>&nbsp;</td>
</tr>
</table>
</form>
<p align=center><b><i>With a difference in
Excellence</i></b></p>
</body>
</html>
