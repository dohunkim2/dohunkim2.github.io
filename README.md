# Dohun Kim (김도훈) - Academic CV & Homepage

Jon Barron 학술 홈페이지 템플릿([jonbarron.github.io](https://github.com/jonbarron/jonbarron.github.io.git)) 기반으로 구축된 CV 웹페이지입니다.

---

## 🌟 주요 특징

1. **PNG, JPG, WebP, GIF 등 모든 이미지 포맷 100% 지원**:
   - 투명 배경 PNG는 물론 일반 사진(JPG), 움직이는 GIF 모두 지원됩니다.
2. **이미지가 없을 땐 깔끔한 '줄글(Text-First)' 형태로 자동 전환**:
   - 폴더에 이미지가 없거나 비어 있으면, 어색한 썸네일 빈칸 없이 **깔끔하고 격조 있는 학술 줄글 형식(100% 폭)**으로 자동 표시됩니다.
   - 폴더에 이미지를 넣으면 즉시 Jon Barron 특유의 **2열 썸네일 + 마우스 호버 애니메이션** 형태로 업그레이드됩니다.
3. **LaTeX CV 내용 100% 반영**:
   - 학력, 연구실 경력, 논문(CIKM 2026, CKAIA 2026/2025), 수상 내역, MPEG 표준 기고서, 과제, 스킬, 교육 경험이 온전히 반영되어 있습니다.

---

## 📁 폴더 구조

각 항목별로 분리된 독립 폴더에 이미지를 넣기만 하면 됩니다:

```text
CV_webpage/
├── index.html                  # 메인 CV 웹페이지
├── stylesheet.css               # 반응형 디자인 & 타이포그래피 스타일
│
├── images/
│   ├── profile/                # 프로필 사진 (예: profile.png 또는 profile.jpg)
│   ├── publications/
│   │   ├── cikm2026/           # CIKM 2026 이미지 (preview.png, hover.png)
│   │   ├── ckaia2026/          # CKAIA 2026 이미지 (preview.png, hover.png)
│   │   └── ckaia2025/          # CKAIA 2025 이미지 (preview.png, hover.png)
│   └── projects/
│       ├── knpa2025/           # 경찰청 과제 이미지 (preview.png)
│       └── etri2024/           # ETRI 과제 이미지 (preview.png)
│
├── data/
│   └── cv.pdf                  # CV PDF 파일 (다운로드용)
│
└── README.md                   # 본 문서
```

---

## 🖼️ 이미지 사용 안내

- **이미지를 넣고 싶을 때**:
  - 해당 폴더에 `preview.png` (또는 `.jpg`), 마우스 호버용 `hover.png`를 넣으시면 됩니다.
- **이미지를 안 넣을 때**:
  - 아무것도 넣지 않으셔도 기본적으로 깔끔하고 미니멀한 줄글 텍스트 레이아웃으로 완벽하게 보입니다.

---

## 🚀 배포 정보

- 저장소: [https://github.com/dohunkim2/dhkim.github.io](https://github.com/dohunkim2/dhkim.github.io)
- GitHub 저장소 설정(**Settings** > **Pages**)에서 `Branch: main`을 선택하시면 배포가 활성화됩니다.
