# Life-Tracker
시간, 건강, 목표 관리 등 통합적으로 관리할 수 있는 iOS/웹 앱

Life Tracker는 개인의 일상, 목표, 건강 및 시간 관리를 돕기 위한 통합 플랫폼입니다.
사용자는 물 섭취, 운동, 업무 및 개인 시간을 추적하며, 주/월/연 단위로 일기를 작성하고 회고를 볼 수 있습니다.
또한 자격증 목표를 설정하고 진행 상황을 시각적으로 확인할 수 있습니다.
웹과 iOS에서 연동되며, Google Calendar와의 통합을 통해 일정 관리도 간편하게 제공합니다.

# 기술스택
Frontend
- React (Next.js)
- TailwindCSS 또는 Material-UI
Backend
- Node.js (Express.js)
- Google Calendar API
Database
- Firebase Firestore 또는 MongoDB Atlas
기타
- Firebase Authentication (로그인 기능)
- React Native 또는 PWA (iOS 지원)

# 프로젝트 기능
1. 메인 화면
- 오늘의 활동을 시각적으로 표시
- 물 섭취량: 물 아이콘으로 표시
- 운동 시간: 운동 아이콘으로 표시
- 업무/개인 시간 비율: 막대그래프 또는 파이차트
2. 상세 화면
- 일기 작성 및 저장: 하루를 돌아보는 일기 작성
- 주/월/연간 회고 보기:
- 주/월/연 단위의 회고 비교
3. 목표 관리
- 자격증 목표 설정 및 진행 추적
- 목표 완료 시 “라이프 업적”으로 메인 화면에 표시
4. Google Calendar 연동
- 캘린더와 연동하여 일정 관리 및 시간 추적
5. 로그인 기능
- Firebase Authentication을 활용한 이메일/비밀번호 및 Google 계정 로그인
  
# 프로젝트 개발 단계
	1.	기본 환경 설정 및 로그인/캘린더 연동
	2.	메인 화면 및 데이터 시각화 기능 구현
	3.	상세 화면(일기 및 회고) 구현
	4.	목표 관리 및 업적 시스템 구축
	5.	UI 디자인 개선 및 iOS 연동 최적화
