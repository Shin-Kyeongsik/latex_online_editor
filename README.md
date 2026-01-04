# LaTeX Online Editor

브라우저에서 **LaTeX 수식 코드를 입력하면 즉시 미리보기를 보여주는** 초경량 웹 에디터입니다. 별도 설치 없이 링크로 접속해 바로 수식을 작성하고, 결과를 확인할 수 있도록 만드는 것을 목표로 합니다. :contentReference[oaicite:1]{index=1}

🔗 Demo: https://latex-online-editor.vercel.app/ :contentReference[oaicite:2]{index=2}

## What you can do

- **실시간 미리보기**: 입력 영역(LaTeX Input)과 결과 영역(Preview)을 나눠, 작성→확인을 빠르게 반복할 수 있습니다. :contentReference[oaicite:3]{index=3}
- **수식 이미지로 저장(PNG)**: 현재 수식을 PNG로 저장할 수 있으며, **DPI(100/150/200/300)** 선택을 지원합니다. :contentReference[oaicite:4]{index=4}
- **정적(Static) 구성**: HTML/CSS 기반의 단순한 구성으로, 로컬에서도 쉽게 실행/수정할 수 있습니다. :contentReference[oaicite:5]{index=5}
- (옵션) **KaTeX 기반 렌더링 전제**: 에디터에서 KaTeX 문서(Help)로 바로 연결되도록 구성되어 있습니다. :contentReference[oaicite:6]{index=6}

## Quick Start (Local)

이 프로젝트는 정적 파일이라, 아래 중 아무 방식으로 실행해도 됩니다.

### 1) 파일을 바로 열기
- `index.html` 또는 `editor.html`을 브라우저로 열기 :contentReference[oaicite:7]{index=7}

### 2) 간단한 로컬 서버로 열기 (권장)
```bash
python -m http.server 8000
# then open http://localhost:8000