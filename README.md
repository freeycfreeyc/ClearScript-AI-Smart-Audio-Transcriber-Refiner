🎙️ AI Voice Recorder & Editor (STT + AI Correction)
OpenAI Whisper를 이용한 로컬 음성 인식과 Google Gemini 2.5 Flash를 활용한 지능형 텍스트 교정을 결합한 데스크톱 애플리케이션입니다. 강의 녹음, 회의록 정리, 인터뷰 스크립트 작성 시 오탈자를 수정하고 문맥을 매끄럽게 다듬는 작업을 자동화합니다.

✨ 주요 기능 (Key Features)
Local STT Engine: OpenAI의 Whisper (Small) 모델을 활용하여 별도의 비용 없이 로컬 환경에서 음성을 텍스트로 변환합니다.

AI Contextual Correction: 변환된 텍스트를 Google Gemini API에 전달하여 문맥에 맞는 오탈자 교정, 띄어쓰기 수정, 문단 구분을 수행합니다.

Custom Prompting: 사용자가 '핵심 키워드'나 '상황 설명'을 입력하여 AI의 교정 방향을 직접 제어할 수 있습니다.

Intuitive UI/UX: CustomTkinter 기반의 모던한 다크 모드 GUI와 파일 Drag & Drop 기능을 지원합니다.

Real-time Logging: 작업 진행 상황(모델 로딩, 변환 중, 교정 중)을 실시간으로 확인할 수 있습니다.

🛠️ 기술 스택 (Tech Stack)
Language: Python 3.11

AI Models: * openai-whisper (Small Model) - 로컬 음성 인식

google-generativeai (Gemini 2.5 Flash) - 문맥 교정 및 요약

GUI Library: CustomTkinter, TkinterDnD2

Build Tool: PyInstaller (GPU Acceleration 지원)

🚀 시작하기 (Getting Started)
1. 필수 요구사항 (Prerequisites)
이 프로그램은 음성 처리를 위해 FFmpeg가 반드시 필요합니다.

Windows: winget install ffmpeg 또는 공식 홈페이지에서 다운로드 후 환경 변수 설정

Mac: brew install ffmpeg

2. API 키 발급
문맥 교정 기능을 사용하려면 Google Gemini API 키가 필요합니다.

Google AI Studio에서 무료로 발급받을 수 있습니다.

3. 설치 및 실행 (Development Mode)
Bash
# 저장소 클론
git clone https://github.com/freeycfreeyc/AI-Voice-Recorder-and-Editor.git

# 필수 패키지 설치
pip install -r requirements.txt

# 프로그램 실행
python app.py
📦 배포 (Distribution)
고성능 GPU 가속(NVIDIA CUDA)을 지원하는 단일 실행 파일(.exe) 버전은 아래 링크에서 다운로드할 수 있습니다.

[👉 최신 버전 다운로드 https://drive.google.com/file/d/1uDpn-nM-m-6yhwQQtmUyp2CSeJx9-yix/view?usp=drive_link] * 참고: AI 엔진 포함으로 인해 용량이 약 2.7GB입니다.

Email: [kim7539548@gmail.com]
