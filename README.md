# 🕒 ShiftOps AI

> **"고정 근무표 자동 생성과 CCTV 기반 혼잡도 분석을 결합한 지능형 알바 근무 운영 플랫폼"**

---

## 1. 📌 Project Overview
* **프로젝트명:** ShiftOps AI
* **개발 기간:** 7주
* **팀원 구성:** 4인 (React Native, React Web, Spring Boot 백엔드, Python AI 비전)
* **주요 목적:** 근무표 작성, 휴무/대타 처리, 출퇴근 관리 등 점주의 반복적인 운영 부담을 시스템으로 표준화하고, CCTV 기반 인원 분석을 통해 실시간 매장 혼잡도 통계를 시각화하여 최적의 인력 배치를 돕습니다.

---

## 2. 🛠️ Tech Stack

### 📱 Mobile App (직원 및 고객용)
| Framework | Platform |
| :---: | :---: |
| ![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) | ![Expo](https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white) |

### 💻 Admin Web (점주용)
| Language / Framework | Styling / Chart |
| :---: | :---: |
| ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white) | ![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) ![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white) |

### 🧱 Back-end & Database
| Main Server | Database |
| :---: | :---: |
| ![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white) | ![Oracle](https://img.shields.io/badge/Oracle_DB-F80000?style=for-the-badge&logo=oracle&logoColor=white) |

### 🤖 AI Vision & Analytics
| AI Server | Vision Processing |
| :---: | :---: |
| ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) | ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white) ![YOLO](https://img.shields.io/badge/YOLO-00FFFF?style=for-the-badge&logo=yolo&logoColor=black) |

---

## 3. 👥 Team & Individual Contributions

### 📱 김선민 (Mobile App Developer)
> **"React Native를 활용해 직원의 스케줄 관리와 QR 근태, 실시간 매장 상호작용을 담당하는 모바일 애플리케이션 프론트엔드를 총괄했습니다."**

#### 💡 Key Role & Detailed Contributions

##### 1️⃣ 모바일 앱 아키텍처 및 모던 UI 설계
* **크로스 플랫폼 앱 개발:** Expo 프레임워크 기반의 React Native 환경을 구축하여 네비게이션 구조 설계 및 화면 라우팅 처리.
* **모던 UI 밸런싱 최적화:** 모바일 디바이스의 다양한 해상도를 고려하여, 헤더(Header) 및 하단 네비게이션 탭 등 주요 레이아웃 요소들을 정확하게 중앙 정렬(Center Alignment) 처리하여 앱 전반의 시각적 안정성과 프로페셔널한 룩앤필 확보.

##### 2️⃣ 직원 운영 워크플로우 통합 구현
* **온보딩 및 스케줄링 UI:** 직원 회원가입부터 매장 연결 대기 상태 화면을 구현하고, 월간/주간 캘린더 기반의 개인 근무표 조회 인터페이스 개발.
* **휴무 및 대타 시스템 연동:** 특정 근무일에 대한 휴무 신청 모달과 대타 모집 공고 목록 확인, 지원 기능을 직관적인 플로우로 설계하여 점주의 관리 시스템(Web)과 원활하게 상호작용하도록 연동.

##### 3️⃣ 디바이스 하드웨어 제어 및 렌더링 최적화
* **QR 코드 기반 실시간 근태 관리:** 디바이스 카메라 권한을 제어하여 QR 스캔 기능을 구현하고, 출/퇴근 인증 기록 및 지각/정상 여부 데이터를 Spring Boot 서버로 실시간 전송.
* **독립적 컴포넌트 상태 관리:** 유휴시간 체크리스트 완료 처리 및 긴급 공지사항 확인 버튼 클릭 시, 앱 전체 화면의 새로고침을 방지하고 해당 컴포넌트의 확인 상태 데이터만 개별적으로 비동기 업데이트하도록 로직을 설계하여 매끄러운 UX 제공.
* **고객용 매장 현황 뷰 구현:** MVP 단계에 맞춰, 고객이 현재 매장의 혼잡도(여유/보통/혼잡 등)와 예상 웨이팅 시간을 간편하게 조회할 수 있는 전용 뷰 개발.
