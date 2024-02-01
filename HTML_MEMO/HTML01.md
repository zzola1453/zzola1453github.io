<h1>HTML 시작</h1>

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
'''html
 <em> 내용 </em> 
''' 
  
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

'''html
<img src="사진" />
'''

<img
  src="https://www.choicenews.co.kr/news/photo/202308/119206_84696_3036.jpg" />

# 속성(Attributes)
![image](https://github.com/zzola1453/zzola1453github.io/assets/71739885/62c07670-6f31-480c-85ea-ff293069ccc1)
* 실제로 나타내고 싶지 않지만 추가적인 내용을 담고 싶을 때 사용한다.
1. 요소 이름 다음에 바로 오는 속성은 요소 이름과 속성 사이에 공백이 있어야 되고, 하나 이상의 속성들이 있는 경우엔 속성 사이에 공백이 있어야 함.
2. 속성 이름 다음엔 등호(=)가 붙는다.
3. 속성 값은 열고 닫는 따옴표로 감싸야 함.

ex) href 태그
href="https://github.com/zzola1453/"

<a href="https://www.youtube.com/watch?v=4cshHDL0m34/" target="_blank">마인크래프트 엔더드래곤 스피드런 영상</a>

## 참과 거짓 속성
ex) disabled
<input type="text" disabled />
<input type="text" />

# HTML 문서의 구조
![캡처](https://github.com/zzola1453/zzola1453github.io/assets/71739885/67adfe54-0470-4459-b555-6416f62fa2d2)

1. !DOCTYPE html : 과거에는 유용하게 사용했지만 지금은 그냥 모든 것이 제대로 작동하기 위해 필요함
2. html,/html : html의 요소, 전체 페이지의 콘텐츠를 포함하고 기본요소로 알려져 있음
3. haed, /head : head의 요소, 검색결과에 노출될 키워드, css스타일, 홈페이지 설명 등 HTML 페이지에 대한 모든 내용을 담음
4. meta charset="utf-8" : 이 설정을 사용하면 페이지에 포함된 모든 텍스트 내용을 처리할 수 있음
5. title, /title : title의 요소, 페이지의 제목이 설정되며 브라우저 탭에 표시되는 제목으로 사용한다.
6. body, body : body의 요소, 텍스트, 이미지, 비디오, 게임, 재생 가능한 오디오 트랙 등을 비롯하여 페이지에 표시되는 모든 콘텐츠 포함

## HTML 공백
ex) 이거 둘 다 똑같더라
<p>Dogs are silly.</p>

<p>Dogs        are
         silly.</p>

# HTML 주석
아래에 글 있는데 주석이라 안보입니다.
<!-- <p>gang is dangerous!</p> -->

적은 내용
'''html
<!-- <p>gang is dangerous!</p> -->
'''


         


