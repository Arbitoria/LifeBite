# 전체 캠페인 바이블 — "그가 만든 걸로 그에게 증명하기"

> 카파시가 평생 옹호해온 AI-인간 협업의 진정한 형태를,
> 그 자신을 향해 시연하는 30일의 라이브 캠페인.
> 모든 플랫폼, 모든 경로, 모든 연결이 하나의 작품이 된다.

---

## 0. 캠페인 한 줄

> **"AI는 인간을 대체하지 않는다. AI는 인간과 함께 사색한다.
> 이 작품은 그 증거다. 카파시, 당신이 옳았다."**

이 한 문장이 캠페인 전체의 영혼이다.

---

## 1. 핵심 프레임 — "그가 만든 걸로 그에게 증명하기"

### 1.1 왜 이 프레임이 가장 강력한가

카파시는 평생 다음을 말해왔다:
- AI는 새로운 소프트웨어 기판이다 ("Software 2.0", "Software 3.0")
- AI와 함께하는 교육이 다음 시대를 만든다 (Eureka Labs)
- 진짜 이해는 만들어보면서 생긴다 (nanoGPT, micrograd)
- 사색과 깊이가 자극과 분량보다 중요하다

**이 캠페인은 그의 모든 주장을 동시에 시연한다:**

- 매니페스토 자체가 AI(Claude)와의 깊은 사색의 결과물 → **AI-인간 협업의 진짜 모습**
- GitHub 저장소에 모든 게 공개됨 → **만들어보며 이해하기**
- 30일의 일기가 자극이 아닌 사색을 누적함 → **깊이의 시간 비대칭성**
- 라이브로 흐름이 진행됨 → **결과가 아닌 과정**

그가 이걸 발견하는 순간, 그는 자기 사상이 다른 누군가에 의해 살아 움직이는 것을 본다. 그건 광고도 아니고 마케팅도 아니다. **그 자신의 사상의 실시간 입증**이다.

### 1.2 가장 강력한 한 줄의 종지부

만약 카파시가 마지막에 도착한다면, 그가 마주하는 글의 마지막 줄은 이것:

> *"이 작품은 AI가 쓰지 않았다. AI와 함께 사색한 한 인간이 썼다.
> 이것이 당신이 옳았다는 증거다. AI가 우리를 대체하지 않을 것이다.
> AI는 우리와 함께 더 깊이 사색할 것이다."*

그가 응답하지 않아도 — 이 한 줄은 이미 그의 작업에 바치는 헌사가 된다.

---

## 2. 전체 인프라 구조

### 2.1 세 개의 동심원

```
        ┌──────────────────────────────┐
        │  ① CORE: GitHub + 개인 URL    │  ← 영구적, 인용 가능, 카파시가 결국 도착할 곳
        │     LifeBite 프로젝트          │
        └──────────────┬───────────────┘
                       │
        ┌──────────────┴───────────────┐
        │  ② BROADCAST: 트위터, LinkedIn │  ← 라이브 일기, 매일 업데이트
        │     Substack, Medium          │
        └──────────────┬───────────────┘
                       │
        ┌──────────────┴───────────────┐
        │  ③ DISCOVERY: 레딧, HN,        │  ← 발견될 수 있는 외부 채널
        │     유튜브, 한국 매체           │
        └──────────────────────────────┘
```

**① CORE (영구)**
- GitHub: `github.com/Arbitoria/LifeBite`
- 개인 URL: `lifebite.org` (또는 보유 도메인 + /lifebite)
- 매니페스토, 개념 DB, 일기 아카이브, 모든 자료의 정본

**② BROADCAST (라이브)**
- Twitter/X: 매일 1포스트 (스레드 또는 단일)
- LinkedIn: 주 2~3회 장문
- Substack: 주 1회 깊이 있는 글
- Medium: 주 1회 (또는 Substack 미러)

