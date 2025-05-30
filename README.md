# 스팸네컷 프론트 레포지토리

## 🎮 사용법

1. **시작**: "시작하기" 버튼 클릭
2. **튜토리얼**: 사용법 안내 확인
3. **프레임 선택**: 원하는 포토프레임 선택
4. **촬영**: 
   - 카메라 버튼 클릭
   - 5초 카운트다운 후 자동 촬영
   - 총 4장 연속 촬영
5. **결과 확인**: 완성된 포토프레임 확인 및 다운로드

## 🔧 개발 정보

### 사용 언어와 프레임워크
![CSS]
![JS]
![react]

### 주요 컴포넌트

- **WebcamCapture**: 웹캠 제어 및 사진 촬영
- **PhotoFrameTest**: 이미지 합성 및 프레임 처리
- **ChooseScreen**: 프레임 선택 인터페이스

### 카메라 설정

- **해상도**: 960x1280 (세로 모드)
- **포맷**: JPEG
- **외부 웹캠 우선 사용**: HDMI 연결 카메라 자동 감지
- **권한 관리**: 자동 권한 요청 및 에러 처리

### 이미지 처리

- **크롭**: 자동 중앙 정렬 및 비율 조정
- **최종 해상도**: 1920x2560
- **품질**: 최고 품질 (1.0) JPEG

## 🐛 문제 해결

### 카메라가 안 켜질 때
1. 브라우저 권한 확인 (주소창 왼쪽 🔒 아이콘)
2. HTTPS로 실행: `HTTPS=true npm start`
3. 다른 앱에서 카메라 사용 중인지 확인
4. 브라우저 개발자 도구(F12) → Console에서 에러 확인

### 빌드 관련
```bash
# 프로덕션 빌드
npm run build

# 개발환경 실행
npm start
```


[JS]: https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white
[react]: https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=white
[CSS]: https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white