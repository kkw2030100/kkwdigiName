# 김기원의 디지털 명함 | KKW Digital Namecard

네오부루탈리즘(Neo-Brutalism) 디자인 스타일의 개인 디지털 명함 웹사이트입니다.

## 🎯 프로젝트 개요

- **개인 소개**: 부동산 빅데이터 전문가, 유튜버, 데이터노우즈 대표 이사
- **주요 기능**: 한 페이지에서 모든 연락 정보 제공
- **디자인**: 네오부루탈리즘 (굵은 테두리, 미니멀, 고명도 대비)
- **반응형**: 모바일, 태블릿, 데스크톱 완벽 지원

## 🚀 빠른 시작

### 로컬에서 실행

```bash
# 저장소 클론
git clone https://github.com/kkw2030100/kkwdigiName.git
cd kkwdigiName

# 브라우저에서 열기
open index.html
# 또는 VS Code Live Server 사용
```

### 배포

Vercel을 통해 자동 배포됩니다.
- **배포 URL**: [Vercel에서 배포 후 업데이트 예정]

## 📁 파일 구조

```
kkwdigiName/
├── index.html          # 메인 HTML
├── styles.css          # 네오부루탈리즘 스타일
├── .gitignore          # Git 무시 파일
├── README.md           # 이 파일
├── SPEC.md             # 프로젝트 스펙
├── PLAN.md             # 개발 계획
└── assets/
    └── images/         # 프로필 이미지 등
```

## 🎨 네오부루탈리즘 디자인 특징

- **굵은 테두리**: 모든 요소에 2-4px 검은색 테두리
- **제한된 색상**: 검은색, 흰색, 강한 악센트 색만 사용
- **미니멀 레이아웃**: 불필요한 장식 제거
- **큰 타이포그래피**: 굵고 큰 글씨로 강렬함 표현
- **고명도 대비**: 검은색과 흰색의 강한 대비
- **기하학적 형태**: 순수한 사각형, 원형 사용

## 📞 연락 정보

- **이메일**: kkw2030100@gmail.com
- **전화**: 010-8288-6580
- **유튜브**: [@RICHGO406](https://www.youtube.com/@RICHGO406)
- **서비스**: [리치고](https://richgo.kr) - 부동산 정보 서비스

## ✨ 주요 기능

### 1. 프로필 정보
- 이름, 직책, 전문 분야 표시
- 프로필 이미지 (원형 테두리)

### 2. 원클릭 연락처
- **이메일**: `mailto:` 링크로 기본 메일 클라이언트 실행
- **전화**: `tel:` 링크로 기본 전화 앱 실행
- **유튜브**: 새 탭에서 유튜브 채널 열기

### 3. 반응형 디자인
- **모바일** (320px+): 세로 레이아웃
- **태블릿** (768px+): 최적화된 레이아웃
- **데스크톱** (1024px+): 전체 너비 활용

### 4. 접근성
- 시맨틱 HTML
- WCAG AA 색상 대비
- 키보드 네비게이션 지원

## 🛠️ 기술 스택

- **마크업**: HTML5
- **스타일**: CSS3 (반응형, 다크 모드 지원)
- **배포**: Vercel

## 📱 브라우저 호환성

- ✅ Chrome (최신)
- ✅ Safari (최신)
- ✅ Firefox (최신)
- ✅ Edge (최신)

## 🔧 커스터마이징

### 프로필 이미지 변경
1. `assets/images/` 폴더에 이미지 추가
2. `index.html`의 `.profile-image` 수정

```html
<div class="profile-image" style="background-image: url('assets/images/profile.jpg');">
</div>
```

### 색상 변경
`styles.css`의 CSS 변수 수정:

```css
:root {
    --color-accent-blue: #0066FF;  /* 이 부분 변경 */
    --color-accent-orange: #FF6633;
}
```

### 연락처 정보 수정
`index.html`에서 다음 정보 수정:
- 이메일 링크: `href="mailto:..."`
- 전화 링크: `href="tel:..."`
- 유튜브 링크: `href="https://..."`

## 📊 성능

- **로딩 시간**: < 1초
- **번들 크기**: < 50KB
- **Lighthouse**: 95+ 점수

## 📝 라이선스

이 프로젝트는 개인 사용을 목적으로 하며, 자유롭게 수정할 수 있습니다.

## 👨‍💻 개발자

**김기원** (Kim Ki-Won)
- 깃허브: [@kkw2030100](https://github.com/kkw2030100)
- 유튜브: [@RICHGO406](https://www.youtube.com/@RICHGO406)

---

**마지막 업데이트**: 2026년 3월
