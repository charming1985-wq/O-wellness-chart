# PAVING 웰니스 체크 — GitHub Pages 빌드 (v4.4)

- 로그인 화면에서 결과/진행 UI 강제 비표시 가드 강화
- `navTo(view)`에서 현재 view를 body dataset으로 노출
- 초기 로드 시 dataset을 'login'으로 세팅
- 푸터에 버전 표식 표시

빌드 생성: 2025-09-11


## v4.4.4 (2025-09-12, Asia/Seoul)
- '측정' 기본 화면에서 통계 대시보드(추이/최신카테고리/통계/히스토리/스파크라인)를 제거
- 네비게이션 '통계' 버튼 선택 시에만 #progressSection이 표시되도록 구조 변경
- `navTo('measurement')`에서 `infoSection` 표시 호출 제거
- 마크업 변경 없이 기존 ID 유지 (차트/히스토리/스파크라인 기능 기존 JS 그대로 동작)


## v4.4.5 (Goal/Memo + BMI/Zone visuals)
- 새 '목표/메모' 전용 큰 textarea 추가 (기본/신체 정보 아래)
- 기존 회원 선택 시, 가장 최근 기록의 메모 자동 로드(빈 칸일 때만)
- BMI 바 시각화 및 Zone1/2/3 (HRR 기반) 범위 표시
- 저장 시 goalMemo 우선 저장 (goalNote 하위 호환)
