# MDM Desktop

**The Fastest Document-to-AI Converter**

HWP, HWPX, PDF, DOCX 파일을 깨끗한 Markdown으로 변환하는 데스크톱 앱입니다.

Converts **HWP, HWPX, PDF, DOCX** into clean **Markdown + Media Bundles** optimized for AI/LLM consumption.

## Download

[Releases](https://github.com/seunghan91/mdm-desktop/releases) 페이지에서 다운로드하세요.

| Platform | Status |
|----------|--------|
| macOS (Apple Silicon) | Available |
| macOS (Intel) | Coming soon |
| Windows x64 | Coming soon |

## Features

- 9개 포맷 지원: HWP, HWPX, PDF, DOCX, XLSX, PPTX, HTML, CSV, TXT
- Rust 코어 엔진 — Pandoc보다 23%p 높은 품질, 10-100x 빠름
- 변환 → 뷰어 자동 연결 (렌더/소스/나란히 보기)
- 배치 변환 지원
- 번들 크기 ~9.4MB (Tauri 2.0 + WebView2)

## Tech Stack

- **Core**: Rust (21K LOC)
- **Desktop**: Tauri 2.0 + Svelte 5
- **Design**: iOS 26 inspired Glassmorphism

## Requirements

| Platform | Minimum |
|----------|---------|
| macOS | 12.0 Monterey+ |
| Windows | 10 (with WebView2) |

## License

MIT
