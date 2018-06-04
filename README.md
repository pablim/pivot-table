# Requirements

jQuery https://jquery.com/

# Exemple

```
<!DOCTYPE html>
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
			<tr>
				<td>valor 1</td>
				<td>valor 2</td>
				<td>valor 3</td>
				<td>valor 3</td>
				<td>valor 3</td>
			</tr>
			<tr>
				<td>valor 1</td>
				<td>valor 2</td>
				<td>valor 3</td>
				<td>valor 3</td>
				<td>valor 3</td>
			</tr>
			<tr>
				<td>valor 1</td>
				<td>valor 2</td>
				<td>valor 3</td>
				<td>valor 3</td>
				<td>valor 3</td>
			</tr>
		</table>
		</div>
	</div>
</body>
</html>
```
<table>
	<tr>
		<th>Header 1</th>
		<th>Header 2</th>
		<th>Header 3</th>
		<th>Header 4</th>
		<th>Header 5</th>
	</tr>
	<tr>
		<td>valor 1</td>
		<td>valor 2</td>
		<td>valor 3</td>
		<td>valor 4</td>
		<td>valor 5</td>
	</tr>
	<tr>
		<td>valor 1</td>
		<td>valor 2</td>
		<td>valor 3</td>
		<td>valor 4</td>
		<td>valor 5</td>
	</tr>
	<tr>
		<td>valor 1</td>
		<td>valor 2</td>
		<td>valor 3</td>
		<td>valor 4</td>
		<td>valor 5</td>
	</tr>
</table>

After screen width limit achieved, the pivot table is activated. The limit screen is 600px by default, you can change this value directly in pivot-table.js in line `var minWindowSize = 600;`

<table>
	<tr>
    <th>Header 1</th>
    <td>valor 1</td>
  </tr>
  <tr>
  	<th>Header 2</th>
    <td>valor 2</td>
  </tr>
  <tr>
  <th>Header 3</th>
    <td>valor 3</td>
  </tr>
  <tr>
  	<th>Header 4</th>
    <td>valor 4</td>
  </tr>
  <tr>
  	<th>Header 5</th>
    <td>valor 5</td>
  </tr>
</table>

<table>
	<tr>
    <th>Header 1</th>
    <td>valor 1</td>
  </tr>
  <tr>
  	<th>Header 2</th>
    <td>valor 2</td>
  </tr>
  <tr>
  <th>Header 3</th>
    <td>valor 3</td>
  </tr>
  <tr>
  	<th>Header 4</th>
    <td>valor 4</td>
  </tr>
  <tr>
  	<th>Header 5</th>
    <td>valor 5</td>
  </tr>
</table>

<table>
	<tr>
    <th>Header 1</th>
    <td>valor 1</td>
  </tr>
  <tr>
  	<th>Header 2</th>
    <td>valor 2</td>
  </tr>
  <tr>
  <th>Header 3</th>
    <td>valor 3</td>
  </tr>
  <tr>
  	<th>Header 4</th>
    <td>valor 4</td>
  </tr>
  <tr>
  	<th>Header 5</th>
    <td>valor 5</td>
  </tr>
</table>

