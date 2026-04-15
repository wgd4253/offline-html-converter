# Offline HTML Converter

외부 CDN 의존성이 있는 HTML 파일을 폐쇄망에서도 동작하는 단일 파일로 변환합니다.

## 사용법

1. **[converter.html 열기](https://wgd4253.github.io/offline-html-converter/)**
2. HTML 파일을 드래그하거나 클릭하여 선택
3. `원본파일_offline.html` 자동 다운로드

모든 변환은 브라우저 내부에서 수행됩니다. 파일이 서버로 전송되지 않습니다.

## 내장 라이브러리

| 라이브러리 | 용도 |
|---|---|
| Tailwind CSS (CDN JIT) | 유틸리티 CSS |
| Chart.js | 차트 |
| chartjs-plugin-datalabels | 차트 데이터 라벨 |
| chartjs-adapter-date-fns | 날짜 축 어댑터 |
| PapaParse | CSV 파서 |
| Font Awesome 6.4.0 (woff2 포함) | 아이콘 |
| Google Fonts Noto Sans KR | → 시스템 폰트(맑은 고딕) 대체 |

## 특징

- 설치 불필요 — 브라우저만 있으면 동작
- 폐쇄망에서 결과물 사용 가능
- 변환기 자체도 오프라인 동작 (HTML 파일 저장 후 사용)

## 라이선스

- 본 변환기 코드: MIT
- 내장 라이브러리: 각 라이브러리의 원 라이선스 유지 (모두 MIT / OFL / CC BY 4.0)