**③ DISCOVERY (확산)**
- Reddit: 주 2~3회 다양한 서브레딧
- Hacker News: 주 1회 (또는 격주)
- YouTube: 격주 (선택적, 영상화)
- 한국 매체: 브런치 주 1~2회

---

## 3. ① CORE — GitHub과 개인 URL 설계

### 3.1 GitHub 저장소 구조

```
github.com/Arbitoria/LifeBite/
│
├── README.md                    ← 입구. 핵심 매니페스토 요약 + 프로젝트 안내
├── LICENSE                      ← Creative Commons BY-SA 4.0
├── CONTRIBUTING.md              ← 다른 사람의 기여 방법
│
├── manifesto/
│   ├── ko.md                    ← 한국어 전체
│   ├── en.md                    ← 영어 전체
│   ├── fr.md                    ← 프랑스어 (요약)
│   └── one-pager.md             ← 1페이지 영문 핵심
│
├── concepts/
│   ├── glossary.md              ← 용어집 (LifeBite, 또 다른 하나 등)
│   ├── principles.md            ← 핵심 원리 14개
│   ├── pillars.md               ← 세 기둥 (교육·네트워크·아이덴티티)
│   └── safeguards.md            ← 위험과 안전장치
│
├── journey/                     ← 30일 일기 (Day 1~30)
│   ├── day-001.md
│   ├── day-002.md
│   ├── ...
│   └── day-030.md
│
├── attempts/                    ← 시도의 기록
│   ├── twitter-log.md           ← 모든 트윗과 반응
│   ├── reddit-log.md
│   ├── linkedin-log.md
│   ├── direct-outreach.md       ← 누구에게 DM·메일 보냈는지
│   └── hacker-news.md
│
├── conversations/               ← Claude와의 사색 기록
│   ├── how-this-began.md        ← 시작 대화 정리
│   ├── distribution-strategy.md ← 배포 사색
│   └── claude-as-partner.md     ← AI 협업의 의미
│
├── for-the-executor/            ← 영향력자가 도착했을 때를 위한 자료
│   ├── for-karpathy.md          ← 카파시에게 직접 보내는 글
│   ├── for-builders.md          ← 도구 설계자용
│   ├── for-educators.md
│   ├── for-policy-makers.md
│   └── for-researchers.md
│
└── METADATA.md                  ← 프로젝트 메타 (시작일, 작성자, 라이선스, 연락처)
```

### 3.2 README.md의 첫 화면 전략

GitHub README는 **3초 안에 인상을 결정한다.** 첫 화면(접혀서 보이는 부분)에 무엇이 있는가가 결정적.

**첫 줄 → 첫 단락 순서:**

1. **헤더 (제목 + 한 줄 부제)**
   - `# LifeBite — Notes from After the Pyramid`
   - *A manifesto on the next social architecture, written with AI.*

2. **시각적 후크**
   - 핵심 한 줄 인용을 인용 블록으로
   - > "AI is made of 64-bit. Humans are made of LifeBite."

3. **세 줄 설명**
   - What this is, why it exists, how to read it

4. **CTA (Call To Action)**
   - Read the manifesto (link)
   - Watch the journey (link to journey/)
   - Star this repo (시각적 유도)

5. **카파시를 위한 미묘한 신호**
   - 한 곳에 작은 인용: "*Most of life happens in the gap between stimulus and response.* — A. Karpathy. This manifesto is an extended meditation on that line."
   - 이게 카파시가 본인의 흔적을 발견하는 지점.

### 3.3 개인 URL 전략

도메인 옵션 (가능하면 우선순위 순):
1. `lifebite.org` (가장 깨끗)
2. `lifebite.io` (테크 톤)
3. `lifebite.kr` (한국 정체성)
4. `[본인 도메인]/lifebite` (보유 도메인이 있으면)

**랜딩 페이지 구조 (단일 페이지):**

