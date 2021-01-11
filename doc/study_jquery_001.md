# 001 jquery study

[TOC]



## 기초

- jQuery는 자바스크립트 라이브러리이다
- jQuery는 자바스크립트 프로그래밍을 단순화한다.
- jQuery는 HTML 태그를 선택하고, 태그의 액션을 수행하는데 최적이다.



## 기본 문법

- jQuery 사용 준비

  ```javascript
  <script type="text/javascript" src="jquery.js"></script>
  ```
  
  
  
- $ 기호는 jQuery를 정의/접근하는 기호이다.

- 가장 기본적인 문법은 **$(selector).action()**  이다

  ```html
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  <script>
  $(document).ready(function(){
      $("p").click(function(){
          $(this).hide();
      });
  });
  </script>
  ```
  
  ```javascript
  $(this).hide() 			// object  : 현재 태그를 숨긴다 
  $("p").hide()			// 태그명    : P 태그를 숨긴다.
  $(".myclass").hide()	// 클래스명   : "myclass" 클래스의 모든 태그를 숨긴다.
  $("#myid").hide()		// id	    : id가 "myid"인 모든 태그를 숨긴다.
  ```
  
- jQuery 기본 프레임
  문서 로딩이 끝나기 전에 jQuery 코드가 실행되는 것을 방지한다.

  ```css
  $(document).ready()(function(){
     // jQuery 코드를 여기에 
  });
  ```

  or

  ```javascript
  $(function(){
  	// jQuery 코드를 여기에
  });
  ```

  or

  ```javascript
  jQuery(document).ready(function(){
  	// jQuery 코드를 여기에
  });
  ```

  or

  ```javascript
  jQuery(function(){
  	// jQuery 코드를 여기에
  });
  ```



## 기본 함수

###### eq(n) : n번째에 위치하는 요소를 선택.

```javascript
// li 요소중 3번째 li의 배경색을 빨간색으로 변경 (0부터 카운트 시작)
$( "li" ).eq(2).css( "background-color", "red" ); 
```

[example]: .\example_eq.md	"example_eq.md"



## next()

next

```javascript
next
```



