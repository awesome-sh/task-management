# Task Management App

Public Task Management WebApp Release Repository.

레스너들을 위한 똑똑한 일정관리

하이브리드 웹앱 기술검토를 목적으로 스터디 중 기획부터 생각주머니가 디벨롭되어 진행하게 된 프로젝트 🤣

Develop URL
https://task-manager-lac.vercel.app

최종배포 : Android Release를 목표로 함

### Preview
![screenshot-task-manager-lac vercel app-2022 07 08-15_14_14](https://user-images.githubusercontent.com/46561976/177928585-43271363-0a96-4e30-bc30-9e3e42a4840b.png)


### Develop Env

- Core: React
  
- Styling: Styled Components

- State Management: Context API
  
- Database: Web (Local Storage), Android App (Realm, SharedPreferences)

- Vercel (https://vercel.app), Static Web Release


### Features

- 종합 대시보드 : 레슨생, 일정, 메모 데이터들의 전반적인 지표를 표출
- 레슨생 관리 : 레슨생 CRUD / 전화걸기
- 레슨일정 관리 : 레슨생 등록 시 작성한 레슨일정 데이터로 캘린터에 마킹 및 레슨진행 여부 토글링
- 메모장 : 일정과 별개로 자유롭게 남길 수 있는 메모장 / 민감한 내용의 메모는 잠금(비밀글, 암호로 인증) 처리 가능
- 통계 : 레슨생 인원 증/감 현황, 이번 달 예상 레슨비 통계, 지난 달, 다음 달 레슨비용 예측

### Progress

- 기획 ✓
- 디자인, 수시로 변경 (바꾸고 나면 더 이쁜 디자인이 생각나는건?...) ✓

- 22.07.08 : 현재까지 개발 완료된 기능
  - 메모 탭
 네이티브 브릿지 작업 → 웹 접근/앱 접근을 분리하여 User Agent에 따라 다른 스토리지를 사용하도록 개발
 안드로이드(Realm) / 웹(Local Storage, 임시)
