# Deep_me 감정대화 테스트 페이지

Deep_me 백엔드 서버와 WebSocket으로 연결하여 감정대화를 테스트할 수 있는 웹 페이지입니다.

## 사용 방법

1. 웹 페이지 열기: https://bentleypark.github.io/deepme-chat-test/
2. 페이지를 열면 서버를 자동으로 깨웁니다. 상태 표시줄에 "서버 준비됨"이 뜰 때까지 기다리세요.
   - 테스트 서버는 Render 무료 플랜이라 15분 동안 요청이 없으면 잠듭니다. 깨우는 데 보통 1분 이내, 최대 90초가 걸립니다.
3. "연결" 버튼 클릭
   - 로그인 전이면 Google 로그인이 뜨고, 로그인하면 자동으로 연결됩니다 (로그인은 탭을 닫기 전까지 유지됩니다)
4. 메시지 입력 후 Enter로 전송
5. 실시간 AI 응답 확인

## 기술 스택

- WebSocket (wss://deep-me-test-server.onrender.com/ws/emotion)
- 바닐라 JavaScript
- GitHub Pages

## 백엔드 서버

- 저장소: https://github.com/Deepme123/Deep_me_V2
- 테스트 서버: https://deep-me-test-server.onrender.com
