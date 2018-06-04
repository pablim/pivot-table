# pivot-table

# Requirements

jQuery https://jquery.com/

# Exemple

´´´<!DOCTYPE html>
<html>
<head>
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<script type="text/javascript" src="jquery-3.2.1.js"></script>
	<script type="text/javascript" src="pivot-table.js"></script>
</head>
<body>	

<div class="w3-row w3-margin">
	<div class="w3-col">
		<table class="pv-pivot-table">
			<thead>
				<tr>
					<th>Coluna 1</th>
					<th>Coluna 2</th>
					<th>Coluna 3</th>
					<th>Coluna 4</th>
					<th>Coluna 5</th>
				</tr>
			</thead>
			<?php for($i=0; $i<5; $i++) {?>
				<tr>
					<td>valor 1</td>
					<td>valor 2</td>
					<td>valor 3</td>
					<td>valor 3</td>
					<td>valor 3</td>
				</tr>
			<?php }?>
		</table>
		</div>
	</div>
</body>
</html>
´´´
