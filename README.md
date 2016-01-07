# Exchat
A simple and fast exchange information application "Exchat"

# File information
* PSD : .psd 파일이 포함되어 있습니다.
* resource-xxxhdpi : <strong>XXXHDPI</strong>해상도의 리소스가 포함되어 있습니다.
* screenshots : 디자인 스크린샷이 포함되어 있습니다.
* icons : 아이콘이 각 해상도와 용도로 리사이징되어 들어있습니다.

# Resource information
<strong> 아이콘 크기는 XXXHDPI 기준이니 주의할것 >_<// </strong>

* `ic_main_calculator_to.png` - 메인 계산기 아랫부분의 > 아이콘.
* `ic_main_mainexchange_to.png` - 메인 메인환율 부분의 > 아이콘.
* `title_nav.png` - 네비게이션 드로워의 한글 타이틀. <s>텍스트로 구현되면 빼도 됨</s>
* `title_fastsearch.png` - 빠른검색(Fastsearch) 위젯 타이틀.
* `title_about_app.png` - About창 타이틀부분 앱 로고.
* `title_about_team.png` - About창 타이틀부분 앱 로고 아래의 팀 로고.
* `btn_tutorial_back.png` - 튜토리얼부분 뒤로가기 버튼.
* `title_tutorial_slide1.png` - 튜토리얼 슬라이드 1부분 로고.
* `title_tutorial_slide2_frame.png` - 튜토리얼 슬라이드 2 스크린샷과 기기 프레임.
* `title_tutorial_slide3_frame.png` - 튜토리얼 슬라이드 3 스크린샷과 기기 프레임.
* `ic_tutorial_slide4_spinner.png` - 튜토리얼 슬라이드 4 주요 환율 부분 스피너 아이콘.

# Color information

* `#455A64` - Bluegray 700 / 메인컬러
* `#263238` - Bluegray 900 / 스테이터스 바 컬러
* `#37474F` - Bluegray 800 / 서브컬러
* `#FF8A65` - 숫자 중 주황 부분
* `#00BFA5` - Teal A700 / 숫자 중 초록 부분
* `#757575` - Gray 600 / 글씨색

# App Storyboard

* 쉽고 빠르게 환전 정보를 알려주는것을 목표로 하는 어플리케이션입니다. <br>
* 앱 메인에서는 자신이 설정한 주요 환율과 함께 계산기가 존재하고 그 아래로 '빠른 검색(Fastsearch)'에서 검색했던 환율 정보 히스토리를 표시합니다. (스크롤 가능)
* 네비게이션 드로워에서는 주요 환율을 재설정하거나, 히스토리 삭제, 빠른검색 비활성화 / 활성화를 할 수 있습니다.
* 빠른 검색에서는 클립보드에 복사한 해외금액을 알아와 바로 대한민국 원으로 얼마인지 위젯으로 보여줍니다. 위젯에서 바로 공유하거나 앱을 열 수 있습니다.
* 공유를 했을 때 아래와 같은 형식의 메세지로 공유됩니다.
~~~
오늘 일본환율은 100 JPY = 1,020.58 KRW 입니다. #Exchat.
~~~
* 튜토리얼은 간단한 소개와 주요 환율 설정만 합니다.
