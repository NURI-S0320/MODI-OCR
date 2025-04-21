문서 관리 시스템
브랜드 인보이스와 발주서를 관리하고 비교하는 웹 기반 시스템입니다.
기술 스택
백엔드

Flask: RESTful API 서버
SQLite: 문서 및 비교 데이터 저장
Google Vision Cloud API: OCR 텍스트 추출
PDF2Image: PDF 변환

프론트엔드

HTML/CSS: 반응형 대시보드 구현
JavaScript: 동적 UI 상호작용
Chart.js: 데이터 시각화
FontAwesome: UI 아이콘

주요 기능

문서 OCR 처리: 인보이스와 발주서 PDF에서 데이터 추출
문서 자동 비교: 발주서와 인보이스 간 데이터 일치율 분석
대시보드 분석: 일치율 추이, 브랜드별 주문 금액 시각화
캘린더 연동: 선적 일정 자동 등록 및 관리
데이터 내보내기: 분석 결과 엑셀 추출

설치 및 실행
bash# 저장소 복제
git clone https://github.com/username/document-management-system.git

# 종속성 설치
pip install -r requirements.txt

# 서버 실행
python run.py
화면 구성

대시보드: 주요 지표 및 차트 시각화
발주 및 계약 관리: 문서 관리 및 비교
보고서: 브랜드 및 품목별 데이터 분석
업로드: 새 문서 OCR 처리
캘린더: 선적 일정 관리
