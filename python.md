## Python

### アップロード後のパーミッションの変更
![image](https://user-images.githubusercontent.com/1501327/164583307-9b39a7f8-ee85-476e-8506-d867325edcee.png)\
![image](https://user-images.githubusercontent.com/1501327/164582975-0cb41cf0-ab4b-4bac-a001-247b09bc6193.png)


### 以下、f-string

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
