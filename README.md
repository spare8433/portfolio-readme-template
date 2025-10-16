<a id="readme-top"></a>

<br />

<div align="center">
  <h1 align="center">프로젝트명</h1>
  <p>프로젝트 설명</p>
  
  <!-- 프로젝트 대표 이미지 또는 로고 위치 -->

</div>

<br /><br />

<!-- 목차 -->

## 목차

<br />

<ol>
  <li>
    <a href="#프로젝트-소개">프로젝트 소개</a>
    <ul>
      <li>
        <a href="#개발-동기">개발 동기</a>
      </li>
      <li>
        <a href="#프로젝트-개요">프로젝트 개요</a>
      </li>
    </ul>
  </li>
  <li>
    <a href="#주요-기능">주요 기능</a>
  </li>
  <li>
    <a href="#기술-스택">기술 스택</a>
  </li>
  <li>
    <a href="#시작하기">시작하기</a>
    <ul>
      <li>
        <a href="#요구사항">요구사항</a>
      </li>
      <li>
        <a href="#설치-및-실행">설치 및 실행</a>
      </li>
    </ul>
  </li>
  <li>
    <a href="#프로젝트-구조">프로젝트 구조</a>
  </li>
  <li>
    <a href="#주요-구현-사항">주요 구현 사항</a>
  </li>
  <li>
    <a href="#트러블슈팅">트러블슈팅</a>
  </li>
  <li>
    <a href="#개발-리뷰">개발 리뷰</a>
    <ul>
      <li>
        <a href="#배운-점">배운 점</a>
      </li>
      <li>
        <a href="#아쉬운-점">아쉬운 점</a>
      </li>
      <li>
        <a href="#개선-방안">개선 방안</a>
      </li>
    </ul>
  </li>
</ol>

<br /><br />

<!-- 프로젝트 소개 부분 -->

## 프로 젝트 소개


<br />

### 개발 동기

- 왜 이 프로젝트를 시작했는지
- 어떤 문제를 해결하고자 했는지
- 프로젝트를 통해 학습하고자 한 목표

<br />

### 프로젝트 개요

