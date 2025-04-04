# 1주차 스터디 보고서

---

## 1. 태그 종류 및 역할 학습

- title : 윈도우 창의 메인 이름으로, head 태그 안에 적는다. 닫힘 태그가 필요하다.
- html : html을 사용하겠다고 선언하는 태그이다. 사이에는 !DOCTYPE html을 제외한 모든 태그가 포함된다. 닫힘 태그가 필요하다.
- meta charset="UTF-8" : UTF-8 코드를 사용하여 html 내의 언어를 읽는다. 만약 이 태그를 사용하지 않으면, 한글이 모두 깨지게 되어 읽을 수 없게 된다. 닫힘태그는 필요없다.
- h1 ~ h6 : 제목 또는 부제목을 적을 때 사용하는 태그이며, 숫자가 커질수록 글자의 크기가 작아진다. 닫힘태그가 필요하다.
- p, pre : p태그와 pre태그는 모두 텍스트를 적을 때 사용하는 태그이다. p태그는 엔터키를 눌러도 줄바꿈이 적용이 안되지만, pre태그는 엔터키를 누르면 줄바꿈이 적용되어 보인다는 차이가 존재한다. 둘다 닫힘태그가 필요하다.
- hr : 수평선을 그린다. 닫힘태그는 필요없다.
- br : 줄바꿈을 한다. 닫힘태그는 필요없다.
- img : 이미지를 삽입할 때 사용하며, 닫힘태그가 필요하다.
- ol, ul, li : ol은 ordered list로 1, 2, 3, a, b, c와 같이 순서를 정의할 수 있는 리스트이고, ul은 unordered list로 * 점으로 표시되는 리스트이다. li는 리스트의 항목을 적을 때 사용한다.
- a : 하이퍼링크를 삽입할 때 사용하며, 닫힘태그가 필요하다.

- div : 태그들을 묶어 한번에 디자인을 하거나 기능을 사용할 때 사용한다. 닫힘 태그가 필요하다.
- span : 텍스트의 일부를 디자인을 하거나 기능을 사용할 때 사용한다. 닫힘 태그가 필요하다.

- strong, b : 텍스트를 굵게 볼드 처리를 한다. 닫힘 태그가 필요하다.
- ins, del : ins는 밑줄, del은 취소선을 그어준다. 닫힘 태그가 필요하다.
- mark : 형광색 팬으로 하이라이팅하는 효과를 준다. 닫힘태그가 필요하다.


## 2. 태그의 사용법

- img : src 속성에 데스크톱에서의 이미지 파일 경로를 적어준다. alt 속성은 이미지 파일이 보여지지 않을 때 출력할 텍스트를 적어준다.
- ol : type 속성에는 ordered list를 1부터 시작할지, a부터 시작할지, ㄱ부터 시작할지 설정한다. ol type="1" 이면 1, 2, 3, ol type="a"이면 a, b, c, ol type="ㄱ"이면 ㄱ, ㄴ, ㄷ와 같이 출력된다.
- a : href 속성에 웹사이트 링크를 적어준다. 예를 들어, href="www.naver.com"으로 설정하면 네이버 페이지로 이동하게 된다. download 속성은 하이퍼링크를 클릭하면 파일이 다운로드되는 기능을 추가해준다. 
target 속성은 창을 어디에서 열지 정한다. 예를 들어, _self 태그는 현재 창에서 링크를 열게 해주며, 이는 기본값으로 설정되어 있다. _blank로 할 경우 새창에서 연다.

---