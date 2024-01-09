
# HTML 요소(Element)의 구조
![image](https://github.com/zzola1453/zzola1453github.io/assets/71739885/2bfb65df-fe0b-4522-b869-fcd91c2261a6)
* 여는 태그(Opening tag): 이것은 요소의 이름과(이 경우 p), 열고 닫는 꺽쇠 괄호로 구성됨. 요소가 시작(이 경우 단락의 시작 부분)부터 효과가 적용되기 시작한다.
* 닫는 태그(Closing tag): 이것은 요소의 이름 앞에 슬래시(/)가 있는것을 제외하면 여는 태그(opening tag)와 같다. 이것은 요소의 끝(이 경우 단락의 끝 부분)에 위치한다. 닫는 태그를 적어주지 않는 것은 흔한 초심자의 오류이며, 이것은 이상한 결과를 낳게됨.
* 내용(Content): 요소의 내용이며, 이 경우 단순한 텍스트이다.
* 요소(Element): 여는 태그, 닫는 태그, 내용을 통틀어 요소(element)라고한다.

ex)
<em>This is my text</em> : em 태그
## 포함된 요소
ex)
gang is <strong>dangerous</strong> : strong 태그
## 블럭 레벨 요소 : 각 요소들이 새로운 줄에 나타난다.
ex) em 태그
<em>hood</em>
<em>gang</em>
<em>gun</em>
## 인라인 요소 : 각 요소들이 서로 같은 줄에 나타난다.
ex) p 태그
<p>Bob</p>
<p>John</p>
<p>Kim</p>

## 빈 요소 : 단일 태그를 사용하는 요소
ex) img 태그
<img
  src="https://www.choicenews.co.kr/news/photo/202308/119206_84696_3036.jpg" />

# 속성(Attributes)
* 실제로 나타내고 싶지 않지만 추가적인 내용을 담고 싶을 때 사용한다.
1. 요소 이름 다음에 바로 오는 속성은 요소 이름과 속성 사이에 공백이 있어야 되고, 하나 이상의 속성들이 있는 경우엔 속성 사이에 공백이 있어야 합니다.
2. 속성 이름 다음엔 등호(=)가 붙습니다.
3. 속성 값은 열고 닫는 따옴표로 감싸야 합니다.

ex) href 태그
href="https://github.com/zzola1453/"

<<a href="https://www.youtube.com/watch?v=4cshHDL0m34/" target="_blank">마인크래프트 엔더드래곤 스피드런 영상</a>
