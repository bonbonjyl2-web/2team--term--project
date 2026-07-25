# [Project A] AI 기반 모바일용 병원 진료 예약 서비스 UI/UX 디자인 시안 제작
 
  ## 주제 설명
 
 본 프로젝트는 디지털 기기 조작에 어려움을 겪는 60대 이상 고령층 사용자가 병원 접수, 예약, 진료 내역, 확인, 복약 관리를 손쉽게 수행할 수 있도록 돕는 'AI 병원 접수·진료 도우미' 모바일 앱 UI/UX 디자인 생성 및 프롬프트 고도화 작업
 
 ### 기본 규칙
 텍스트 프롬프트의 구성 요소(스타일, 레이아웃, 색상 등)가 결과물의 기본 규칙 적용하여 60대 고령층의 사용성, 접근성, 편의성을 고려함
● 가시성 확보: 큰 글씨, 큰 카드형 버튼, 높은 색상 대비(7:1 이상) 적용
● 직관성 강화: 직관적인 에셋 및 아이콘, 넉넉한 여백 레이아웃 설계
● 단계별 검증: 메인 홈 화면부터 마이페이지까지 5개 주요 화면의 순차적 이미지 생성 및 QA 반영

 시니어 친화적 UI/UX 디자인 가이드라인 요약
