# VoiceTyper - 바이브코딩할 때 쓰는 음성타이핑 프로그램

> 바이브코딩할 때 쓰는 음성타이핑 프로그램 (feat. 클로드코드, 코덱스)

## 소개

클로드코드(Claude Code)나 코덱스(Codex) 같은 AI 코딩 도구로 바이브코딩할 때, 키보드 대신 **말로 지시**하면 더 빠르고 편합니다.

단축키를 누르고 말하면, 음성을 인식하여 커서 위치에 텍스트를 자동 입력합니다.

- **간편한 사용** - 단축키(Right Ctrl)를 누르고 있는 동안 녹음, 떼면 자동 입력
- **높은 정확도** - faster-whisper 기반 최신 음성인식 엔진
- **다국어 지원** - 한국어, 영어, 일본어, 중국어
- **GPU 가속** - NVIDIA GPU(CUDA) 사용 시 더 빠른 인식
- **자동 업데이트** - 새 버전 출시 시 알림 및 원클릭 업데이트

## 다운로드

👉 [최신 버전 다운로드 (Releases)](https://github.com/pb-official/VoiceTyper-releases/releases/latest)

`VoiceTyper.exe`를 다운로드하여 실행하면 됩니다. 별도 설치 과정이 없습니다.

## 시스템 요구 사항

- Windows 10 이상
- 마이크
- (선택) NVIDIA GPU + CUDA Toolkit - GPU 가속 사용 시

## 사용 방법

1. `VoiceTyper.exe` 실행 (시스템 트레이에 아이콘 표시)
2. 텍스트를 입력할 곳에 커서를 놓고
3. **Right Ctrl** 키를 누른 채로 말하기
4. 키를 떼면 음성이 인식되어 자동 입력

## 설정

트레이 아이콘 우클릭 → **설정** 에서 변경 가능:

| 항목 | 설명 |
|------|------|
| 언어 | 한국어, English, 日本語, 中文 |
| 모델 크기 | tiny ~ large-v3 (클수록 정확, 느림) |
| 장치 | CPU / GPU(CUDA) |
| 단축키 | 녹음 시작/종료 키 변경 |
| 자동 시작 | Windows 부팅 시 자동 실행 |
| 소리 알림 | 녹음 시작/종료 효과음 |

## 후원

이 프로그램이 유용하셨다면 커피 한 잔 후원 부탁드립니다 ☕

<p align="center">
  <a href="https://qr.kakaopay.com/FMUehKbRf">
    <img src="kakaopay-qr.png" alt="카카오페이 후원 QR코드" width="250">
  </a>
  <br>
  <em>카카오페이로 후원하기</em>
</p>

## 문의

문제가 있으면 [Issues](https://github.com/pb-official/VoiceTyper-releases/issues)에 남겨주세요.