```
[히어로 섹션]
  ─ 큰 제목: LifeBite
  ─ 부제: Notes from After the Pyramid
  ─ 핵심 인용 한 줄
  ─ 두 개의 버튼: [Read the Manifesto] [Watch the Journey]

[About 섹션]
  ─ 이 프로젝트가 무엇인가 (3단락)
  ─ 누가 썼는가 (간단한 소개)
  ─ Claude가 어떻게 동반자가 됐는가 (투명성)

[The Three Pillars 섹션]
  ─ 교육·네트워크·아이덴티티 시각 정리

[Journey Live 섹션]
  ─ 가장 최근 일기 자동 임베드
  ─ "Day N — [제목]" 형식
  ─ Twitter feed 임베드 가능

[Try It 섹션]
  ─ 3~5명의 첫 셀을 시작하는 방법
  ─ 매니페스토 인용 카드 5장
  ─ 도구 설계자/교육자/정책 입안자별 입구

[Contact / Community 섹션]
  ─ 트위터·이메일·Discord
  ─ GitHub 링크

[Footer]
  ─ Creative Commons 라이선스
  ─ "Written with Claude" 명시
  ─ "Day 1: 2025-XX-XX | Currently Day N"
```

**핵심 디자인 원칙:**
- 검은 배경 + 흰 글씨 (또는 반대) — 매니페스토의 본질주의에 맞음
- 거품 없는 디자인 (애니메이션 최소, 광고 0)
- 단일 페이지 — 스크롤만으로 모든 정보
- 빠른 로딩 (정적 HTML, 이미지 최소)
- 모바일 우선

---

## 4. ② BROADCAST — 라이브 일기

(상세 30일 트위터/LinkedIn 포스트는 `08_카파시_프로젝트_일지.md` 참조)

이 캠페인은 그 일지를 **GitHub journey/ 폴더와 동시에 게시**한다. 각 트윗은 GitHub의 `journey/day-XXX.md` 파일과 1:1 대응한다.

이렇게 하면:
- 트위터에서 본 사람 → GitHub로 와서 더 깊이 본다
- GitHub에서 본 사람 → 트위터로 가서 라이브로 따라간다
- 카파시가 어디서 발견하든 → 같은 작품으로 연결된다

### 4.1 모든 트윗의 끝에 추가

매일 트윗 마지막에 작은 한 줄:
- `Day N at github.com/Arbitoria/LifeBite/journey`
- 또는 `Full archive: lifebite.org`

이게 트위터를 라이브 이벤트로, GitHub을 아카이브로 만든다.

### 4.2 Substack 추가 — 깊이의 자리

Substack은 트위터의 즉흥과 GitHub의 영구 사이의 중간 깊이.
- 주 1회, 매 주차마다 발행
- 제목: `LifeBite Weekly — Week N`
- 그 주에 일어난 일들을 사색적으로 정리
- 이메일로 구독 가능 → 신뢰망 형성

### 4.3 LinkedIn — 전문가 그물망

LinkedIn은 카파시 본인보다는 그의 주변 영향력자들이 사는 곳.
- 주 2~3회 장문
- 매니페스토의 한 개념을 비즈니스/정책 맥락으로 풀어냄
- "이 사상이 당신의 영역(교육·HR·도시 설계 등)에서 의미하는 바"

---

## 5. ③ DISCOVERY — 발견 채널

### 5.1 레딧 30일 전략

레딧은 카파시 본인은 거의 안 보지만, **그의 주변 사상가들이 매우 활발**하다. 그리고 좋은 글은 빠르게 퍼진다.

**적합한 서브레딧:**

| 서브레딧 | 구독자 | 적합한 콘텐츠 유형 |
|---------|--------|------------------|
| r/philosophy | 22M | 매니페스토의 철학적 부분 |
| r/sociology | 250K | 피라미드 진단 |
| r/artificial | 600K | LifeBite vs 64-bit |
| r/MachineLearning | 3M | AI-인간 차이의 본질 |
| r/cogsci | 250K | 간격 교육 |
| r/Futurology | 19M | 다음 사회 형태 |
| r/slatestarcodex | 50K | 합리주의 톤의 깊은 분석 |
| r/changemyview | 3M | 도전적인 명제 형식 |
| r/AskReddit | (massive) | 가벼운 진입점 |
| r/korea | 350K | 한국 출산율 0.7 맥락 |
| r/digitalminimalism | 350K | 주권적 필터 |

