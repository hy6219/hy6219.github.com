# Overview
## HTML과 CSS, Javascript

1.  HTML?
2.  CSS?
3.  JavaScript?

----------

1.  HTML?

-   Hyper Text Markup Language


-   페이지에 제목, 문단, 표, 이미지, 동영상 등을 정의 && 그 **구조**의 의미를 부여하는 **정적 언어**→**튼튼한 구조(semantic)을 만드는 것에 집중!** 💓

2.  CSS?

-   Cascading Style Sheets


-   **마크업언어(HTML, XML 등)가 실제 표시되는 방법(색상, 크기, 폰트, 레이아웃 등)을 지정**하여 **콘텐츠 구조를 꾸며주는 정적 언어** →웹의 시각적 표현을 담당💓

3.  Javascript?

-   페이지를 동적으로 꾸며주는 역할(웹의 동적 처리 담당)
-   예 : 콘텐츠를 바꾸고 움직이기

## 웹 표준과 크로스 브라우징, 웹 접근성

1.  웹 표준?
2.  크로스 브라우징?
3.  웹 접근성?

----------

1.  웹 표준?

-   **W3C 권고안(REC)에서 나온 기술**들이 해당되는, **"웹에서 사용되는 표준 기술이나 규칙"**
    
    2.  크로스 브라우징?
-   **여러 브라우저**에서 **동일한 사용자 경험**(같은 화면, 같은 동작 등)을 줄 수 있도록 제공하는 기술
    
-   브라우저 종류 : 크롬(구글), 엣지(MS), 파이어폭스( 모질라), 오페라, 스윙(이스트 소프트), 웨일(네이버), IE(Internet Explorere)(MS), 사파리(애플)
    

**-IE 브라우저, 웹 표준에 맞추어지지 않아서, 표준화하기 쉽지 않음**

3.  웹 접근성

웹의 힘은 그것의 보편성에 있다. 장애에 구애없이 모든 사람이 접근할 수 있는 것이 필수적인 요소이다 ((팀 버너스 리 경(웹의 창시자)))

-   누구나 쉽게 웹 서비스를 이용할 수 있도록 하는 것
-   정보통신보조기기 : 한손 사용자용 키보드, 큰키 키보드, n-Abler 조이스틱, SmartNav, 소리 알리미
-   웹 접근성 품질인증 마크 : 장애인 및 고령자가 웹사이트 이용에 불편이 없도록 웹 접근성 표준을 준수한 우수 사이트에 품질을 인증하고 마크를 부여하는 제도 : 과학기술정보통신부에서 지정한 웹 접근성 품질인증 기관을 통한 심사 및 인증을 받을 수 있음

## 웹에서 사용하는 이미지

1.  비트맵 이미지

-   각 픽셀이 모여 만들어진 정보의 집합 ("레스터(Raster) 이미지")
-   픽셀 단위로 화면에 렌더링(컴퓨터가 화면에 그림을 그려서 우리가 볼 수 있게 하는 것)
-   이미지 확대/축소에 따른 용량변화 발생 → 장점
-   일반적으로 사용하는 대부분의 이미지 형식이 해당됨 ex) jpg, png, webp(구글에서 만들어진것)

가. JPG(JPEG); Joint Photograhic coding Experts Group

-   압축률 훌륭(적은 용량)->사진 or 예술분야에서 사용됨
-   특징


a. 손실 압축 

b. 표현 색상도(24비트, 약 1600만 색상)이 뛰어나고해상도 표시장치에 적합 


c. 이미지 품질과 용량을 쉽게 조절 가능 


d. 가장 널리 쓰이는 이미지 포맷

나. PNG;Portable Network Graphics

-   **gif의 대체포맷**으로 개발되었음
-   특징 
    
    a. **비손실 압축**(→이미지를 해상도를 손실시키지 않으면서 저장되고, 용량이 큼)
    
    b. 8비트(256 비트)/24비트(약 1600만 색상) 동시 사용 가능 
    
    c. **투명도 지원**(Alpha channel) 
    
    d. W3C 권장 포맷

다. GIF; Graphics Interchange Format

-   **동영상 같은 이미지!(애니메이션)**
-   이미지 파일 내에 이미지 및 문자열 같은 정보들을 저장할 수 있음 ↔여러장의 이미지라던지, 문자열을 넣을 수 있음 ↔"움짤"
-   특징 
    a. 비손실 압축 
    
    b. 8비트 컬러만 지원(→따라서, 다양한 색상을 표현하는 작업에는 적합하지 않음)

라. WEBP(Webp)

-   JPG, PNG, GIF를 모두 대체할 수 있는 구글이 개발한 이미지 포맷
-   특징 

    a. 완벽한 손실/비손실 압축 지원 
    
    b. GIF와 같은 애니메이션 지원 
    
    c. Alpha Channel 지원(손실, 비손실 모두) 
    
    d. 완벽한 포맷! 그러나 지원되는 브라우저가 많지 않음
2. 벡터 이미지

-   **수학적 정보의 형태(Shape)**들이 만들어내는 결과물

-   이미지가 갖고 있는 점,선,면의 위치(좌표), 색상 등의 정보를 온전히 가짐 && 이를 화면에 렌더링

-   (vs 비트맵) 해상도로부터 자유롭게 렌더링 가능

-   확대 및 축소 시 이미지가 깨지지 않음

-   이미지 확대/축소에 따른 용량변화 x →단점이 될 수 있음

-   일러스트 같은 툴로 편집 가능

가. SVG; Scalable Vector Graphics

-   **마크업언어(HTML, XML 등) 기반의 벡터 그래픽을 표현**하는 포맷
-   [SVG 종류] 

a. **코드**로 되어 있는 경우 

b. **파일**로 되어 있는 경우

-   특징 

   a. 해상도 영향에서 자유로움 


   b. CSS로 Styling 가능 


   c. JS로 Event Handling 가능

-   작성이 어렵기 때문에 일러스트 툴로 만들어야 좋음

# [HTML]특수기호는 엔티티로!

[특수기호는 엔티티로 이용해보자!](https://www.freeformatter.com/html-entities.html)

**특수기호**를 문자로 직접 입력하게 되는 것이 잘 표시되지 않을 수 있기 때문에 엔티티를 이용하는것이 보다 뚜렷할 수 있음