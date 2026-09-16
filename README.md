# QR_System

TIG KOREA 기술1팀 **납품 장비 이력 관리 시범 웹**입니다.

## 바로가기
- **관리자/내부 시범 화면**: https://wantoscar.github.io/QR_System/
- **장비별 공개 QR 인쇄 화면**: https://wantoscar.github.io/QR_System/qr-public.html
- **공개 장비 예시(EQ-009)**: https://wantoscar.github.io/QR_System/public.html?id=EQ-009

## 화면 구조
`고객사/업체 → 지사/관리그룹 → 현장 → 장비 → 장비 상세`

장비 상세 화면에서는 다음 내용을 확인할 수 있습니다.
- 장비 기본 정보
- 고객사/관리 정보
- 납품 장비 이력
- 장비/현장 사진 영역
- 제조사·모델별 자가진단/간단조치 가이드
- **장비 전용 QR**
  - 휴대폰 화면 열기
  - QR 저장
  - 전용 링크 복사
  - QR 인쇄

## 장비별 공개 QR
각 장비 QR은 해당 장비 한 대의 공개 화면으로만 연결됩니다.

예시:
`https://wantoscar.github.io/QR_System/public.html?id=EQ-009`

## 시범안 안내
현재는 GitHub Pages 기반 정적 시범 사이트입니다. 실제 운영 단계에서는 서버 기반 로그인, 고객사별 권한 제어, DB 분리 후 기존 통합관리시스템과의 연동을 개발팀과 협의하는 방향을 전제로 합니다.
