# 오늘의 메뉴

Rust언어로 변경하였습니다.

템플릿 폴더에 프론트 쪽 코드 업데이트하면서

서버 연동하면서 프론트도 바꾸는 중입니다.

프론트는 Tera 템플릿 엔진 써서 코드 연동해도 됩니다.

# 시현

## 로그인 -> 추천 -> 리뷰 작성 -> 리뷰 보기 -> 주문 -> 끝

회원가입 했다고 가정하에 첫 로그인 따라서 음식 선호도 페이지로 넘어감

선호도 대충 정하고 추천 메뉴 페이지로 넘어검 (알고리즘 돌린 척 랜덤 5개 띄웁니다)

DB 연동도 시간 없어서 앱 내부에서 DB 처럼 하지만 재 실행할 때마다 정보 초기화 됩니다.

연동 했다치고 보고서 쓰시면 되고, 추천 메뉴 페이지에서 주문으로 가던가 `관심 없음` 눌러서 일반 메뉴판 페이지로 넘어갑니다.

주문하기 눌렀을 때 학식처럼 번호 보여주고 식당에서 조리를 시작하면 알림이 뜨고 (약 3~4초 후 그냥 알림으로 뜨는 방식으로 시현)

식당에서 번호를 불러 스크린에 나오면 알람 띄어주는 방식이면 좋을 것 같습니다.
