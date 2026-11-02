<p align="center">
  <img src="./assets/hello_world.png" width="420" alt="Hello World" />
</p>

# Hi, I'm Hajin 👋

Full Stack Developer

React Native 기반 서비스 개발부터 Node.js / NestJS 기반 API 및 데이터 처리,
AWS 기반 배포 자동화와 서비스 운영까지 경험해 온 개발자입니다.

새로운 기술 자체보다 문제를 분석하고, 필요한 기술을 학습해 실제 개선으로 연결하는 과정을 중요하게 생각합니다.

프론트엔드와 백엔드의 경계를 나누기보다,
서비스의 전체 흐름을 이해하고 문제에 적합한 기술과 구조를 선택하는 개발을 지향합니다.

🔗 Portfolio: https://summer-jin.store/

---

## Tech Stack

**Backend**  
Node.js · TypeScript · NestJS · REST API · Prisma

**Database / Data**  
PostgreSQL · MySQL · Redis · PostGIS

**Frontend / Mobile**  
JavaScript · TypeScript · React · React Native · Next.js

**Infrastructure / DevOps**  
AWS (EC2, S3, SSM, IAM) · Docker · GitHub Actions · Git

---

## Work Experience

### Quad Miners | Web Developer

기업 홈페이지 개발·운영을 담당하며,
외주 중심의 관리 체계를 내부 개발 및 배포 환경으로 전환했습니다.

- 외주 운영 서버의 소스 분석 및 레거시 코드 정리
- 사내 Git 기반 형상관리 체계 구축
- WordPress Core와 커스텀 테마·플러그인 분리 및 개발환경 표준화
- GitHub Actions → Private S3 → AWS SSM → EC2 기반 CI/CD 파이프라인 구축
- IAM Role 및 OIDC 기반 인증으로 장기 Access Key 의존도 축소
- 배포 자동화 과정에 백업, 권한 설정, Apache reload 및 실패 시 rollback 처리 구현
- 기업 홈페이지 신규 페이지 개발, 기존 UI 개선 및 운영 환경 관리

`WordPress` `PHP` `JavaScript` `MySQL` `AWS` `GitHub Actions`

### iCRAFT | Frontend Developer

React Native 기반 DApp 운영 서비스에서
사용자 기능 개발과 REST API 연동을 담당했습니다.

- 배송 옵션 선택, 배송지 입력 및 배송 현황 확인 등 사용자 기능 개발
- REST API 연동 및 응답에 따른 화면 상태 처리
- Class Component를 Function Component 및 Hooks 기반으로 전환
- 기존 코드 유지보수, 오류 수정 및 운영 서비스 개선

`React Native` `JavaScript` `REST API` `React Hooks`

---

## Featured Projects

### [Check EAT](https://github.com/pepperflavor/Check_Eat)

식단 조건 기반 음식점 검색 및 음식 데이터 처리 서비스

사용자의 식단 조건과 위치를 기반으로 음식점을 검색하고,
OCR·AI·외부 API를 활용해 음식점 및 메뉴 정보를 처리하는 서비스입니다.

- NestJS 기반 REST API 및 PostgreSQL 데이터 모델 설계
- PostGIS 기반 위치 반경 검색과 식단 조건 필터링 구현
- 검색 구조 개선으로 API 응답 시간 약 8초 → 3초 단축
- Redis 기반 캐싱 및 BullMQ를 활용한 비동기 작업 처리
- 외부 API 장애에 대응하기 위한 재시도 및 exponential backoff 로직 구현
- Azure OCR·AI 및 공공 API를 연동한 사업자 인증·음식 데이터 처리

`NestJS` `TypeScript` `PostgreSQL` `Prisma` `PostGIS` `Redis` `BullMQ` `Azure`

---

### [Stadiumly](https://github.com/pepperflavor/Stadiumly_Backend_Second)

KBO 경기 및 직관 정보 자동 수집·제공 서비스

야구 직관에 필요한 경기 일정, 날씨, 주변 정보를
자동 수집하고 API로 제공하는 서비스입니다.

- NestJS 기반 경기·직관 정보 REST API 개발
- Scheduler를 활용한 KBO 경기 데이터 수집 자동화
- 웹 데이터 크롤링 및 파싱을 통한 데이터 정규화
- PostgreSQL 기반 수집 데이터 저장 및 조회
- Redis 및 Docker 환경 구성, 컨테이너 간 통신 오류 분석·해결

`NestJS` `TypeScript` `PostgreSQL` `Prisma` `Redis` `Docker` `Scheduler`

---

### [Portfolio World](https://github.com/pepperflavor/Resume)

Next.js와 Phaser로 구현한 인터랙티브 개발자 포트폴리오

게임 속 공간을 탐험하며 개발 경험과 프로젝트를 확인할 수 있는
웹 기반 인터랙티브 포트폴리오입니다.

- Next.js · TypeScript · Phaser 기반 웹 애플리케이션 구현
- React와 Phaser 간 상태 소유권 및 이벤트 전달 책임 분리
- Single Source of Truth 원칙을 적용한 퀘스트 진행 상태 관리
- 키보드·모바일 입력 정규화 및 입력 처리 구조 개선
- 오디오 이벤트 기반 게임 판정 로직 구현
- 모바일 환경 및 PWA 대응

`Next.js` `TypeScript` `React` `Phaser` `PWA`

🌐 Live Demo: https://summer-jin.store/

---

### [DiveToSpace](https://github.com/orax5/orax5)

음악 저작권 NFT 펀딩·거래 플랫폼

Web2 서비스와 블록체인을 결합한 음악 NFT 펀딩 플랫폼으로,
4인 팀에서 백엔드 개발을 전담했습니다.

- NestJS 기반 사용자 인증 및 역할별 REST API 구현
- 펀딩 진행 상태에 따른 데이터 모델 및 처리 흐름 설계
- 관리자 승인·거절 및 펀딩 상태 관리 기능 구현
- AWS S3 파일 저장과 IPFS 메타데이터 저장 영역 분리
- ERC-1155 기반 NFT 서비스와 백엔드 연동

`NestJS` `TypeScript` `MySQL` `Prisma` `Redis` `AWS S3` `IPFS` `ERC-1155`

---

## Engineering Interests

- Software Architecture — 책임 분리, 상태 관리, 유지보수 가능한 구조
- API & Data Processing — API 설계, 데이터 수집·정규화 및 성능 개선
- Asynchronous Processing — 작업 큐, 재시도 및 외부 서비스 장애 대응
- Database Design — 관계형 데이터 모델링, 공간 데이터 검색 및 캐싱
- Infrastructure & DevOps — CI/CD, AWS, 배포 자동화 및 운영 안정성
- Problem Solving — 문제 원인 분석, 기술 검증 및 구조 개선

---

## Links

- 🌐 Portfolio: https://summer-jin.store/
- 💻 GitHub: https://github.com/pepperflavor