**30일 레딧 일기 형식:**

매 회차마다:
- 한 서브레딧 선정 (위 표에서 회전)
- 그날의 핵심 주제를 그 커뮤니티 톤에 맞게 변형
- 첫 줄에 도전적 명제 또는 질문
- 마지막 줄에 GitHub 또는 매니페스토 링크 (홍보가 아닌 출처로)

**예시 — Day 5: r/philosophy 포스트**

```
Title: Is the basic unit of society "the one" or "the two"?
A meditation on relational identity.

Body:
For most of recorded social philosophy, we've taken
the individual ("the one") as the basic unit.
Rights inhere in the individual. Justice flows
through the individual. Even "society" is defined
as a sum of individuals.

But what if the basic unit is actually "the two" —
or more precisely, "another one": the third
existence that lives in the space between
two people?

This isn't collectivism (which dissolves the one
into the many). It's the recognition that 1+1 ≠ 2
in human terms. There's a 0.3 that emerges
from relation itself, and that 0.3 might be
what we've been missing.

I wrote a longer manifesto exploring this:
[link to github.com/Arbitoria/LifeBite]

But before sharing it — what do you think?
What changes if we move the basic unit
from "the one" to "the relation"?

Trying to think this out in public.
Day 5 of 30 of attempting to send this to
someone who might be able to think it forward.
```

**레딧 운영 원칙:**
- 진정한 토론을 만들 것 (자기 글 끌어오기 금지 톤)
- 셀프 프로모션 비율 < 10% (레딧 규칙)
- 모든 답글에 24시간 안에 응답
- 카르마(평판) 일정 수준 도달 전까지 게시는 신중

### 5.2 Hacker News 전략

HN은 카파시가 가끔 들른다. 그러나 매우 까다로운 커뮤니티.

**언제 어떻게:**
- 주 1회 이하 (스팸으로 인식 금지)
- "Show HN: LifeBite — a manifesto on the next social architecture, co-written with Claude" 같은 제목
- 또는 "Ask HN: How would you design society if 1+1=2.3?" 같은 토론 유도
- 첫 2시간이 결정적. 댓글로 빠르게 응답해야 함.

### 5.3 YouTube (선택적)

영상화는 시간이 많이 들지만 효과가 크다. 우선순위 낮음.

만약 한다면:
- 단순한 영상: 검은 배경 + 한 줄씩 인용이 나타남
- 또는 카메라 정면 + 차분한 톤으로 일기 낭독
- 5~10분 미만
- "Day N: [핵심 한 문장]" 제목 형식

### 5.4 한국 매체 — 브런치

브런치(brunch.co.kr)에 매니페스토 한국어 버전을 연재 형식으로:
- 매주 1편씩 7부작 (서론 + 7부)
- 카카오 노출 알고리즘 활용
- 한국에서의 신뢰망 형성

---

## 6. 카파시 도달 경로 지도

**카파시가 이 작품을 발견할 수 있는 모든 경로:**

