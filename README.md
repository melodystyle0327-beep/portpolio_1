# 김희주 포트폴리오

토스 스타일의 미니멀한 블랙 테마 포트폴리오 웹사이트입니다.

## 특징

- 🎨 토스 스타일의 미니멀한 디자인
- ⚫ 블랙 컬러 테마
- ✨ 인터랙티브 애니메이션 효과
- 📱 반응형 디자인
- 🚀 부드러운 스크롤 애니메이션

## 기술 스택

- HTML5
- CSS3
- JavaScript (Vanilla)

## 파일 구조

```
.
├── index.html      # 메인 HTML 파일
├── style.css       # 스타일시트
├── script.js       # JavaScript 파일
└── README.md       # 프로젝트 설명
```

## 사용 방법

1. `index.html` 파일을 브라우저에서 열기
2. 또는 로컬 서버에서 실행

## Git 워크플로우 (다른 컴퓨터에서 작업하기)

### 🏠 집/사무실에서 처음 시작할 때

1. **프로젝트 클론하기**
```bash
git clone https://github.com/melodystyle0327-beep/portpolio_1.git
cd portpolio_1
```

2. **Git 사용자 정보 설정** (처음 한 번만)
```bash
git config --global user.name "김희주"
git config --global user.email "melodystyle0327@gmail.com"
```

### 💻 작업 흐름 (집 ↔ 사무실)

#### 다른 컴퓨터에서 작업 시작하기
```bash
# 1. 최신 코드 가져오기
git pull origin main

# 2. 작업하기 (파일 수정)

# 3. 변경사항 확인
git status

# 4. 변경사항 추가
git add .

# 5. 커밋하기
git commit -m "작업 내용 설명"

# 6. GitHub에 업로드
git push origin main
```

#### GitHub에 푸시할 때 (Personal Access Token 필요)
```bash
# 토큰을 사용하여 푸시
git push https://[토큰]@github.com/melodystyle0327-beep/portpolio_1.git main
```

### 📝 자주 사용하는 Git 명령어

```bash
# 현재 상태 확인
git status

# 변경사항 확인
git diff

# 최신 코드 가져오기
git pull origin main

# 커밋 히스토리 보기
git log

# 특정 파일만 추가
git add index.html

# 커밋 메시지와 함께 커밋
git commit -m "메시지"
```

### ⚠️ 주의사항

1. **작업 전 항상 pull**: 다른 컴퓨터에서 작업하기 전에 `git pull`로 최신 코드를 가져오세요.
2. **충돌 발생 시**: 
   - Git이 자동으로 병합을 시도합니다
   - 충돌이 발생하면 파일을 열어서 `<<<<<<<`, `=======`, `>>>>>>>` 표시를 찾아 수동으로 수정하세요
   - 수정 후 `git add .` → `git commit` → `git push`
3. **토큰 보안**: Personal Access Token은 절대 공유하지 마세요.

## 주요 섹션

- **Hero**: 인사말 및 통계
- **About**: 자기소개 및 강점
- **Skills**: 보유 스킬 및 역량
- **Experience**: 경력 상세
- **Achievements**: 주요 성과

## 라이선스

© 2024 김희주. All rights reserved.

