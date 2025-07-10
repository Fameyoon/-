# -
홈페이지 제작 with 이명박

# 🛰️ 홉페이지 프로젝트 (Astro 기반)

회사 브랜드와 콘텐츠(강의, 유튜브 등)를 홍보하기 위한 정적 웹사이트입니다.  
Astro 프레임워크를 기반으로 빠른 속도와 간결한 구조를 추구하며, 비전공자도 Markdown 파일 등을 통해 쉽게 콘텐츠 기여가 가능합니다.

---

## 🧱 기술 스택

- [Astro](https://astro.build/) – 정적 사이트 프레임워크
- HTML / CSS / JavaScript
- Markdown – 블로그 및 후기 콘텐츠 작성용
- GitHub Pages / Vercel – 배포 플랫폼 (선택)
- (선택적으로) React 컴포넌트 삽입 가능

---

## 📂 프로젝트 구조

```bash
/
├── public/               # 이미지 및 정적 자산
├── src/
│   ├── pages/            # 개별 페이지 (index.astro 등)
│   ├── components/       # 재사용 UI 컴포넌트
│   ├── layouts/          # 공통 레이아웃
├── posts/                # 마크다운 기반 콘텐츠 (후기, 블로그)
├── astro.config.mjs      # Astro 설정 파일
├── package.json
└── README.md
