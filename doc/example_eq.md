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
	<li>첫번째</li>
	<li>두번째</li>
	<li>세번째</li>
	<li>네번째</li>
	<li>다섯번째</li>
</ul>


<script>
	$( "li" ).eq(2).css( "background-color", "red" ); // li 요소중 3번째 li의 배경색을 빨간색으로 변경 (0부터 카운트 시작)
</script>
    
</body>
</html>
```

