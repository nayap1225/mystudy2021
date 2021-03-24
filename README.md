# memo

### scss

``` 
** node-sass 설치 **
npm install -g node-sass **or** sudo npm intsall --unsafe-perm -g node-sass   
```
```
** 파일경로 & 컴파일 저장경로 설정 **
npm node-sass [옵션] <입력파일경로> [출력파일경로] ==> npm scss/style.scss css/style.css
option : --watch or -w : 런타임 중 파일을 감시하여 자동으로 변경사항을 컴파일
```
|  데이터  |  설명  |  예시  |
|:------:|:------|:------|
|  __Numbers__  |  숫자  |  1, .82, 20px, 2em…  |
|  __Strings__  |  문자  |  bold, relative, "/images/a.png", "dotum"  |
|  __Colors__  |  색상 표현  |  red, blue, #FFFF00, rgba(255,0,0,.5)  |
|  __Booleans__  |  논리  |  true, false  |
|  __Nulls__  |  아무것도 없음  |  null  |
|  __Lists__  |  공백이나 ,로 구분된 값의 목록  |  (apple, orange, banana), apple orange  |
|  __Maps__  |  ists와 유사하나 값이 Key: Value 형태  |  L	(apple: a, orange: o, banana: b)  |

```
--output-style             CSS output style (nested | expanded | compact | compressed)
node-sass --watch assets/scss/style.scss assets/css/style.css --output-style expanded
--> 명령어 취소 : ctrl + c
```

```
Libsass나 node-sass는 현재 유지 관리는 되고 있으나 폐지되었으므로 Dart Sass를 사용하도록 하자.
```
