---
marp: true
theme: gaia
paginate: true
---

# 🧑‍🏫 Markdown으로 슬라이드?  
## Marp로 만드는 간단하고 강력한 프레젠테이션  
### -Marp 소개 및 활용 방법-

---

## 📌 Marp란?

- **Markdown 기반** 슬라이드 제작 도구  
- Marp = **Markdown Presentation Ecosystem**  
- GitHub 기반의 오픈소스  
- PDF, HTML, PPTX 형식으로도 **출력 가능**

👉 발표자료 + 문서 + 강의안 = **하나의 Markdown**

---

## ✅ 왜 Marp?

- 📄 **Markdown 문법만 알면** 누구나 작성 가능  
- ⚡️ 빠른 작성 → 빠른 배포  
- 🎨 **테마(theme)**, 레이아웃 등 다양한 커스터마이징  
- 🧑‍💻 Git 기반 버전 관리에 최적화  
- 💼 실습 자료와 강의안을 **동시에** 작성하기 좋음

---

## 🛠️ Marp 사용 방법

1. **Markdown 파일 작성** (예: `slides.md`)  
2. 슬라이드 구분: `---`  
3. 테마 설정: `theme: gaia` 등  
4. Marp CLI 또는 확장 프로그램으로 슬라이드 변환

💻 VSCode 확장, CLI, Docker 등 다양한 방식 지원

---

## ✨ 예시 슬라이드

```markdown
---
theme: default
paginate: true
---

# Hello, Marp!

- Markdown만으로
- 이렇게 슬라이드를
- 만들 수 있어요!
````

👆 위와 같은 코드를 작성하면 바로 슬라이드 생성!

---

## 🧱 Marp 구성 요소

* **슬라이드 구분자**: `---`
* **메타데이터 영역**: `theme`, `paginate`, `class`, `style`
* **기본 테마**: default, gaia, uncover
* **PDF / PPTX / HTML 변환**: CLI 또는 확장 기능 활용

---

## 💼 Marp 사용 예시

* 교육자료, 강의안
* 학회 및 세미나 발표
* 기술 문서 + 발표자료 동시에 작성
* GitHub Pages로 슬라이드 공유

📢 "문서와 발표자료가 Markdown 하나로 끝난다!"

---

## 🔚 요약 & 다음 단계

* Markdown 기반으로 슬라이드 쉽게 제작
* PDF, HTML, PPTX 등 다양한 출력 가능
* 커스터마이징, 실습자료로도 완벽!

👉 이제 직접 Marp로 만들어봅시다!

---

## 🧑‍🎨 팁: 슬라이드 커스터마이징

* `<!-- _class: lead -->` 같은 클래스 적용
* `style` 속성으로 슬라이드마다 CSS 적용 가능
* `backgroundImage`, `backgroundColor` 설정

💡 Marp는 Markdown의 확장일 뿐!

---

## 🖨️ Marp 출력 방법 (CLI 기반 예시)

```bash
# HTML 슬라이드로 변환
marp slides.md --html

# PDF 출력
marp slides.md --pdf

# PPTX 출력 (Marp CLI 3.x 이상)
marp slides.md --pptx
```

---
## 예시

- [실제 수업 사용 예시](https://expandsource.github.io/tableau_2025/html/16_Histogram.html)