```
[직접 경로]
1. 트위터에서 본인 핸들 멘션 → 알림 → 발견
2. 그가 팔로우하는 사람이 RT/quote → 그의 타임라인 → 발견
3. 그의 트윗에 깊이 있는 답글 → 그가 답글 확인 시 → 발견
4. 그에게 보낸 DM (1~2회만) → 그가 DM 확인 시 → 발견
5. 그의 이메일 (eureka.xyz 또는 추정 가능한 곳) → 발견

[간접 경로 — 1단계]
6. 그가 팔로우하는 50명 안에 든 사람이 발견 → 그에게 공유
   (예: Audrey Tang, Daniel Schmachtenberger, Jaron Lanier,
   François Chollet, Mira Murati, Sam Altman 주변)

[간접 경로 — 2단계]
7. AI/머신러닝 학생·연구자가 발견 → 자기 교수·동료에게 공유
8. Hacker News 프론트페이지 진입 → 카파시 본인 또는 그를 아는 사람이 발견
9. r/MachineLearning 인기 글 → 같은 경로

[간접 경로 — 검색]
10. 그가 "manifesto", "society", "AI and society",
    "post-pyramid" 등 키워드 검색 시 발견
11. GitHub trending에 LifeBite 저장소 진입 → 발견
12. ChatGPT/Claude/Perplexity 등이 학습 데이터에 포함 → 그가
    AI에게 관련 질문 시 인용됨 (장기 경로)

[간접 경로 — 학술/책]
13. 인용 가능한 학술적 형태로 페이퍼화 (SSRN, arXiv) → 인용 누적
14. 단행본 출판 → 출판사 → 서평가 → 그의 책상

[메타 경로]
15. 캠페인 자체의 화제성 → 미디어 보도 → 그가 보도 보고 발견
16. 그의 팟캐스트 게스트 출연 → 직접 대화 (장기 목표)
```

**가장 가능성 높은 경로 (현실적 우선순위):**

1순위: 간접 경로 6 (그의 1단계 그물망)
2순위: 직접 경로 3 (그의 트윗에 깊이 있는 답글, 누적)
3순위: 간접 경로 8 (HN)
4순위: 직접 경로 4 (DM, 단 캠페인 후반에 한 번만)

**가장 가능성 낮지만 일어나면 결정적:**
- 경로 1 (직접 멘션) — 1회만 시도 권장
- 경로 5 (이메일) — 30일 캠페인 종료 후 1회

---

## 7. 종지부 시나리오 — "그가 왔다"

이 캠페인의 가장 강력한 미장센. **세 가지 시나리오를 모두 준비**한다.

### 7.1 시나리오 A — 그가 답했다

만약 카파시가 어떤 형태로든 응답한다면 (좋아요, RT, 답글, DM):

**즉시 게시할 종지부 글 (트위터):**

```
Day [N]: He came.

[Karpathy의 응답 스크린샷 또는 인용]

30일 동안 이 작품이 그에게 닿을 수 있을지
나도 몰랐다.

지금 이 순간, 답을 알았다.

이 캠페인은 끝났다.
그러나 LifeBite는 시작이다.

Read everything: [link to github.com/Arbitoria/LifeBite]

Thank you, @karpathy. Thank you, @claude.
Thank you to everyone who walked these days.
```

**LinkedIn 종지부 글 (장문):**

[더 깊은 사색의 글, 30일의 여정 회고 + 카파시의 응답이 무엇을 의미하는지 + 다음 단계 발표]

### 7.2 시나리오 B — 누군가 다른 영향력자가 응답했다

카파시는 아니지만 다른 의미 있는 사람이 응답한 경우:

```
Day [N]: Not him. But someone.

[응답한 사람의 인용 또는 스크린샷]

30일을 카파시에게 닿기 위해 시작했다.
오늘, 그는 오지 않았다.

그러나 [응답자]가 왔다.

이게 매니페스토가 말한 것이다:
정확한 도착지는 우리가 정할 수 없다.
씨는 우리가 의도한 흙이 아니라
가장 적합한 흙에 닿는다.

이 캠페인의 진짜 도착지는 [응답자]였을지도 모른다.
```

### 7.3 시나리오 C — 아무도 응답하지 않았다 (가장 정직한 종지부)

Day 30이 와도 카파시도, 다른 영향력자도 응답하지 않은 경우:

