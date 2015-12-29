# opentutorialsHTML
생활코딩 HTML 수업

## HTML 기술 소개

HyperText = 하이퍼텍스트를 가장 중요한 특징으로 하는

Markup = 마크업이라는 형식을 가진

Language = 컴퓨터 프로그래밍 

언어의 핵심은 **약속** 사람과 컴퓨터 사이의 약속. 사람과 웹브라우저의 약속.

## HTML 기본 문법

HTML의 특징 = 굉장히 쉽다. 어떤 프로그래밍 언어보다 쉽다. 모든 문법을 배우는데는 20분.

많은 프로그래머들 중에 상당수가 웹으로 프로그래밍을 시작한 사람이 많다. 웹 프로그래밍의 시작은 HTML.

웹 페이지를 만들 예정.

태그를 살펴볼 예정.

strong 태그 -> 굵게 해주기.

meta charset="UTF-8" -> 한글깨짐 현상 때문에 추가..

h1 태그 = 제목으로 처리(H1태그는 굵게 표시하고 줄바꿈을 한다라는 기능)

h2 태그 = 소제목.

핵심은 태그의 이름이 아니고 꺽쇠로 시작해서 꺽쇠 슬래시로 닫히는 태그의 문법이 가장 중요.

태그의 이름은 html 프로그래밍 언어의 사용 설명서를 보면 있음.

## 하이퍼텍스트와 속성

속성만 익히면 HTML 문법은 끝.

링크를 어떻게 표현하는가?

a 태그는 속성이 필요함(href)

target="_blank" 속성 추가시 새로운 탭이 생성되면서 열림.

title="전설적인프로그래머" 속성 등 여러가지 속성을 추가 가능.

a 태그는 매우 중요함..

GML(1960) -> SGML -> SGMLguid -> HTML

## 태그의 중첩과 목록

문법 끝이 거짓말은 아니었는데 약간의 과장이 있었다. ~~이게 뭔 말이야.~~

태그를 중첩해서 사용 하는 방법을 배울 예정이다.

목록으로 웹페이지를 표현하는 방법.

li 태그 = 리스트 (list)

ul 태그로 묶을수 있음(그룹핑) 순서가 없는 리스트 unordered list

ol 태그 = 순서가 있는 리스트 ordered list

## 문서의 구조

가장 큰 틀의 체계들이 있음.

본문 이외의 정보들도 있음.(title, meta charset 등)

HTML은 부가적인 정보와 본문을 각각 다른 태그에 담도록 약속이 되있음. (head태그)

본문 태그는 body태그에 담자. 그래서 HTML은 HEAD태그와 BODY태그로 구성되있음 그리고 HTML태그는 이 두개의 태그를 감싸줌.

## DOCTYPE

지금까지 배웠던 것들에 비하면 그렇게 중요한건 아니지만 좀 어려움.

DOCTYPE = Document type declaration

자신이 작성한 HTML 코드가 어떤 방식의 HTML코드로 작성되있는지 알려주는 문자.

18~20개 사이의 코드가 있었음 (처음에) 지금은 140개 정도가 있음. ~~엄청적다~~

어떠한 태그는 없어지거나 추가되거나 의미가 변경되기도 한다. 그래서 여러분이 어떠한 표준에 따라 작성 했는지 웹브라우저가 알아야 된다.

현 시점에서는 HTML5의 !DOCTYPE html 을 맨 위에 작성하면 된다.

## 웹사이트 만들기

140개의 태그를 다 살펴보기는 쉽지도 않고 의미도 없당. 여러분들이 배운것을 가지고 의미있는걸 해보는게 더 중요하다.

완결된 웹 사이트를 만들기 

총 5개의 파일.

## 개발도구

개발도구는 선택사항입니다.

목록
* atom(추천 확장기능 emmet)
* sublime text(추천 확장기능 emmet)
* bracket
* visual studio code(emmet 내장)

이 수업은 atom 에디터 기반으로 작성됨. 개발도구 안 배워도 됨. ~~하지만 손발이 고생하겠지~~

