# min-height vs height 비교 및 활용.
 height를 500px로 지정해 놓고 height 200px 박스를 10 넣는다면 어떻게 될까?

 똑같이, min-height를 500px로 지정해 놓고 하면?

 첫번째 경우, overflow가 default (visible)로 세팅되어 있다면 200px 박스는 부모를 넘어갈 것이다.
 두번째 경우, 부모박스가 알아서 늘어난다.

# transform의 translate에 대하여...




# absoulte랑 top left right bottom을 한번에 사용한다?
Bonus Tip: Sizing Without Width or Height
Here’s a bonus tip that probably not a lot of people know about. You can actually define the dimensions of any absolutely positioned element using the top, left, bottom, and right values alone, without any content in the element and without width or height values.

.box {
  position: relative;
  width: 400px;
  height: 400px;
}

.inner-box {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
}

This will cause the inner element to fill the outer element’s content area. Here’s a JSBin with some exaggerated borders, so you can see how this works:


#position 한번 더 공부하기.
static
 - 기본이 static이면 왼쪽에서 오른쪽으로 쌓인다.
relative
 - 기본 위치에서 이동을 합시다. 기본 위치란,  static으로 했으면 어디에 있을까? 라고 생각하면 된다.
absolute
 - 얘는 기본위치가 아니어라 조상요소를 기준으로 움직인다.
fixed
 - 기본위치 + 이동가능 + 스크롤 되어도 그 자리에~