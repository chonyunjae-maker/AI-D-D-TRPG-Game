<img width="1308" height="871" alt="캡처" src="https://github.com/user-attachments/assets/9d475d9f-33d8-46f0-ba55-c4ec74b20dee" />
# **⚔️ Chronicles of Eldoria — AI D\&D TRPG Web Game**

> **Gemini API**와 웹 기술(HTML, Tailwind CSS, JavaScript)을 활용해 구현한 몰입감 넘치는 텍스트 기반 인터랙티브 D\&D(Dungeons & Dragons) TRPG 웹 게임입니다.

## **🌟 주요 특징 (Features)**

1. **실시간 AI 던전 마스터 (DM):**  
   * 플레이어의 자유로운 행동 입력을 실시간으로 판정하고, 다크 판타지 세계관의 이야기를 흥미진진하게 이끌어갑니다.  
2. **시각적 몰입도 향상 (색상 구분):**  
   * 마크다운 볼드체(\*\*) 태그를 배제하여 깔끔한 가독성을 제공합니다.  
   * **대사:** 노란색/앰버 계열 (「...」, “...”)로 시각적 강조  
   * **생각/독백:** 회색 빗살무늬 박스 ((...)) 스타일로 내면 심리 묘사  
3. **간편한 API 키 관리:**  
   * 웹페이지 상단 헤더에서 본인의 Gemini API 키를 직접 입력하고 브라우저 로컬 스토리지에 안전하게 저장할 수 있습니다.  
4. **반응형 디자인:**  
   * PC와 모바일 환경 모두에서 최적화된 다크 판타지풍 UI를 제공합니다. 첫 행동 입력 시 캐릭터 설정 패널이 자동으로 접히며 게임 화면이 확장됩니다.

## **🚀 시작하기 (Getting Started)**

이 프로그램은 백엔드 서버 없이 단일 HTML 파일(index.html)로 작동하므로, 브라우저만 있으면 언제 어디서든 실행할 수 있습니다.

### **1\. Gemini API 키 발급 받기**

1. [Google AI Studio](https://aistudio.google.com/)에 방문하여 무료로 API 키를 발급받습니다.

### **2\. 실행 방법**

1. 이 저장소의 index.html 파일을 다운로드하거나 클론합니다.  
2. index.html 파일을 더블 클릭하여 웹 브라우저(Chrome, Edge, Safari 등)로 엽니다.  
3. 화면 상단의 **🔑 API 키** 입력란에 본인의 Gemini API 키를 입력하고 \[저장\]을 누릅니다.  
4. 왼쪽 사이드바에서 캐릭터 이름과 직업을 설정한 뒤, 첫 번째 행동을 입력하여 모험을 시작하세요\!

## **🛠️ 기술 스택 (Tech Stack)**

* **Frontend:** HTML5, JavaScript (Vanilla JS), Tailwind CSS (CDN)  
* **Fonts:** Cinzel (Fantasy Typography), Noto Sans KR  
* **AI Model:** Google Gemini 2.5 Flash API (generateContent)

## **📜 라이선스 (License)**

이 프로젝트는 MIT 라이선스를 따릅니다. 자유롭게 수정하고 나만의 TRPG 세계관으로 확장해 보세요\!
