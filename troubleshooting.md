## 문제

navbar의 위치를 float: right를 써서 오른쪽 끝으로 옮겨놓았는데,

main요소들에 margin-top을 적용하자 float: right가 함께 딸려 내려왔다.

왜? 일까?

## 해결방안

flex요소들을 아무리 써보아도 해결이 되지 않아, 개발자도구가 생각났다.

개발자도구에서, body를 선택해서 미리 속성을 구현해보는 방법이 있는데

display: contents를 적용하니 navbar만 상단 우측에 배치됐다.

## display: contents란 ?