다중 편집 환경 제공, 검색 등 중요 환경 제공. 개발도구를 사용하는것은 중요하다.

emmet이 엄청 좋다.

## HTML의 변천사와 통계

HTML은 여러가지 태그가 있다.

태그들을 살펴 볼 예정. 살펴 볼 방향성.. 웹이 발전하는 과정에서 태그들이 늘어남.

HTML 연대기 = http://www.martinrinehart.com/frontend-engineering/engineers/html/html-tag-history.html

HTML 통계 = https://developers.google.com/webmasters/state-of-the-web/2005/

태그의 사용 빈도 수에 따라 설명할 예정. 어쩌다 쓰는건 검색해서 사용해라.

## 주요 태그

본 토픽의 하위에서는 주요한 태그들을 살펴봅니다. 오래된 태그나 사용빈도가 높은 태그의 순으로 학습을 합니다. 따라서 모든 수업을 완주할 필요는 없고 하는만큼하면 됩니다. 모르는 태그는 검색을 통해서 알아내시면 됩니다. 

### 단락 - p

paragraph의 줄임말로 단락을 표현할 때 사용합니다.

### 줄바꿈 - br

새로운 행에서부터 입력이 시작되도록 합니다. A forced line-break의 줄임말

등장시기 : html 2

br 태그는 줄바꿈일뿐이고.. 단락을 표현하고 싶으면 p 태그를 사용하자.

### 이미지 - img

문서에 이미지를 포함합니다

등장시기 : html 2

pixabay : 여러가지 이미지를 저작권에 구애하지 않고 사용할수 있는 이미지들을 제공하는 사이트.

alt는 꼭 쓰는게 좋음.

### 표 - table

가장 복잡하고 이해하기 힘든 태그. 그렇다고 이해 못 할 정돈 아님.

만들어볼 예제

이름 | 성별 | 주소
----|-----|-----
최진혁| 남  | 청주
최유빈| 여  | 청주

td로 묶고 tr로 그룹핑 그리고 table로 그룹핑..

테이블을 이쁘게 꾸밀땐 css를 사용한다.

디자인을 할때 레이아웃을 잡을때 과거에 웹페이지 하나를 전체로 표로 잡음. 그래서 html이 너저분해짐.

테이블을 쓰지말고 css로 레이아웃을 만들어라! 그래서 최근에는 테이블을 이용해서 레이아웃을 잡지 않음. ~~하지만 지금도 쓰는 사람이 많음~~

지금 부터는 상관 없는 얘기 (보충) 

시각적으로 차이는 없지만 표의 머리와 분문을 구별할 필요가 있음.. 

thead, tbody, tfoot 등.. 각각의 테이블의 위치를 결정 구조화

표 병합 - 수평과 수직 병합 둘다.

rowspan = 행, 수직 병합

colspan = 열, 수평 병합

### 입력양식 - form

로그인, 글쓰기 등 글을 작성할때 서버로 데이터를 전송할때 사용하는 글자를 입력하는 것들.. 무언가를 선택하는 것들.

사용자가 입력한 정보를 서버로 전송할때 사용하는 것들..

등장시기 = html 2

#### 텍스트 입력

name, value 속성

textarea 등..

#### 선택

DropDown list

#### 버튼

꼼꼼히 보지말고 초반에 나오는 내용만 보고 대충 넘기고 나중에 필요해지면 수업을 듣거나 검색엔진으로 검색.. 그리고 최대한 실습하자.

#### 데이터 전송 - hidden

서버를 데이터를 전송해야될때 ui가 필요 없거나 몰래 전송해야 될때.

#### 컨트롤의 제목 - label

html의 권장방법?? label 사용.. 무언가의 이름표다.. 좀더 명확히.

label for 속성 추가 그리고 해당되는 태그에 id 부여

차이?? 레이블을 클릭해도 해당 태그로 이동됨.

귀찮으면 label 태그로 감싸줄수도 있음..

