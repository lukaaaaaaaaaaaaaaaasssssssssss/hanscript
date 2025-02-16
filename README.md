# 한스크립트 (우리글 지시문)

## 개요

한스크립트(우리글 지시문)는 한국어로 프로그래밍할 수 있도록 설계된 JavaScript 확장 라이브러리입니다. 기존 JavaScript 문법을 최대한 유지하면서도, 변수 및 함수명을 한글화하여 프로그래밍 초보자도 쉽게 이해하고 접근할 수 있도록 구성되었습니다.

## 특징

- **한국어 기반 문법**: 일반적인 JavaScript 코드 대신 한글 키워드를 사용하여 더욱 직관적인 프로그래밍 환경 제공
- **가독성 향상**: 한국어로 된 함수명과 변수명 덕분에 코드가 직관적으로 읽힘
- **JavaScript와의 완전한 호환**: JavaScript의 기존 기능을 그대로 사용하면서 한글 기반 함수들을 추가하여 활용 가능

---

## ✅ 장점

### 1. **한국어 기반 문법으로 직관적**

- 프로그래밍 초보자도 쉽게 접근할 수 있음
- 영어가 익숙하지 않은 사용자도 쉽게 코드 작성 가능

### 2. **가독성 향상**

- 한글 함수명을 사용하여 코드의 의미를 더 명확하게 표현 가능
- 기존 JavaScript 코드보다 직관적인 코드 작성 가능

### 3. **학습 도구로 적합**

- 초보자나 학생들이 코딩을 배울 때 개념을 쉽게 익힐 수 있도록 도움
- 한국어로 프로그래밍 개념을 설명하기 쉬움

### 4. **기존 JavaScript와 연동 가능**

- JavaScript의 표준 기능을 그대로 활용하면서도 한글 함수 추가 가능
- 기존 프로젝트에도 점진적으로 적용 가능

### 5. **실험적이며 창의적인 접근**

- 한국어 기반 프로그래밍 언어 실험 가능
- 다양한 프로젝트에서 활용 가능

---

## ❌ 단점

### 1. **기존 개발자들에게 익숙하지 않음**

- 대부분의 개발자는 JavaScript의 기존 문법(영어 기반)에 익숙하여 새로운 문법에 적응하는 데 시간이 필요함

### 2. **개발 문서 및 커뮤니티 부족**

- 기존 JavaScript에 비해 자료가 부족하여 학습에 어려움을 겪을 수 있음
- 관련 오픈소스 프로젝트나 커뮤니티가 아직 많지 않음

### 3. **실무 적용의 어려움**

- 대부분의 기업 및 개발 환경에서 영어 기반 JavaScript를 사용하므로 한스크립트를 바로 적용하기 어려울 수 있음
- 팀 내 협업 시 영어 기반 코드와 혼용하면 오히려 코드 해석이 어려워질 가능성 있음

### 4. **번역 및 유지보수 문제**

- JavaScript의 새로운 기능이 추가될 때마다 한글화된 문법도 지속적으로 업데이트해야 하는 부담이 있음
- 한글 함수명과 기존 JavaScript 함수명이 혼용될 경우 혼란이 발생할 가능성 있음

---

## 설치 및 사용법

```html
<script src="hanscript.js"></script>
<script>
  값바꿈("메시지", "안녕하세요, 한스크립트!");
  보여주기(값바꿈들["메시지"]);
</script>
```

또는 Node.js 환경에서 사용하려면:

```sh
npm install hanscript
```

```js
const 한스크립트 = require("hanscript");
한스크립트.값바꿈("메시지", "안녕하세요!");
한스크립트.보여주기(한스크립트.값바꿈들["메시지"]);
```

---

## 기여 방법

이 프로젝트는 오픈 소스로 제공됩니다. 누구나 기여할 수 있으며, 새로운 기능 추가 및 개선 사항을 제안할 수 있습니다.

1. 이 저장소를 포크합니다.
2. 새로운 기능을 개발하거나 버그를 수정합니다.
3. 변경 사항을 커밋한 후 풀 리퀘스트(PR)를 보냅니다.

---

## 라이선스

한스크립트는 오픈 소스로 제공되며, 자유롭게 사용하고 수정할 수 있습니다. 다만, 이를 사용할 경우 반드시 크레딧을 표기하고, 다음 깃허브 링크를 명시해야 합니다:

**[깃허브 링크 추가 예정]**

모든 기여는 오픈 소스 정신을 따릅니다.

