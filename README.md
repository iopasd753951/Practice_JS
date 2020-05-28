# Learning JavaScript 

## jQuery

### BOM
- 브라우저 관련 객체들의 집합 (Browser Object Model)

### DOM
- 문서 객체 (Document Object Model)
- Html문서의 태그들을 JS가 이용할 수 있는 객체로 만든 것.

#### 문서객체생성
- 정적생성 : HTML의 태그를 읽어 생성하는 것.
- 동적생성 : JavaScript로 문서객체를 생성하는 것.

###### ref : https://m.blog.naver.com/magnking/220972680805

### jQuery
- DOM을 좀 더 쉽게 작업하기 위한 라이브러리 

```JavaScript
<!DOCTYPE html>
<html>
  <body>
    <!-- 비어있는 머릿글을 변경 -->
    <h1></h1>
    <!-- 결과: Hello jQuery! -->
    <Script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></Script>
    <Script>
      $("h1").text("Hello jQuery!");
    </Script>
  </body>
</html>
```
- h1 태그를 찾고, 그 사이 텍스트를 바꿈

###### ref : https://www.biew.co.kr/37, https://cloudstudying.kr/lectures/83,https://opentutorials.org/course/53/45