#### method

form이란것은 사용자가 입력한 정보를 서버로 전송하는 방법.

데이터를 전송하는 몇가지 방법이 있음(지금까지 한것은 get 방식이었음.)

get과 post의 차이를 배울 예정. 다소 서버쪽의 기술을 알고 있어야 제대로 이해 가능.

수박 겉핥기 식 수업일듯. 이해 안가면 넘기면 됨. 

경우에 따라 url로 전송할때가 있고 감춰야 할 때가 있음.

form을 이용해서 데이터를 전송하면 100% post를 사용하면 된다. 그게 아니면 서버에서 원하는 방식으로 전송.

#### 파일 업로드

서버에서 할 일이 훨씬 많아서 수업이 피상적일 수 밖에 없다.

하지만 html쪼에서 어떻게만 해주면 된다는 사실만 알면 서버 개발자와 협업 가능.

이해 가지 않는 부분이 서버쪽이면 마음 편하게 넘어가면 됨.

### 정보로서의 html

처음에는 웹 페이지를 표현할 언어였지만, 웹이 폭발적으로 성장하면서 일류의 많은 정보들이 웹화 됨(html로 표현됨)

그렇게 되므로서 굉장히 중요한 사회적 역할이 됨.. 그렇게 되면서 html이 정보를 담는데 집중하게 되는 여러가지 조치가 시작됨.

html이 정보를 담는 여러가지 초치들은 어떤 것이 있는지 배울 예정.

#### font(퇴출됨)

쓰지 말라고 설명하는 수업. 아직도 많은 곳에서 쓰임.. font 태그는 아무런 의미가 없음.(그냥 시각적인 디자인일 뿐)

그리고 여러번 등장하면 중보되서 실행됨.. html 전체에세 디자인과 정보가 혼합되면서 복잡해짐..

그래서 font를 퇴출시켜버림. 퇴출시키면서 css를 고안해서 그 언어가 디자인을 담당시킴.(html이 정보에 집중하기 위해)

등장시기 html3.2

#### meta

등장시기 html2

어떠한 데이터를 설명하는 태그.

웹페이지의 저자, 어떠한 데이터를 담고있는가?, 키워드? 등 웹페이지를 설명할때 필요.

#### 의미론적 태그

목적

문서의 정보를 보다 잘 표현하기 위해서는 의미에 맞는 태그를 잘 사용해야 합니다. 특히 HTML5에서는 웹페이지에서 통상 많이 사용하는 구조에 의미를 분명히 부여하기 위해서 의미론적 태그(semantic element)를 새롭게 정의해서 제공하고 있습니다. 그 목록은 아래와 같습니다. 

semantic(의미론적인) 굉장히 추상적이고 광범위함. 아무런 기능 변화가 없음

태그     | 내용
--------|----------------------
article | 본문
aside   | 광고와 같이 페이지의 내용과는 관계가 적은 내용들
details | 기본적으로 표시되지 않는 정보들의 정의
figure  | 삽화나 다이어그램과 같은 부가적인 요소를 정의
footer  | 화면의 하단에 위치하는 사이트나 문서의 전체적인 정보를 정의
header  | 화면의 상단에 위치하는 사이트나 문서의 전체적인 정보를 정의
main    | 문서에서 가장 중심이 되는 컨텐츠를 정의
mark    | 참조나 하이라이트 표시를 필요로 하는 문자를 정의
nav     | 문서의 네비게이션 항목을 정의
section | 문서의 구획들을 정의
time    | 시간을 장의 

등장시기 html 5

#### 검색엔진 최적화

구글검섹엔진 최적화 가이드 : http://static.googleusercontent.com/media/www.google.com/ko//intl/ko/webmasters/docs/search-engine-optimization-starter-guide-ko.pdf

검색엔진들이 여러분의 컨텐츠를 잘 해석하고, 상위에 노출할수 있도록.. 그런 노력들.

검색엔진에 최적화 하려면 무엇을 해야되나? 결론적으로는 의미론적으로 html 작성.

