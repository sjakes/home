# AppCraft - 모바일 앱 개발 회사 홈페이지

혁신적인 모바일 앱 개발 전문 회사 AppCraft의 공식 홈페이지입니다.

## 🌟 주요 기능

- **반응형 디자인**: 모든 디바이스에서 완벽하게 작동
- **모던한 UI/UX**: 최신 디자인 트렌드 적용
- **부드러운 애니메이션**: 스크롤 애니메이션 및 인터랙션 효과
- **섹션 구성**:
  - Hero Section: 매력적인 첫 인상
  - About: 회사 소개 및 통계
  - Services: 제공 서비스 소개
  - Portfolio: 프로젝트 사례
  - Contact: 문의 양식 및 연락처

## 🚀 GitHub Pages 배포 방법

### 1. 저장소 설정

이 프로젝트를 GitHub에 푸시합니다:

```bash
git add .
git commit -m "Initial commit: Add company homepage"
git push origin main
```

### 2. GitHub Pages 활성화

1. GitHub 저장소 페이지로 이동
2. `Settings` 탭 클릭
3. 왼쪽 메뉴에서 `Pages` 클릭
4. `Source` 섹션에서:
   - Branch: `main` 선택
   - Folder: `/ (root)` 선택
5. `Save` 클릭

### 3. 웹사이트 접속

몇 분 후 `https://[your-username].github.io/[repository-name]/`에서 웹사이트를 확인할 수 있습니다.

## 📝 커스터마이징 가이드

### 회사 정보 수정

**index.html**에서 다음 정보를 수정하세요:

- 회사명: `AppCraft`를 원하는 이름으로 변경
- 연락처 정보: 이메일, 전화번호, 주소 수정
- 서비스 내용: Services 섹션의 카드 내용 수정
- 포트폴리오: Portfolio 섹션의 프로젝트 정보 수정

### 색상 테마 변경

**styles.css**의 `:root` 섹션에서 색상을 변경하세요:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #f093fb;
    /* ... */
}
```

### 이미지 추가

1. `images` 폴더 생성
2. 이미지 파일 추가
3. HTML에서 `.image-placeholder` 클래스를 가진 요소를 `<img>` 태그로 교체

## 🛠️ 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: Flexbox, Grid, Animations
- **JavaScript**: Vanilla JS (프레임워크 없음)
- **폰트**: Google Fonts (Poppins)

## 📱 반응형 브레이크포인트

- 데스크톱: 1200px 이상
- 태블릿: 768px ~ 1199px
- 모바일: 767px 이하

## ✨ 주요 기능 설명

### 네비게이션
- 고정 헤더 (스크롤 시 스타일 변경)
- 모바일 햄버거 메뉴
- 부드러운 스크롤 이동

### 애니메이션
- 스크롤 애니메이션
- 호버 효과
- 통계 카운터 애니메이션
- 패럴랙스 효과

### 폼
- 연락처 폼 (현재 클라이언트 사이드만 구현)
- 서버 연동 시 `script.js`의 form submit 핸들러 수정 필요

## 📞 연락처

프로젝트에 대한 문의사항이 있으시면 contact@appcraft.com으로 연락주세요.

## 📄 라이선스

이 프로젝트는 자유롭게 사용 가능합니다.

---

Made with ❤️ by AppCraft
