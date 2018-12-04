## 구글 웹 폰트사용하기 (https://fonts.google.com/)
 - 한글 웹폰트가 필요하다면 Language를 Korean으로 설정한다.
 - (+) 버튼을 클릭하여 글꼴을 선택한다.
 - 검은바를 선택한다
 - CUTOMIZE 탭은 선택하고 필요한 것들을 체크한다. (font weight와 load time등을 체크할 수 있다)
 - STANDARD 와 @IMPORT 중 선택한다.
 - 사용한다.

## 이미지를 중앙으로 어떻게..?
 - HINT. cover + center center + no-repeat


## Background 효과

 background-color: red
 background-image: url('~')
 background-repeat: no-repeat / repeat / repeat-x / repeat-y
 background-attachment: fixed (글을 스크롤 되지만 이미지는 스크롤되지 않는다) / 기본값은 scroll
 background-size: 500px 100px / cover (cover-and-contain.jpg 확인) / contain (cover-and-contain.jpg 확인)
 background-position: left top / right top / center center .... 
 
 컬러와 이미지를 같이 사용할 수 있지만, 이미지가 크면 Color가 가려진다.


## gradient
 그래디언트(gradient)란 둘 이상의 색 사이의 색상 표현을 부드럽게 전환해주는 효과를 말한다.
 linear-gradient 와 radial gradient가 있다

 # linear-gradient
  background: linear-gradient(진행방향, 색상지정점1, 색상지정점2, ...);
  기본 진행방향은 위에서 아래이며 top, right, bottom, left 가 있다.

## cursive ?

## transition (전환)
 - 속성들의 값이 변환되었을 때(hover, active...) 부드럽게 전환~
 - 폰트를 10에서 100으로 바꿨을때 딱! 바뀌는거보다 자연스럽게 바뀌는게 좋겠지
 - block이거나 inline block 에서만 동작한다.

 - transition-property: all (누구에게 줄 것인가? 모든 속성에 대해서) / font-size transform (따로따로 써로 된다)
 - transition-duration: 1s (얼마동안? 1초동안)
 - transition: all 0.1s / transiton:font-size 1s, transform 0.1s

 - transition-delay: 1s (1초 후에 전환을 하겠다)
 - transiton-timing-function: ease (기본값) (참고: https://matthewlein.com/tools/ceaser)

## transform (변형)
 - 줄이고 늘리고 회전하고 외곡시키고 이동시킨다
 - 여러개의 변형을 주고 싶다? 한 줄로 써야함. 여러줄로 쓰면 마지막에 쓴 변형이 덮어버림
 - scaleX(0.5)
 - scaleY(0.5)
 - scale(0.5, 0.5)
 - https://codepen.io/vineethtr/pen/XKKEgM 참고
 - 단위 참고 https://developer.mozilla.org/en-US/docs/Web/CSS/transform
 - transform을 검색 잘 해서 프로젝트에 녹여야 겠네



transition / transform 같은 경우 codepen을 참고하면 좋다!