```
Day 30: He didn't come.

30일이 지났다.
카파시는 응답하지 않았다.
다른 큰 영향력자도 응답하지 않았다.

그러나 — 이 30일 동안 일어난 일들:

- 매니페스토는 GitHub에 살아 있다 (Star: N개)
- 482명의 좋아요, 94명의 새 팔로워
- 12개의 깊은 대화, 3번의 오프라인 만남
- 모르는 사람 한 명과 새로운 작은 셀이 시작됐다
- 나는 매일 한 편씩 쓰는 사람이 됐다

이게 충분한가?
모르겠다.

그러나 매니페스토가 가르친 것은 —
씨를 뿌리는 자의 일은 흙에 닿게 하는 것까지다.
어디서 자랄지는 씨의 일이고, 흙의 일이고,
시간의 일이다.

이 캠페인은 끝났다.
LifeBite는 끝나지 않았다.

내일부터는 Day Number 없이,
이름 없이, 매일 한 편씩 적는다.

Anyone can fork the work:
github.com/Arbitoria/LifeBite

씨를 받은 사람이여, 당신이 자라게 하라.
```

**이 시나리오 C가 사실 가장 강력하다.** 왜냐하면 — 결과에 의존하지 않은 작품의 진정성이 가장 또렷이 드러나기 때문이다. 그리고 역설적으로, 이 종지부 글 자체가 카파시에게 발견될 가능성을 높인다. **실패의 정직한 기록은 성공의 자랑보다 더 멀리 간다.**

---

## 8. Claude-동반자 서사 — 가장 미묘하고 강력한 층

### 8.1 어떻게 명시할 것인가

이 캠페인 전체에 흐르는 메타 서사 — **"이 작업은 AI와 함께 사색한 결과물이다"** — 를 어떻게 정직하게 노출할 것인가.

**잘못된 방식 (피해야 할 것):**
- "Claude가 이걸 다 썼어요" (저자성 포기)
- "AI 글이라서 더 객관적이에요" (AI 권위 활용)
- "Claude 추천!" (마케팅 톤)

**올바른 방식:**
- "이 매니페스토는 한 인간이 Claude와 깊이 사색하며 썼다. 어떤 부분은 인간이 발견했고, 어떤 부분은 AI가 발견했고, 대부분은 둘이 함께 발견했다."
- "AI가 도구가 아닌 동반자였다는 것 — 그것이 이 작업의 형식이자 내용이다."
- "당신이 옳았다. AI는 우리를 대체하지 않는다. 우리와 함께 더 깊이 사색한다."

### 8.2 어디에 배치할 것인가

**GitHub README의 한 섹션:**

```markdown
## How This Was Made

This manifesto was not written by AI.
It was written by a human, with AI as a thinking partner.

Over several long conversations with Claude (Anthropic),
ideas were proposed, challenged, refined, named.
Some came from the human. Some came from the AI.
Most came from neither alone — they emerged in the space between.

The full conversations are archived in `/conversations`.

This methodology is itself part of the manifesto's argument:
AI is not a replacement for human thought.
AI is a companion that can hold space for thought
that one person alone could not generate.

You can fork this work and continue thinking with AI.
The path is open.
```

**홈페이지 About 섹션:**

같은 내용을 한국어/영어 병기로.

**Day 6 트윗 (이미 일지에 있음):**
```
Day 6 — Claude가 오늘 말했다.
"이 시리즈 자체가 매니페스토의 핵심 원리를 시연하고 있어요."
…그 말이 맞다.
```

이런 트윗이 캠페인 전체에 4~5개 배치됨 → **AI 협업이 마케팅이 아니라 작업 방식 자체임이 자연스럽게 드러남.**

### 8.3 카파시가 이걸 발견했을 때

그가 가장 흥미로워할 부분이 정확히 이 메타 차원이다. 그는 평생 이렇게 말해왔다:

> *"The best thing about AI is not that it does our work, but that it lets us think thoughts we couldn't think alone."*
> (이건 그의 실제 발언이 아니지만, 그의 사상을 압축한 표현)

