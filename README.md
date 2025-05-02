# 📌 가계부 서비스 앱 : 커비의 가계부

Vue.js 기반의 가계부 서비스 웹 앱입니다.  
수입/지출 기록부터 분석 차트 시각화까지 제공하며, 반응형 UI와 REST API 기반 CRUD 기능을 지원합니다.

---

## 🏗️ 프로젝트 개요

- **주제**: 개인의 수입·지출 내역 관리와 분석
- **팀원**
  - 송용욱: 분석 페이지 (원형/막대 차트, 합산)
  - 이규리: 404 페이지, 로고 제작
  - 이승예: 회원가입, 로그인, 마이페이지
  - 전영태: 메인 페이지
  - **정혜빈: 수입/지출 작성, 수정, 삭제 페이지**
  - 최창연: 필터링, 조회 기능

---

## 🚀 기술 스택

- **Frontend**: Vue.js, Vite, Pinia, Vue Router, Tailwind CSS
- **데이터 처리**: json-server
- **API 통신**: REST API
- **협업**: GitHub, Notion

---

## 📂 프로젝트 구조

```bash
TeamProject/
├── public/
│   └── img/             
├── src/
│   ├── api/  
│   ├── assets/
│   ├── components/
│   │   ├── common/
│   │   ├── charts/
│   │   └── sums/
│   ├── views/
│   ├── router/
│   ├── stores/
│   └── main.js
├── db.json
├── index.html
├── package.json
└── postcss.config.js
```

---

## 📝 주요 기능

1. 회원가입/로그인/마이페이지
2. 아이디 중복 확인, 비밀번호 검증, 프로필 수정
3. **수입·지출 CRUD**
4. **작성/수정/삭제 (카테고리, 금액, 메모 입력)**
5. 거래 내역 조회 및 필터
6. 기간별, 유형별, 금액별 필터링
7. 분석 페이지
8. 이번 달/지난 달 총합
9. 원형/막대 차트 시각화
10. 메인 네비게이션
11. 404 에러 페이지

---

## 🧩 컴포넌트

- **common/CategoryPicker.vue: 카테고리 선택 버튼**
- **common/TypeSwitch.vue: 수입/지출 토글**
- charts/ExpenseChart.vue: 분석용 차트
- sums/LastSum.vue: 지난달 합계
- **views/ExpenseEditPage.vue: 지출 수정 페이지**
- views/Login.vue: 로그인
- stores/userStore.js: 사용자 인증 상태
- stores/transactionStore.js: 거래 내역 상태

## ✅ 담당 역할: 정혜빈

**수입/지출 작성, 수정, 삭제 페이지 개발 담당**

날짜	작업 내용
4/08	프로젝트 초기 설정, Pinia 스토어, 라우터, Axios
4/09	카테고리, 기록 폼, 토글 컴포넌트 구현, 작성/수정 페이지
4/10	Tailwind 기반 반응형, 배너 이미지 추가, 404 연동

---

## 주요 기여

- CRUD 기능 전체 구현
- 모바일/PC 반응형 UI
- 배너 이미지 압축 및 UX 개선
- try-catch 예외처리 및 404 연동
- 라우터 경로 정의 및 페이지 연결 설계

---

## 🔗 프로젝트 정리 링크
[커비의가계부_노션링크](https://hyebini.notion.site/1e7db7d859568077b562d733098ee153?pvs=4)

---

## ✨ 기타

- Vue.js, Pinia, TailwindCSS 기반
- Mobile First
- SRP(단일 책임 원칙), 재사용성 고려
- GitHub Flow 기반 협업
