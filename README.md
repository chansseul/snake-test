# 🐍 스네이크 게임

구글 스네이크 게임과 유사한 클래식 스네이크 게임입니다.

## 🎮 게임 방법

- 방향키 또는 화면 버튼으로 스네이크 조종
- 빨간 음식을 먹으면 점수 획득 및 길이 증가
- 벽이나 자기 몸에 부딪히면 게임 오버
- 최고 점수는 자동으로 저장됩니다

## 🚀 배포 방법

### Vercel 배포

1. GitHub에 코드를 푸시
2. [Vercel](https://vercel.com)에 접속하여 프로젝트 연결
3. 자동으로 배포됩니다

또는 Vercel CLI 사용:

```bash
npm i -g vercel
vercel
```

### 로컬 실행

```bash
# Python 사용
python -m http.server 3000

# 또는 Node.js 사용
npx serve
```

## 📁 파일 구조

```
.
├── index.html       # 게임 메인 파일
├── package.json     # 프로젝트 설정
├── vercel.json      # Vercel 배포 설정
└── README.md        # 프로젝트 설명
```

## 🎯 기능

- ✅ 부드러운 게임 플레이
- ✅ 점수 및 최고 점수 저장
- ✅ 반응형 디자인
- ✅ 키보드 및 터치 컨트롤
- ✅ 게임 일시정지 기능

