# React 개인 프로젝트 - 노랑풍선(YELLOW BALLOON) 클론 코딩

React, Redux, React-Router를 기반으로 구현한 여행사 예약 시스템 클론 코딩 프로젝트입니다.

## 📌 목차
- [개요](#-개요)
- [기술 스택](#-기술-스택)
- [학습 목표](#-학습-목표)
- [주요 기능 및 화면 구성](#-주요-기능-및-화면-구성)
- [개선 사항 및 회고](#-개선-사항-및-회고)

---

## 📝 개요
- **프로젝트 목표:** 여행사 사이트(노랑풍선)의 UI/UX 및 예약 시스템을 직접 구현하며 React 구조 및 상태 관리 학습
- **개발 인원:** 1인 (프론트엔드 개인 프로젝트 / 이근석)

---

🛠 기술 스택
- **Language:** JavaScript (ES6+), HTML5, CSS3 
- **Framework / Library:** React, React Router DOM
- **State Management:** - Redux Toolkit: 장바구니 및 예약 정보 전역 상태 관리 
- **Context API:** 컴포넌트 간 실시간 데이터 전달 및 상태 공유 
- **localStorage:** 게시판 데이터(CRUD) 및 장바구니 정보 영구 보존 
- **Data:** JSON(Mock Data) 비동기 로딩 (fetch API 활용) 
- **Icons:** React Icons (FiCalendar, FiShoppingBag, FiCheck 등 활용) 

---

🚀 주요 구현 로직 및 회고
- **상태 기반 동적 날짜 동기화:**

    사용자가 출발일을 변경할 때 기존 출발일과의 편차(diffDays)를 계산하여 전체 일정표의 날짜와 요일이 실시간으로 재구성되도록 구현했습니다. 단순 텍스트 변경이 아닌 shiftDateString 유틸리티 함수를 통한 선언적 UI 업데이트를 경험했습니다.

- **비즈니스 로직 기반 CRUD 게시판:**

    백엔드 없이 localStorage만을 활용해 '고객의 소리' 게시판의 등록, 조회, 수정, 삭제 기능을 완벽히 구현했습니다. 특히 mode 상태값에 따라 4가지 뷰(LIST, READ, WRITE, EDIT)가 유기적으로 전환되는 구조를 설계했습니다.

- **전역 상태와 로컬 스토리지의 결합:**

    Redux Toolkit을 통해 관리되는 장바구니 데이터가 새로고침 시에도 유지되도록 useEffect를 활용해 스토리지와 실시간으로 동기화하는 로직을 구축했습니다.

---

## 🎯 학습 목표
1. React 기반의 컴포넌트 설계 방식 이해
2. Redux Toolkit을 활용한 전역 상태 관리 학습 및 실전 적용
3. React Router를 통한 라우팅 처리 및 페이지 전환 방식 학습
4. fetch API를 통한 외부 데이터 로딩 및 전역 상태 구성

---

## 💻 주요 기능 및 화면 구성
<br>
<img width="6000" height="3375" alt="React 포트폴리오1" src="https://github.com/user-attachments/assets/db329156-a409-4518-8901-dbfcaeb2f465" />
<br>
<br>
<img width="6000" height="3375" alt="React 포트폴리오2" src="https://github.com/user-attachments/assets/2bcdac78-2bed-4368-bd04-688dafd8a3ae" />
<br>
<br>
<img width="6000" height="3375" alt="React 포트폴리오3" src="https://github.com/user-attachments/assets/316e33c0-db1a-4ce8-a6a7-76e1853171a1" />
<br>
<br>
<img width="6000" height="3375" alt="React 포트폴리오4" src="https://github.com/user-attachments/assets/a5d127aa-5052-4a96-bfe9-0a17b69ac881" />
<br>
<br>
<img width="6000" height="3375" alt="React 포트폴리오5" src="https://github.com/user-attachments/assets/6086cc0c-15e9-4dba-a675-308b672bcb9b" />
<br>
<br>
<img width="6000" height="3375" alt="React 포트폴리오6" src="https://github.com/user-attachments/assets/7785374d-9a46-4c41-ab0c-6303528363e7" />
<br>
<br>
<img width="6000" height="3375" alt="React 포트폴리오7" src="https://github.com/user-attachments/assets/9148174f-286a-4476-ad62-dcd4617c0905" />
<br>
<br>
<img width="6000" height="3375" alt="React 포트폴리오8" src="https://github.com/user-attachments/assets/42116694-cdc5-4cd2-b478-96bedf1ba68d" />
<br>
<br>
<img width="6000" height="3375" alt="React 포트폴리오9" src="https://github.com/user-attachments/assets/32665cb9-a979-4a3f-881e-f0bfb05ef679" />
<br>
<br>
<img width="6000" height="3375" alt="React 포트폴리오10" src="https://github.com/user-attachments/assets/c01890b8-310f-4594-837d-0a2aa475cb23" />
<br>
<br>
<img width="6000" height="3375" alt="React 포트폴리오11" src="https://github.com/user-attachments/assets/13864d11-8444-432e-aef3-f95aebe82eb2" />
<br>
<br>
<img width="6000" height="3375" alt="React 포트폴리오12" src="https://github.com/user-attachments/assets/a37e3f3d-2c47-485a-a72e-dd94528b7007" />
<br>
<br>
<img width="6000" height="3375" alt="React 포트폴리오13" src="https://github.com/user-attachments/assets/5bdcdf90-436a-4979-970f-190466c32c14" />
<br>
<br>
<img width="6000" height="3375" alt="React 포트폴리오14" src="https://github.com/user-attachments/assets/642af844-8be3-4dd1-b3b4-75bb6d500c6d" />




---

## 🚀 개선 사항 및 회고 (추후 업데이트 예정)

1. **상태 관리 도구의 단일화:** - 현재 Redux Toolkit, Context API, localStorage가 각각 다른 목적으로 혼용되고 있습니다. 이를 Redux Toolkit(RTK) 중심으로 통합하여 데이터 흐름을 일원화하고 유지보수 효율을 높일 계획입니다.
2. **반응형 웹(Responsive Web) 완성:** - 현재 데스크탑 환경 위주로 구성된 UI에 미디어 쿼리를 전면 도입하여 모바일 및 태블릿 기기에서도 최적화된 사용자 경험(UX)을 제공하고자 합니다.
3. **백엔드 서버 및 API 연동:** - 현재의 Mock Data와 localStorage 기반 환경에서 탈피하여, 실제 DB(MySQL 등)와 REST API를 연동한 실시간 데이터 통신 환경으로 확장할 예정입니다.
