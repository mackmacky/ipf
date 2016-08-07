<!DOCTYPE html>
<html>
	<head>
		<title>International Partner Formater</title>
		
		<script>
			<!--Funtion to generate Format-->
			function generate_format_string(){
				var formated_text = "";
				formated_text += document.getElementById("partner_name").value + " | ";
				formated_text += document.getElementById("reference_number").value + " | ";
				formated_text += document.getElementById("reciever_name").value + " | ";
				formated_text += document.getElementById("address").value + " | ";
				formated_text += document.getElementById("cell_number").value + " | ";
				formated_text += document.getElementById("bday").value + " | ";
				formated_text += document.getElementById("amount").value + " | ";
				formated_text += document.getElementById("id_type").value + " | ";
				formated_text += document.getElementById("id_number").value + " | ";
				formated_text += document.getElementById("id_expiration").value + " | ";
				formated_text += document.getElementById("sender_name").value + " | ";
				formated_text += document.getElementById("origin").value + " | ";
				<!-- Copy the formated text to the clipboard -->
				window.prompt("Please Copy", formated_text);
			} <!-- end funtion generate_format_string-->
		</script>
	</head>
	
	<body>
		<h1>International Partner Transaction Formater</h1>
		<form> <!-- Data Entry Format-->
			Partner: 
			<input type="text" id="partner_name" ><br>
			Reference Number:
			<input type="text" id="reference_number" ><br>
			Reciever Name:
			<input type="text" id="reciever_name" ><br>
			Address:
			<input type="text" id="address" ><br>
			Cell Number:
			<input type="text" id="cell_number" ><br>
			Birth Day:
			<input type="date" id="bday" ><br>
			Amount:
			<input type="text" id="amount" ><br>
			ID Type:
			<input type="text" id="id_type" ><br>
			ID Number:
			<input type="text" id="id_number" ><br>
			ID Expiration:
			<input type="date" id="id_expiration" ><br>
			Sender Name:
			<input type="text" id="sender_name" ><br>
			Origin:
			<input type="text" id="origin" ><br>
			Is Regular:
			<input type="radio" id="yes_rad_btn" name="yesno_rad" >YES
			<input type="radio" id="no_rad_btn" name="yesno_rad" >NO<br><br>
			<input type="button" id="generate_format" value="GENERATE FORMAT" onclick="generate_format_string()"><br><br>
			Generated Format:<br>
			<textarea name="generated_format" rows="3" cols="30" message="format" id="gen_format" ></textarea>
		</form>
		

		
	</body>
</html>
