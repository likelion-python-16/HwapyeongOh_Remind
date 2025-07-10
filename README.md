# 🐦 트위터 미디어 다운로더(Twitter Media Downloader)
**트위터 미디어를 zip으로 간편하게 다운로드할 수 있는 개인용 웹 애플리케이션**  
> 공개 트윗의 이미지, 영상, 텍스트를 트윗 내용을 제목으로 자동 저장해주는 웹 사이트
> 수동 입력 기반의 안전한 크롤링 방식 + 광고 기반 수익화까지 고려한 프로젝트

---

## 🔍 프로젝트 개요

트스는 사용자가 입력한 **트위터 계정의 공개 트윗 미디어**를  
→ 자동으로 수집하고,  
→ 트윗 내용을 각 미디어의 **파일 이름**으로 지정해 저장한 뒤,  
→ 하나의 `.zip` 파일로 묶어 다운로드해주는 웹사이트 기반 도구입니다.

AI 또는 자동 크롤링이 아닌 **수동 기반 수집**이기 때문에  
정책적으로 안전하고, 누구나 쉽게 사용할 수 있는 **트위터 콘텐츠 백업 도구**를 목표로 합니다.

---

## 🎯 주요 기능

- ✅ 트위터 계정명 수동 입력 기반
- ✅ 이미지(.jpg), 영상(.mp4), 텍스트(.txt) 자동 분류 및 저장
- ✅ 각 파일 이름 = 해당 트윗 본문 내용
- ✅ zip 형식으로 묶어서 한번에 다운로드
- ✅ 공개 계정 + 공개 트윗만 처리 (정책 위반 방지)
- ✅ 광고 노출 후 다운로드 → 수익화 연동 (애드센스/애드핏 등)
- ✅ 콘텐츠 다운로드 전 저작권 고지 표시
- ✅ 한국어/영어 UI 지원 예정 (i18n)
- ✅ 향후 OAuth 연동 및 Pro 유료 기능 확장 고려

---

## 🛠️ 사용 기술 스택

| 구분 | 기술 |
|------|------|
| 백엔드 | Python, Flask |
| 프론트엔드 | HTML, Bootstrap, JS (Vanilla) |
| 데이터 수집 | snscrape, yt-dlp, requests |
| 미디어 처리 | zipfile, pathlib |
| 광고 | Google AdSense (또는 애드핏), 자체 배너 삽입 |
| 배포 | Railway / Fly.io / Render (계획 중) |
| 문서화 | README + Swagger (확장 가능성) |


---

# DRF Todo List Final

### ⚙️ 개발 환경
- `asgiref==3.8.1`
- `attrs==25.3.0`
- `Django==5.2.3`
- `django-environ==0.12.0`
- `djangorestframework==3.16.0`
- `drf-spectacular==0.28.0`
- `drf-spectacular-sidecar==2025.6.1`
- `gunicorn==23.0.0`
- `inflection==0.5.1`
- `Jinja2==3.1.6`
- `jsonschema==4.24.0`
- `jsonschema-specifications==2025.4.1`
- `MarkupSafe==3.0.2`
- `packaging==25.0`
- `pillow==11.2.1`
- `PyYAML==6.0.2`
- `referencing==0.36.2`
- `rpds-py==0.25.1`
- `sqlparse==0.5.3`
- `typing_extensions==4.14.0`
- `uritemplate==4.2.0`

### ▶️ 실행 방법

1. 가상환경 활성화:
```bash
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows
```

2. 패키지 설치: 
```bash
pip install -r requirements.txt
```


북마크도 눌렀다가 취소하면 팝업창에서 북마크 안되어있음이라 뜨게 수정하였습니다.
