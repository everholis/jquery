## example_eq.html

```html
<!doctype html>
<head>
  <meta charset="euc-kr">
  <title>sample eq</title>
  <script type="text/javascript" src="http://code.jquery.com/jquery-latest.min.js"></script>
</head>
<body>

<ul>
	<li>ù��°</li>
	<li>�ι�°</li>
	<li>����°</li>
	<li>�׹�°</li>
	<li>�ټ���°</li>
</ul>


<script>
	$( "li" ).eq(2).css( "background-color", "red" ); // li ����� 3��° li�� ������ ���������� ���� (0���� ī��Ʈ ����)
</script>
    
</body>
</html>
```

