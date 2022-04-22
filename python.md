## Python

```py
view = f"""<!DOCTYPE html>
<html>
<head>
	<meta content="width=device-width, initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no" name="viewport">
	<meta charset="UTF-8">
</head>
<body>
<div id="main">
	<form method="get">
		<div>
			<div>氏名</div>
			<div><input type="text" name="field1" value=""></div>
		</div>

		<div>
			<div>フリガナ</div>
			<div><input type="text" name="field2" value=""></div>
			<div><input type="submit" name="send" value="送信"></div>
		</div>
	</form>
</div>
</body>
</html>"""

print( view )
```
