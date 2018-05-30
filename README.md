# pivot-table

<!DOCTYPE html>
<html>
<head>
	<title></title>
	<meta charset="utf-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" type="text/css" href="w3.css">
	<script type="text/javascript" src="jquery-3.2.1.js"></script>
	<script type="text/javascript" src="pivot-table.js"></script>
</head>
<body>

	<div class="window-size"></div>

	<div class="w3-row w3-margin">
		<div class="w3-col">
		<table class="w3-table w3-striped w3-border w3-bordered w3-card-4 pv-pivot-table">
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