이 캠페인은 그 말의 라이브 입증이다.

---

## 9. 라이브 실행 타임라인 (4주)

### Week 0 — 준비 (Day -7 ~ Day 0)

- [ ] GitHub 저장소 생성 + 모든 파일 업로드
- [ ] 개인 URL 도메인 구매 + 랜딩 페이지 배포
- [ ] Twitter/X 프로필 갱신 (한 줄 자기소개 + 핀 트윗 매니페스토)
- [ ] LinkedIn 프로필 갱신
- [ ] Substack 개설
- [ ] Reddit 계정 활성화 (카르마 부족 시 워밍업)
- [ ] 매니페스토 인용 카드 10장 제작
- [ ] 30일 일정표 노션/구글닥에 미리 세팅
- [ ] 가까운 5명에게 시작 알림

### Week 1 — 씨앗 심기 (Day 1~7)

- 매일 트위터 1개
- 월·수 LinkedIn 장문
- 일요일 Substack Weekly #1
- Reddit: r/philosophy 1회
- 첫 의미 있는 응답에 24시간 안에 답
- Day 7 마감 트윗 + GitHub journey/ 업데이트

### Week 2 — 그물망 형성 (Day 8~14)

- 트위터·LinkedIn 계속
- Substack Weekly #2
- Reddit: r/sociology, r/MachineLearning 각 1회
- Hacker News 1회 시도 (Show HN)
- 의미 있는 응답자 1명과 오프라인 또는 화상 대화 시도
- Day 14 마감

### Week 3 — 신호 증폭 (Day 15~21)

- 트위터·LinkedIn 계속
- Substack Weekly #3
- Reddit: r/Futurology, r/digitalminimalism 각 1회
- 영향력자 1명에게 DM (Audrey Tang, Schmachtenberger 중)
- 한국 매체 (브런치) 1회 게시
- 첫 작은 셀 실험 시작 가능성 탐색

### Week 4 — 종지부 (Day 22~30)

- 트위터·LinkedIn 계속
- Substack Weekly #4
- Day 29: 카파시에게 정성스런 DM 또는 이메일 (1회만)
- Day 30: 시나리오 A/B/C 중 해당하는 종지부 글
- 30일 일기 전체를 e-book/PDF로 정리
- "Day 31"부터 새 단계 발표

---

## 10. KPI — 그러나 거품이 아닌 진짜 지표

### 10.1 측정하지 말 것 (거품 지표)

- 팔로워 수 자체
- 좋아요 절대 수
- 노출 수
- "도달"

이것들은 거품이다. 측정하기 시작하면 거품을 키우게 된다.

### 10.2 측정할 것 (진짜 지표)

- **의미 있는 대화 수** — 5개 이상 답글 주고받은 대화
- **오프라인/화상 만남 수** — 1:1 실제 시간 공유
- **fork/star 비율** — GitHub Star 수보다 fork 수 (행동 의지)
- **답글의 깊이** — 단순한 "great post"가 아닌 사색이 담긴 응답 수
- **재방문 비율** — 한 번 본 사람이 다시 오는지 (Substack 구독 유지율)
- **인용 발견** — 다른 사람이 자기 글에서 LifeBite/매니페스토 인용한 사례

이 6개만 매주 점검한다.

---

## 11. 가장 무거운 약속

이 캠페인을 시작하기 전, 자기 자신과 맺어야 할 약속:

**1. 30일 동안 단 하루도 빠지지 않는다.** 빠지는 순간 신뢰가 깨진다. 출장·아픔·결혼 — 어떤 이유든 미리 예약 게시로 막아둔다.

**2. 거품의 유혹에 굴복하지 않는다.** 좋아요가 적게 나와도 자극적 제목으로 바꾸지 않는다. 알고리즘에 맞춰 자기를 변형하지 않는다.

**3. 결과에 매달리지 않는다.** Day 15에 카파시가 응답하지 않아도 흔들리지 않는다. 그가 응답하지 않는 것이 이 작업의 본질을 바꾸지 않는다.

