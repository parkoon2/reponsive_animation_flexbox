## input:valid (validity pseudo-selector)
 - 보통 input 박스에 많이 사용된다.
 - required 라는 속성이 필요하다.
 - type이 email 이라면 email 규격에 맞아야 해당 CSS가 적용된다.

## pointer-event
 - none
    + HTML 요소에 정의된 click, hover, active 등과 같은 커서이벤트 옵션들이 비활성화
 - auto
    + 비활성화 된 이벤트를 다시 기본 기능을 하도록 되돌린다

## background: transparent
 - input 박스에 한 번 써봐 ^^

## input[type="submit"]
 - [속성=값]

## ~
 - 형제 선택자
    + 지정된 요소 이후의 모든 형제요소에 적용된다.
## +
 - 인접 형제 선택자
    + 지정된 요소 이후로 가장 근접한 형제요소만 적용된다.

## >
 - 자식 선택자
    + 부모의 직계 자식을 모두 선택한다. 단 손자는 제외!