# Changelog · 변경 이력

Version numbers follow `0.minor.patch`; unless a version is specified, bump by 0.01 (0.80 → 0.81). Every upload to the repository bumps `VERSION`, this file and the version shown in the editor (`index.html`) together, and adds a `v<version>` tag. 1.0 is used only after an official release ("정식 배포").

버전 번호는 `0.주.보조` 형식이며, 따로 지정하지 않으면 0.01 단위로 올립니다(0.80 → 0.81). 저장소에 올릴 때마다 `VERSION`, 이 파일, 편집기(`index.html`)의 버전 표시를 함께 올리고 `v버전` 태그를 붙입니다. 1.0은 정식 배포 이후에만 씁니다.

## 0.8 (2026-11-03)

First public version, in English and Korean. · 첫 공개 버전(영어·국문).


- English and Korean support, English first. Switch the editor language with the **EN | 한국어** button in the top bar (follows the browser language the first time; your work is kept when you switch).
- New **Article language** setting: the built-in wording of a published article (Source, Copy link, Expand / Collapse, hints) and its `lang` attribute follow it, independently of the editor language. Work files saved before this feature open as Korean articles.
- English example article.
- Separate English and Korean user manuals (`manual/User-Manual.en.*`, `manual/사용매뉴얼.*`).

---

- 영어·국문 지원(영어 먼저). 위쪽 막대의 **EN | 한국어** 단추로 편집기 언어를 바꿉니다(처음에는 브라우저 언어를 따르고, 바꿔도 작업 내용은 유지).
- **기사 언어** 설정 추가: 발행 기사 안의 안내 문구(출처, 링크 복사, 펼치기·접기, 빈 칸 안내)와 `lang` 속성이 편집기 언어와 따로 정해집니다. 언어 기능 이전에 저장한 작업 파일은 국문 기사로 열립니다.
- 영문 예시 기사.
- 영문·국문 사용 매뉴얼 분리(`manual/User-Manual.en.*`, `manual/사용매뉴얼.*`).

---

- 기사 블록 편집기: 소제목, 본문, 인용, 설명 상자, 구분선, 사진, 사진 묶음, 유튜브, 숫자 강조(카운트업), Flourish, 구글 시트 표, 구글 어스·지도, 스크롤리텔링, 기타 임베드
- 배경색, 제목·본문 글꼴(기본 나눔고딕, 글꼴 파일 업로드 가능), 본문 글자 크기, 제목 크기 설정
- 작업 파일(.json) 저장과 열기, 브라우저 자동 저장
- 기사 HTML 파일 한 개로 내보내기(발행하기)와 발행 전 점검
- 사용 매뉴얼(Word, 텍스트) 포함
