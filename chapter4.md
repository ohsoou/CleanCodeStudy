
# 주석

### 주석은 나쁜 코드를 보완하지 못함, 코드로 의도를 표현

불필요하거나 업데이트가 안된 주석은 보기 나쁘고, 오히려 코드를 더 이해하기 어렵게 한다.

주석을 쓰지 않고, 대부분 코드로 의도를 표현할 수 있다.

### 좋은 주석

가장 좋은 주석은 주석을 달지 않을 방법을 찾아낸 주석이다.

- 법적인 주석

회사의 구현 표준에 맞춰 저작권 정보다 소유권 정보를 주석화

모든 사항을 열거하는 대신 표준 라이선스나 외부 문서 참조가 더 바람직하다.

- 정보를 제공하는 주석

반환값, 정규식 설명같은 기본적인 정보를 주는 주석

함수 이름을 수정하거나 클래스를 만들어 코드를 옮기면 더 깔끔하고 주석이 필요 없어진다.

- 의도를 설명하는 주석

구현 이해를 도와주는 선을 넘어 코드를 짠 의도까지 설명한다.

- 의미를 명료하게 밝히는 주석

모호한 인수나 바환값을 읽기 좋게 표현하는 것

잘못된 주석을 쓰기 쉬워진다. 위험이 높은 주석이니 충분히 고민 후 다는 것이 좋다.

- 결과를 경고하는 주석

실행이 오래걸리거나 안전하지 못할 때 미리 경고해준다.

테스트에 도움을 줌

- TODO 주석
앞으로 할 일을 남겨둔다.

그러나 나쁜 코드를 남겨놓는 핑계가 되어서는 안된다.

- 중요성을 강조하는 주석

- 공개 API에서 Javadocs

### 나쁜 주석

대다수에 주석이 이 범주에 속한다.

- 주절거리는 주석

의무감으로 정보를 주지도 않고 당연한 이야기를 하는 주석

- 같은 이야기를 반복하는 주석
- 있으나 마나 한 주석

코드에서 알 수 있는 당연한 내용을 다시 반복하는 주석

너무 당연한 사실을 기록해 새로운 정보를 주지 않음 (a.k.a 중복 주석)

- 오해할 여지가 있는 주석

정확한 정보를 담지 않고 '살짝 잘못된 정보'를 담은 주석

- 의무로 다는 주석
- 무서운 잡음

모든 함수에 Javadocs를 넣으라는 규칙같은 필요없는 규칙으로 인해 의무적으로 다는 주석

- 이력을 이록하는 주석
- 공로를 돌리는 주석

변경 이력을 주석화

소스 코드 관리 시스템을 이용한다.

- 함수나 변수로 표현할 수 있다면 주석을 달지 마라

<br>

- 위치를 표시하는 주석

```
//Actions/////////////////////////////////
```
위와 같이 위치를 표시하는 주석, 베너를 사용하는 것은 반드시 필요할 때만 사용

- 닫는 괄호에 다는 주석

차라리 함수를 줄여 이해하기 쉽게 만든다.

- 주석으로 처리한 코드
<br>

- HTML 주석

도구로 주석을 뽑아 웹페이지에 올릴 것이라면 HTML 태그를 주석에 삽입해야 하는 책임은 도구가 져야한다.

- 전역 정보

주석을 달아야 한다면 근처에 있는 코드만 기술

코드 일부에 주석을 달면서 시스템의 전반적인 정보를 기술하지 말라

- 너무 많은 정보
- 모호한 관계
<br>

- 함수 헤더

짧고 한가지만 수행하며 이름을 잘 붙인 함수가 주석으로 헤더를 추가한 함수보다 훨씬 좋다.

- 비공개 코드에서 Javadocs

공개하지 않으려면 굳이 Javadocs를 쓸 필요 없다.
