109306013 form
<!DOCTYPE html>			
<html>				
<body>				
<table border="1">			
<form>	
<thead>
		<th colspan="3">About me -- 109306013</th>
	<tr>

		<th rowspan = "3">
		    <img src = "https://www.zhifure.com/upload/images/2018/7/20221451336.jpg"width ="400"height = "300"></th>
		<td colspan = "2">
			<label for="name"><b>Name:</label>
			<input type="text" name="name" id="name"size="28"><br>
			Gender:
			<input type="radio" id="Male" name="gender" value = "Male">  
			<label for="Male">Male</label>
			<input type="radio" id="Female"name="gender"value="Female">
			<label for="Female">Female</label>
			<input type="radio" id="Other" name="gender" value="Other">
			<label for="Other">Other</label></th>
		</td>
	<tr>
		<td>
			<label for="county"><b>County:</label>
			<select name="county" id="county">
				<option value="taipei">Taipei</option>
				<option value="taichung">Taichung</option>
				<option value="tainan">Tainan</option>
			</select>
		</td>
		<td>
		<label for="birthday"><b>Birthday:</label>
		<input type="text" name="birthday" id="birthday">
       	</td>
        </tr>
    <tr>
    	<td colspan="2">
    		<label for="email"><b>E-mail:</label>
    		<input type="text" id="email"name="email"size="50" >
    	</td>
    </tr>
</thead>
<tbody>
	<tr>
		<td><b>Hobby</td>
		<td colspan="2"><b>
			<input type="checkbox"id="swimming"name="swimming"value="swimming">
			<label for="swimming">Swimming</label>
			<input type="checkbox"id="volleyball"name="volleyball"value="volleyball">
			<label for="volleyball">Volleyball</label>
			<input type="checkbox"id="movies"name="movies"value="movies">
			<label for="movies">Movies</label>
			<input type="checkbox"id="games"name="games"value="games">
			<label for="games">Games</label>
			<input type="checkbox"id="sleeping"name="sleeping"value="sleeping">
			<label for="sleeping">Sleeping</label>
		</td>
	</tr>
	<tr>
		<td><b>Skill</td>
		<td colspan="2"><b>
			<input type="checkbox"id="Java"name="Java"value="Java">
			<label for="Java">Java</label>
			<input type="checkbox"id="HTML"name="HTML"value="HTML">
			<label for="HTML">HTML</label>
			<input type="checkbox"id="Python"name="Python"value="Python">
			<label for="Python">Python</label>
			<input type="checkbox"id="Microsoft Office"name="Microsoft Office"value="Microsoft Office">
			<label for="Microsoft Office">Microsoft Office</label>
			<input type="checkbox"id="Adobe Premiere"name="Adobe Premiere"value="Adobe Premiere">
			<label for="Adobe Premiere">Adobe Premiere</label>
	    </td>
	</tr>
	<tr>
		<td><b>Say Something</td>
		<td colspan="3">
			<textarea id="say something" name="say something" rows="5"cols="65">Say something here.
			</textarea>
		</td>
	</tr>
	<tr>
		<th colspan="3">
			<input type="submit" value="Submit">
			<input type="reset" value="重設">
		</th>
	</tr>
</tbody>
</form>
</html>