● Typography: 최소 16pt 이상의 본문 크기와 20pt 이상의 타이틀 크기 적용으로 시안성 확보
● Color System: 메인 메디컬 블루(Medical Blue, #0052CC)를 통한 신뢰감 제공 및 고대비
텍스트(#0F172A) 활용
● Layout & Tactile: 2x2 카드 그리드 시스템과 넉넉한 여백, Soft Shadow로 터치 가능 영역 강조
● Navigation: 고정형 하단 네비게이션 바를 통한 앱 전체 흐름 통제권 부여

결론 및 향후 계획
본보고를 통해 총 5장의 모바일 UI 화면 이미지 작성이 완료되었으며, 피드백을 통해 발견된 네비게이션 바 요소 수정까지 차질 없이 반영되었습니다. 완성된 UI 시안은 Figma UI Kit 구성 및 실개발 전형 모형으로 활용될 예정


## UI 디자인 이미지 (5 장)

서비스의 핵심 기능을 시각적으로 표현한 모바일  UI 구성 & 디자인 이미지 
* 메인 페이지 1장 : ![alt text](병원예약-1.png)

* 상세 페이지 3장 : ![alt text](병원예약-2.png) ![alt text](병원예약-3.png) ![alt text](병원예약-4.png)

* 마이 페이지 1장 : ![alt text](병원예약-5.png)



# 프롬프트 최적화

 프롬프트 개선 과정(초안 → 수정 → 최종)을 문서로 기록한다.
  
  *  프롬프트 초안 

주제 : AI 병원 접수·진료 도우미

첫 화면은 사용자가 앱을 처음 실행했을 때의 메인(Home) 화면이다.

상단에는 "안녕하세요, 김철수님"과 함께 프로필 사진이 표시된다.

중앙에는 접근성을 고려한 큰 카드형 버튼 4개가 배치되어 있다.

🩺 증상 입력하기

🎤 음성으로 말하기

🤖 AI 진료과 추천

📅 병원 예약하기


그 아래에는 최근 예약 내역과 오늘의 예약 일정 카드가 표시된다.

하단에는 아이콘이 포함된 네비게이션 바가 있다.


홈
예약
진료내역
복약관리
마이페이지

디자인 컨셉은 60대 이상 고령층도 쉽게 사용할 수 있도록 큰 글씨, 큰 버튼, 높은 대비, 직관적인 아이콘, 여백이 넉넉한 레이아웃을 적용한다.

전체 디자인은 화이트와 메디컬 블루를 메인 컬러로 사용하며, 따뜻하고 신뢰감 있는 병원 분위기, Apple iOS 스타일, Material Design 3, Figma High Fidelity UI, Dribbble 스타일, 실제 출시 가능한 수준의 모바일 앱 디자인, Modern Healthcare App, Clean Minimal UI, Soft Shadow, Rounded Card, 9:16 모바일 화면, 초고해상도, 한국어 텍스트.
  
 
  * 프롬프트 수정 
   
화면별 UI 생성 및 프롬프트 피드백 수정 과정
단계 화면명 주요 요구사항 및 수정 내용 프롬프트 피드백 적용

포인트

- 상태

   ** 1장 메인 (Home) • 상단 프로필("안녕하세요, 김철수님")
• 중앙 4개 대형 카드(증상 입력, 음성, AI 추천, 예약)
• 하단 5대 탭 네비게이션 적용

- 초기 슬라이드 방식에서 사용자의 요청에 따라 단독 모바일 UI 이미지 생성으로 전환 및
고대비 버튼 배치

- 완료

** 2장 병원 예약 • 음성 안내 박스("날짜와 시간을 고령층의 복잡한 달력 완료

단계 화면명 주요 요구사항 및 수정 내용 프롬프트 피드백 적용 포인트

- 상태

선택해주세요")
• 날짜/시간 선택 칩 및 추천 병원 카운드
• 하단 대형 '예약 완료' CTA 버튼

클릭 패턴을 최소화하고 큼직한 선택 버튼 카드 구조로 프롬프트 고도화

** 3장 진료 내역 • 병원별 진료 이력 리스트 (서울중앙병원 등)
• 의사명, 처방전 유무, 진료 상태 태그

카드 형태의 시각적 구분감 강조, 텍스트 가독성 최우선 확보

- 수정완료


   ** 4장 복약 관리 • 시간대별 복약 일정 (아침, 점심, 저녁)
• 약 종류 명시 및 '복약 완료/복약 확인'

- 상태 버튼

복약 상태 파악이 용이하도록 색상 태그(초록/노랑) 및 대형 아이콘 적용

- 완료

 ** 5장 마이페이지 • 사용자 기본 정보 및 가족 긴급 알림
• 내 정보 수정, 건강 리포트, 앱 설정 grid 카드

고령층 보호자 연동 및 긴급 연락망 접근성을 고려한 UI 구성

완료


 *** 주요 수정 요구사항 분석 (QA & Revision Highlight)

🔍 [3장 진료내역 화면] 하단 네비게이션 바 누락 이슈 수정
문제점: 3번째 "진료내역" 이미지 생성 결과물에서 하단 네비게이션 바(홈, 예약, 진료내역, 복약관리,
마이페이지)가 잘리거나 누락되는 문제 발생.

수정 전 :  ![alt text](image.png)

수정 작업: 이미지 생성 프롬프트 내에 Bottom Navigation Bar with 5 icons: Home, Booking, Medical History, Medication, My Page 요소를 명확히 재정의하고, 화면 하단 영역 크기를 재조정하여 5개 탭이 완벽히 표시되도록 재생성 완료.

수정 후 : ![alt text](image-1.png)



   
  ** 프롬프트 최종 

주제 : AI 병원 접수·진료 도우미

첫 화면은 사용자가 앱을 처음 실행했을 때의 메인(Home) 화면이다.

상단에는 "안녕하세요, 김철수님"과 함께 프로필 사진이 표시된다.

중앙에는 접근성을 고려한 큰 카드형 버튼 4개가 배치되어 있다.
🩺 증상 입력하기
🎤 음성으로 말하기
🤖 AI 진료과 추천
📅 병원 예약하기

그 아래에는 최근 예약 내역과 오늘의 예약 일정 카드가 표시된다.

하단에는 아이콘이 포함된 네비게이션 바가 있다.
홈 / 예약 / 진료내역 / 복약관리 / 마이페이지

디자인 컨셉은 60대 이상 고령층도 쉽게 사용할 수 있도록 큰 글씨, 큰 버튼, 높은 대비, 직관적인 아이콘, 여백이 넉넉한 레이아웃을 적용한다.

전체 디자인은 화이트와 메디컬 블루를 메인 컬러로 사용하며, 따뜻하고 신뢰감 있는 병원 분위기, Apple iOS 스타일, Material Design 3, Figma High Fidelity UI, Dribbble 스타일, 실제 출시 가능한 수준의 모바일 앱 디자인, Modern Healthcare App, Clean Minimal UI, Soft Shadow, Rounded Card, 9:16 모바일 화면, 초고해상도, 한국어 텍스트.
중간 수정 및 피드백 (Revision & QA Issue)
발생한 문제점 및 수정 요청 사항:

문제점: 3장 "진료내역" 이미지 생성 시 하단 네비게이션 바("홈", "예약", "진료내역", "복약관리", "마이페이지")가 생성 범위를 벗어나 잘리거나 누락되는 문제 발생.

수정 요청 사항: 이미지 생성 모델이 화면 하단 탭 영역을 명확히 인식하여 잘림 없이 5개 메뉴 항목을 완벽히 포함하도록 레이아웃 구도를 재조정하고 하단 영역 가이드라인 보완.

최종 완성본 생성 프롬프트 (Final Prompt)
수정 반영 및 고도화된 영문 Image Generation Prompt:

하단 네비게이션 바 잘림 현상을 해결하고, 고령층 접근성(Senior Accessibility) 요소를 명확한 인자 값으로 지정하여 완성한 최종 프롬프트입니다.

Plaintext
A high-fidelity mobile app UI screen design for a senior-friendly AI Healthcare Assistant, "진료내역" (Medical History) page, 9:16 portrait orientation, full view from top status bar to bottom navigation.

Design System & Aesthetic:
Clean minimal UI, Apple iOS and Material Design 3 style, Crisp white background with Medical Blue (#0052CC) accents, high-contrast dark gray text for maximum senior readability.
Generous whitespace, soft subtle shadows, rounded cards, high accessibility (60+ senior focused), clear Korean text.

Screen Layout (Top to Bottom):
Top Header: Clean title "진료내역 조회" in large Korean typography with standard mobile status bar at the top.
Filter Tabs: Pill-shaped filter buttons ("전체", "최근 3개월", "직접 선택") with "전체" highlighted in solid Medical Blue.
Content List: Vertical list of medical history cards including:
"서울중앙병원 (내과)" - 2026.07.13 | 오후 2:00 [진료완료]
"연세이비인후과" - 2026.06.28 | 오전 11:30 [진료완료]
"박치과의원" - 2026.06.10 | 오전 10:30 [진료완료]
Bottom Navigation Bar (CRITICAL REQUIREMENT):
Fully visible, uncropped bottom bar fixed at the very bottom of the screen.
5 distinct icons with clear Korean text labels under each icon:
"홈" (Home)
"예약" (Booking)
"진료내역" (Medical History - ACTIVE TAB, highlighted in Medical Blue)
"복약관리" (Medication)
"마이페이지" (My Page)

Overall Framing:
Must show the entire smartphone device screen mockup without clipping the bottom navigation area, ultra-clear resolution, Figma high-fidelity output. --ar 9:16


# Figma 프로젝트 (1개)

https://www.figma.com/make/oCRnHBCwoX47JI96wqVKZr/%EB%B3%91%EC%9B%90-%EC%B6%94%EC%B2%9C-%EC%98%88%EC%95%BD-%EC%95%B1?p=f

생성된 이미지를 배치하여 화면 흐름을 구성한 프로젝트 링크
클릭 가능한 영역(Hotspot) 또는 화면 전환 흐름 표시
