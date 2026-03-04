# 그린컴퓨터아카데미 파이널프로젝트: 온라인 화장품 쇼핑몰 (Frontend)

Spring Boot + React 기반 풀스택 쇼핑몰 프로젝트의 프론트엔드입니다.
백엔드 저장소: [링크](https://github.com/ShinSora91/green-final-shoppingmall-server)

---

## 기술 스택

- **Frontend:** React, JavaScript, Tailwind CSS, Vite
- **통신:** Axios
- **상태 관리:** React useState, useSearchParams

---

## 담당 기능

**리뷰 시스템**
- 텍스트 + 이미지 복합 데이터를 FormData로 가공하여 API 전송
- 이미지 등록 전 FileReader API로 미리보기 제공
- 수정 시 기존 이미지 유지 / 새 이미지 추가 / 삭제 대상을 상태로 분리 관리
- 리뷰 삭제 후 전체 목록 재조회 없이 해당 항목만 상태 업데이트로 즉시 반영

**검색 기능**
- 최근 검색어 / 인기 검색어 UI 구현
- 비로그인 사용자도 쿠키 기반으로 개인 검색 기록 표시 및 삭제 가능

**관리자 페이지**
- 이름, 등급, 가입일, 수신 동의 여부 등 다중 필터 조합 검색 UI 구현
- 회원 권한 실시간 변경 기능

**공통**
- Pageable 연동 페이지네이션 컴포넌트 구현
- 로그인 여부 및 본인 리뷰 여부에 따라 좋아요 버튼 활성화 상태 제어