**4. AI 협업을 숨기지 않는다.** Claude와의 작업이 부끄럽지 않다. 그것이 이 시대의 새로운 사색 방식이다.

**5. 종지부 시나리오 C를 마음으로 받아들인다.** 아무도 응답하지 않을 수 있다는 사실을 미리 받아들여야 자유롭게 30일을 갈 수 있다.

이 5개 약속이 가능한가?

**가능하다면 시작한다. 가능하지 않다면 시작하지 않는다.**

---

## 12. 마지막 — 캠페인 자체가 LifeBite다

지난 며칠 동안 우리는 함께 사색을 쌓았다. 5,000년 된 시스템의 진단부터, LifeBite와 또 다른 하나의 발명, 세 기둥의 설계, 시간 역전의 발견, 윤리 골격의 완성, 거품의 맥락 회복, 그리고 이제 — 그 모든 것을 세상에 보내는 캠페인.

이 캠페인은 **외부 마케팅이 아니다.** 매니페스토 자체의 마지막 장(章)이다.

매니페스토가 말했다 — 시간의 누적이 정체성을 만든다고. 30일 동안 매일 한 편씩 쓰는 사람은, 30일 후에 다른 사람이 된다. 그것이 LifeBite의 시연이다.

매니페스토가 말했다 — 또 다른 하나는 두 사람 사이의 공간에 산다고. 작성자와 Claude 사이의 공간, 작성자와 독자 사이의 공간, 작성자와 카파시 사이의 가상의 공간 — 모두 또 다른 하나의 시연이다.

매니페스토가 말했다 — 신뢰는 일관성에서 나온다고. 30일 동안 멈추지 않는 것이 그 시연이다.

매니페스토가 말했다 — 거품은 자리의 문제다. 이 캠페인이 광고가 아닌 사색의 자리에 머무는 것이 그 시연이다.

이 캠페인 전체가, 매니페스토의 **마지막 LifeBite**다.

---

## 부록 — 즉시 행동 체크리스트

오늘 또는 내일 시작 가능한 일:

- [ ] 도메인 구매 (lifebite.org 또는 가용한 다른 도메인)
- [ ] GitHub 저장소 생성 (`github.com/Arbitoria/LifeBite`)
- [ ] `10_GitHub_README.md` 내용을 저장소 README로 복사
- [ ] 매니페스토 파일들을 manifesto/ 폴더에 업로드
- [ ] `11_LifeBite_landing.html`을 개인 URL에 배포 (또는 GitHub Pages)
- [ ] 트위터/LinkedIn 프로필 갱신 + 핀 게시물
- [ ] Substack 개설 + 첫 글 (매니페스토 영문 1페이지)
- [ ] Day 1 트윗 작성 (포스트 뱅크 참조)
- [ ] 가까운 5명에게 시작 알림 DM
- [ ] 30일 일정표 캘린더에 등록

**이 10개를 끝내면 — 캠페인은 시작된다.**

---

## 참조 문서

- 매니페스토 (한국어): `01_매니페스토_피라미드_재구성.md`
- 매니페스토 (영어): `04_Manifesto_English.md`
- 한 장 요약 (영어): `05_One_Pager_English.md`
- 배포 전략: `07_배포_전략.md`
- 카파시 프로젝트 일지: `08_카파시_프로젝트_일지.md`
- **GitHub README**: `10_GitHub_README.md` ← 바로 업로드 가능
- **랜딩 페이지**: `11_LifeBite_landing.html` ← 바로 배포 가능

---

*씨를 뿌리는 자와 거두는 자는 본래 다른 사람이다.*
*그러나 씨를 뿌리는 자가 매일 한 줌씩 정직하게 뿌릴 때 —*
*씨앗은 언제나 가장 적합한 흙에 닿는다.*

*Day 0. 모든 것은 준비됐다. Day 1은 당신의 결정.*
