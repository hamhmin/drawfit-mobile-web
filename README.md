# drawfit-mobile-web
-----------------

drawfit 모바일웹을 제작했습니다.

사이트 링크 : https://hamhmin.github.io/drawfit-mobile-web/

-----------------


## 기능 구현

-----------------
**메인프레임**

* 헤더, 푸터, 토글메뉴창이 모든 페이지마다 실행되도록 함
```c
 - 헤더 안에 검색창을 등장시키는 버튼, 검색창등장 애니메이션 추가, 토글 메뉴버튼을 넣었습니다.
 - 진행중인 이벤트, 공지를 알리는 팝업을 제작하였습니다.
 - scroll-snap 을 이용하여 js사용을 줄이며 유연한 스크롤 기능을 보여줍니다.
```

------------------
**메인페이지**
넘어가기 버튼, 현재페이지를 알리는 변하는 아이콘


수정해야함ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ
------------------
**제품 페이지**

* 제품의 정보는 JSON파일로 정리하였으며 fetch 코드로 불러내어 html형식에 맞게 출력되도록 작성하였습니다.
* 카테고리 필터 버튼 클릭시 2x2, 한줄 로 전환됩니다!
* 제품 페이지 카테고리메뉴(소세지 메뉴)를 클릭하면 카테고리별로 분류가 됩니다.
* 제품 클릭시 상세페이지로 이동됩니다.

------------------
## 상세 페이지

* 상세페이지 상단에는 제품 정보가 기입되어 있고
이미지 슬라이더(swiper)를 삽입하여 사용자가 직접 넘겨서 다음이미지를 볼 수 있게끔 설정해놨습니다.
* radio버튼으로 색상을 선택할 수 있고 수량버튼을 추가하여 플러스버튼과 마이너스버튼으로 수량을 선택할 수 있게 만들었습니다.(Javascript 사용)


## 사용 툴
|JavaScript|HTML5|CSS|


## 사용 라이브러리
bootstrap, jquery