- **개발 기간**: YYYY.MM ~ YYYY.MM (X개월)
- **개발 인원**: 1인 (개인 프로젝트)
- **배포 URL**: [https://example.com](https://example.com/)
  - **테스트 계정**
    - ID: `demo@example.com`
    - PW: `demo1234`
- **데모 URL**: [https://demo.example.com](https://demo.example.com/)

<p align="right">
  (<a href="#readme-top">맨 위로</a>)
</p>

<br /><br />

<!-- 주요 기능 -->

## 주요 기능

<br />

### 1. 기능명 1

![기능 스크린샷 or gif](https://url)

- 기능 설명
- 구현 포인트

### 2. 기능명 2

![기능 스크린샷 or gif](https://url)

- 기능 설명
- 구현 포인트

### 3. 기능명 3

![기능 스크린샷 or gif](https://url)

- 기능 설명
- 구현 포인트

<p align="right">
  (<a href="#readme-top">맨 위로</a>)
</p>

<br /><br />

<!-- 기술 스택 -->

## 기술 스택

### Frontend

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![React Query](https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

- **Framework**: Next.js 14 (App Router)
- **Language**: TypeScript
- **State Management**: React Query, Context API
- **Styling**: Tailwind CSS
- **Testing**: MSW (Mock Service Worker)

<br />

### Backend

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

- **Runtime**: Next.js Route Handlers
- **ORM**: Prisma
- **Database**: MySQL
- **Authentication**: NextAuth.js / JWT

<br />

### DevOps

![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

- **Deployment**: Vercel
- **CI/CD**: GitHub Actions
- **Version Control**: Git, GitHub

<p align="right">
  (<a href="#readme-top">맨 위로</a>)
</p>

<br /><br />

<!-- 시작하기 -->

## 시작하기

<br />

### 요구 사항

- Node.js 18.x 이상
- npm 또는 yarn
- MySQL 8.0 이상

<br />

### 설치 및 실행

#### 1. 저장소 클론

```bash
git clone https://github.com/username/project-name.git
cd project-name

```

#### 2. 환경 변수 설정

```bash
# .env 파일 생성
cp .env.example .env

```

`.env` 파일 내용:

```env
# Database
DATABASE_URL="mysql://user:password@localhost:3306/database_name"

```

#### 3. 의존성 설치

```bash
npm install
# 또는
yarn install

```

#### 4. 데이터베이스 마이그레이션

```bash
npx prisma migrate dev
npx prisma generate

```

#### 5. 개발 서버 실행

```bash
npm run dev
# 또는
yarn dev

```

브라우저에서 [http://localhost:3000](http://localhost:3000/) 접속

<p align="right">
  (<a href="#readme-top">맨 위로</a>)
</p>

<br /><br />

<!-- 프로젝트 구조 -->

## 프로젝트 구조

<br />

```
project-name/
├── prisma/
│   ├── schema.prisma          # 데이터베이스 스키마
│   └── migrations/            # 마이그레이션 파일
├── public/                    # 정적 파일
├── src/
│   ├── app/                   # Next.js App Router
│   │   ├── api/              # API Routes
│   │   ├── (auth)/           # 인증 관련 페이지
│   │   └── ...
│   ├── components/           # 재사용 가능한 컴포넌트
│   │   ├── ui/              # UI 컴포넌트
│   │   ├── features/        # 기능별 컴포넌트
│   │   └── layouts/         # 레이아웃 컴포넌트
│   ├── lib/                 # 유틸리티, 헬퍼 함수
│   ├── hooks/               # 커스텀 훅
│   ├── types/               # TypeScript 타입 정의
│   └── styles/              # 전역 스타일
├── .env.example             # 환경 변수 예시
├── package.json
└── README.md

```

<p align="right">
  (<a href="#readme-top">맨 위로</a>)
</p>

<br /><br />

<!-- 주요 구현 사항 -->

## 주요 구현 사항

<br />

### 1. Prisma를 활용한 타입 안전 API 구축

```typescript
// 예시 코드
import { prisma } from "@/lib/prisma";

export async function getSchedules(userId: string) {
  const schedules = await prisma.schedule.findMany({
    where: { userId },
    include: { tags: true },
  });
  return schedules;
}
```

- Prisma Client로 자동 타입 생성
- TypeScript 전체 환경에서 타입 안정성 확보

<br />

### 2. MSW를 활용한 독립적인 개발 환경

```typescript
// mocks/handlers.ts
import { http, HttpResponse } from "msw";

export const handlers = [
  http.get("/api/schedules", () => {
    return HttpResponse.json([{ id: 1, title: "Sample Schedule" }]);
  }),
];
```

- 백엔드 개발 의존성 제거
- 프론트엔드 독립 개발 가능

<br />

### 3. React Query를 활용한 서버 상태 관리

```typescript
const { data, isLoading } = useQuery({
  queryKey: ["schedules", userId],
  queryFn: () => fetchSchedules(userId),
  staleTime: 5 * 60 * 1000, // 5분
});
```

- 캐싱 전략으로 불필요한 API 호출 감소
- 낙관적 업데이트로 UX 개선

<p align="right">
  (<a href="#readme-top">맨 위로</a>)
</p>

<br /><br />

<!-- 트러블슈팅 -->

## 트러블슈팅

<br />

### 문제 1: 반복 일정 처리 로직 복잡도 증가

**문제 상황**

- 매일/매주/매월 반복되는 일정을 처리할 때 프론트엔드와 백엔드에서 각각 다른 로직 사용
- 데이터 불일치 발생 가능성

**해결 방법**

- DB 스키마 단계에서 반복 규칙을 JSON으로 저장
- 단일 유틸 함수로 반복 일정 생성 로직 통일
- 프론트/백 모두 동일한 로직 사용

**결과**

- 코드 중복 40% 감소
- 유지보수성 향상

<br />

### 문제 2: SMTP 이메일 발송 시 타임아웃 이슈

**문제 상황**

- Nodemailer로 이메일 전송 시 간헐적으로 타임아웃 발생

**해결 방법**

- 이메일 발송을 비동기 큐로 처리
- 타임아웃 설정 조정 (5초 → 30초)
- 재시도 로직 추가

**결과**

- 이메일 발송 성공률 95% → 99.5% 향상

<p align="right">
  (<a href="#readme-top">맨 위로</a>)
</p>

<br /><br />

<!-- 개발 리뷰 -->

## 개발 리뷰

<br />

### 배운 점

- **기술적 학습**

  - Prisma로 타입 안전한 백엔드 구현 경험
  - MSW를 통한 독립적 개발 환경 구축 방법 습득

- **개발 프로세스**
  - 프론트/백 통합 개발로 전체 플로우 이해도 향상
  - CI/CD 구축으로 배포 자동화의 중요성 체감

## 아쉬운 점

- **테스트 코드 부재**

  - 단위 테스트 미작성으로 리팩토링 시 불안함
  - 다음 프로젝트에서는 TDD 또는 최소 Jest 도입 예정

- **반응형 디자인 미흡**
  - 데스크톱 중심 개발로 모바일 UX 고려 부족
  - Tailwind의 반응형 유틸리티 활용도 낮음

<br />

### 개선 방안

- [ ] Jest + React Testing Library 도입
- [ ] 모바일 레이아웃 최적화
- [ ] 성능 모니터링 도구 연동 (Sentry, GA)
- [ ] API 응답 속도 개선 (인덱싱, 쿼리 최적화)

<p align="right">
  (<a href="#readme-top">맨 위로</a>)
</p>

<br />

## 연락

- Email: byeongchan8433@gmail.com
- GitHub: [@spare8433](https://github.com/spare8433)
- Blog: https://spare8433.tistory.com

<p align="right">
  (<a href="#readme-top">맨 위로</a>)
</p>

<br />

## 라이선스

이 프로젝트는 MIT 라이선스를 따릅니다. 자세한 내용은 [LICENSE](https://github.com/spare8433/repository-name/blob/main/LICENSE) 파일을 참고하세요.

<p align="right">
  (<a href="#readme-top">맨 위로</a>)
</p>

<br />
