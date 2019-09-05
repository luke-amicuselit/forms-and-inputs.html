<!DOCTYPE html>
<html>
<head>
	<title>form & input exercise</title>
</head>
<body>
	<h1>Register</h1>

<!-- action - where the form send data to -->
<!-- method - what HTTP method (get/post)-->

	<form>
		<label for="first">First Name:</label>
			<input name="first" id="first" type="text" placeholder="John" required>
		</label>
		<label for="last">Last Name:</label>
			<input name="last" id="last" type="text" placeholder="Smith" required>
		</label>
	<div>
		<label>
			<label for="male">Male</label>
			<input name="gender" id="male" type="radio" value="male"
			value="MALE">
			<label for="female">Female</label>
			<input name="gender" id="female" type="radio" value="female"
			value="FEMALE">
			<label for="other">Other</label>
			<input name="gender" id="other" type="radio" value="other"
			value="OTHER">
		</label>
	</div>
		<div>
		<label for="username">Email:</label>
		<input id="username" type="email" required placeholder="your email">
		<label for="password">Password:</label>
		<input type="password" placeholder="your password" pattern=".{5,10}" required title="Password must be between 5 and 10 characters"> 
		</label>
	</div>
		<div>
		<label>
			Birthday:
			<label>
				<select name="Month">
					<option value="">Month
					</option>
						<option value="January">Jan</option>
						<option value="Feburary">Feb</option>
						<option value="March">Mar</option>
						<option value="April">Apr</option>
						<option value="May">May</option>
						<option value="June">June</option>
						<option value="July">July</option>
						<option value="August">Aug</option>
						<option value="September">Sept</option>
						<option value="October">Oct</option>
						<option value="November">Nov</option>
						<option value="December">Dec</option>
				</select>
			</label>
			<label>
				<select name="Day">
					<option value="">Day
					</option>
						<option value="1">1</option>
						<option value="2">2</option>
						<option value="3">3</option>
						<option value="4">4</option>
						<option value="5">5</option>
						<option value="6">6</option>
						<option value="7">7</option>
						<option value="8">8</option>
						<option value="9">9</option>
						<option value="10">10</option>
						<option value="11">11</option>
						<option value="12">12</option>
						<option value="13">13</option>
						<option value="14">14</option>
						<option value="15">15</option>
						<option value="16">16</option>
						<option value="17">17</option>
						<option value="18">18</option>
						<option value="19">19</option>
						<option value="20">20</option>
						<option value="21">21</option>
						<option value="22">22</option>
						<option value="23">23</option>
						<option value="24">24</option>
						<option value="25">25</option>
						<option value="26">26</option>
						<option value="27">27</option>
						<option value="28">28</option>
						<option value="29">29</option>
						<option value="30">30</option>
						<option value="31">31</option>
				</select>
			</label>
			<label>
				<select name="Year">
					<option value="">Year
					</option>
						<option value="1973">1973</option>
						<option value="1974">1974</option>
						<option value="1975">1975</option>
						<option value="1976">1976</option>
						<option value="1977">1977</option>
						<option value="1978">1978</option>
						<option value="1979">1979</option>
						<option value="1980">1980</option>
						<option value="1981">1981</option>
						<option value="1982">1982</option>
						<option value="1983">1983</option>
						<option value="1984">1984</option>
						<option value="1985">1985</option>
						<option value="1986">1986</option>	
						<option value="1986">1986</option>
						<option value="1987">1987</option>
						<option value="1988">1988</option>
						<option value="1989">1989</option>
						<option value="1990">1990</option>
						<option value="1991">1991</option>
						<option value="1992">1992</option>
						<option value="1993">1993</option>
						<option value="1994">1994</option>
						<option value="1995">1995</option>
						<option value="1996">1996</option>
						<option value="1997">1997</option>
						<option value="1998">1998</option>
						<option value="1999">1999</option>
						<option value="2000">2000</option>
				</select>
			</label>
		<div>
		<label>I agree to the terms and conditions</label>
			<input id="agreed" type="checkbox" required>
			</label>
	</div>
		<input type="submit">

	</form> 

</body>
</html>