검색엔진 최적화를 한다고 해서 너무 검색엔진에 좋게 해면 검색엔진에서 스팸으로 분류 해 버릴 수 있으니 적당히..

구글이 검색엔진에서 글로벌 스텐다드 같은 역할을 함. 메뉴얼을 읽어나가면서 실습및 해석.

SEO = 서치 엔진 옵티마이제이션.(검색엔진최적화)

검색엔진들이 우리의 사이트에 html 코드를 가져가서 분석할거임.

title태그 생활코딩 사이트와 li태그 생활코딩의 사이트가 있을때. title 태그를 사용한 웹사이트를 먼저 노출함.

title 태그 사용시 검색엔진의 제목에 노출될수있으므로 상당히 중요함.

meta 태그를 사용하는 것이 좋다. meta태그의 descript은 짧은 단락을 사용하는게 좋음.

url 구조 개선 url의 구조를 알아보기 쉽게 만들면 좋음.

사이트 내에서 이동하기 쉽게 만들기. (링크를 통해 우리의 웹페이지를 긁어가기 때문에..)

사이트 이동경로를 제공하여 방문자에게 편리를 제공하기. 사용자가 url의 일부를 제거하는 경우 발생할 상황을 고려.. 사이트맵을 제공한다.

우수한 품질의 콘텐츠와 서비스 제공. 검색 엔진을 위한 것이 아닌 사용자를 위한 콘텐츠 작성.

보다 나음 앵커 텍스트 작성(링크)

이미지 사용 최적화 alt를 사용해라.(대안텍스트) 스크린 리더와 같은 다른 기기를 사용하는 경우

구글 이미지 검색이 alt를 기반으로 보여줄 수 있다. 이미지를 단일 디렉토리에 통합하는 것 을고려(images 같은 디렉토리)

제목 태그의 적절한 활용 아주 중요함. 

robots.txt를 효과적으로 활용하기. 나의 웹사이트에 크롤링하기 들어온 수많은 것들에게 접근을 허용할수도있고 안할수도있음.

www.naver.com/robots.txt 라고 하면 해당 사이트의 로봇 txt를 다운받을수있음 네이버는 모든 것들의 접근을 허용하지 않음.. (다른 검색엔진에서 검색할 수 없음) ~~해석은 알아서 맡기겠다.~~

구글은 allow같은 것들이 많음.. ~~역시 착한 구글~~

페이지 랭크. 아... 많은 사이트들이 내 사이트를 가리키면 페이지 랭크를 높여줌.. ~~역시 인맥이 중요하네..~~

웹의 본질은 링크에 있다. 야후가 굉장히 잘나갔는데 굉장히 큰 실수를 함.(검색엔진에 투자를 중단하고 구글에 검색엔진 아웃소싱함)

구글이 성장한 이유는 웹의 본질인 링크로 돌아가서 본질을 응시해서 좋은 기회를 얻었음

html에 소홀히 질 수 있지만, 중요함. 웹을 하는 이상 html을 떠날 수 없음.

웹이 정보로서 굉장히 중요하다.

### 웹개발자 도구

크롬 웹 브라우저에 탑재되있는 개발자 도구를 알아볼 예정.

크롬 개발자 도구 수업 바로가기 : https://opentutorials.org/module/306/2865

오른쪽 버튼 검사를 누르면 그 해당 되는 부분의 태그를 보여줌.

페이지 소스 보기를 누르면 html 코드를 볼 수 있음. 웹 개발자 도구를 사용하면 html을 볼 수 있을 뿐만 아니라.

왜 이런 모양으로 생겼는지 알아내기 쉽다.(css도 나오니..)

Toggle Device Mode 클릭시 여러가지 디바이스를 대응 하기 쉬움.(다양한 화면 크기를 시뮬레이션 해줌)

Network 는 웹 브라우저와 웹서버가 주고 받는 여러가지 데이터를 체크..

### 모바일 지원

타블렛이나 스마트폰에서도 잘 나오게..