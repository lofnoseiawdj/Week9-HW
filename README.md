Week9_HW
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title></title>
</head>
<body>

<table border=‘1’>
	<tr>
		<th colspan="3">About--109306082</th>
	</tr>
	<tr>
		<td rowspan="3"><img src="Sorrylive.jpg" width="100" height="100" alt="personal photo"></td>
		<td colspan="2">Name:<input type="text" name="name"><br>
			Gender:<input type="radio" name="Male">Male
			<input type="radio" name="Female">Female
			<input type="radio" name="Other">Other</td>
	</tr>
	<tr>
		<td>County:<select name="County">
			<option>Taipei</option>
			<option>Tainan</option>
			<option>Taichung</option>
			<option>Taoyuan</option>
			<option>Hualien</option>
		</select>
		</td>
		<td>Birthday:<input type="date" name="Birthday"></td>
	</tr>
	<tr>
		<td colspan="2">E-mail:<input type="mail" name="E-mail"></td>
	</tr>
	<tr>
		<td>Hobby</td>
		<td colspan="2"><input type="checkbox" name="Swimming">Swimming
			<input type="checkbox" name="Volleyball">Volleyball
			<input type="checkbox" name="Movie">Movie
			<input type="checkbox" name="Game">Game
			<input type="checkbox" name="sleep">sleep</td>
	</tr>
	<tr>
		<td>Skill</td>
		<td colspan="2"><input type="checkbox" name="Java">Java
			<input type="checkbox" name="HTML">HTML
			<input type="checkbox" name="Python">Python
			<input type="checkbox" name="Microsoft Office">Microsoft Office
			<input type="checkbox" name="Premiere">Premiere</td>
	</tr>
	<tr>
		<td>Say Something</td>
		<td colspan="2"><textarea name="saysth" placeholder="Say something here."></textarea></td>
	</tr>
	<tr>
		<td colspan="3"><input type="submit" name="submit"><input type="reset" name="reset"></td>
	</tr>
</table>

</body>
</html>
