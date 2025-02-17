# 한스크립트 (우리글 지시문)

## 개요
한스크립트(우리글 지시문)는 한국어로 프로그래밍할 수 있도록 설계된 JavaScript 확장 라이브러리입니다. 기존 JavaScript 문법을 최대한 유지하면서도, 변수 및 함수명을 한글화하여 프로그래밍 초보자도 쉽게 이해하고 접근할 수 있도록 구성되었습니다.

최근 HTML 지원이 추가되어, 웹 문서 내에서 한스크립트를 통해 손쉽게 HTML 요소를 조작할 수 있습니다. 또한, CSS 지원이 도입되어 스타일링까지 한글 기반 명령어로 작성할 수 있습니다.

## 특징
- **한국어 기반 문법**: 일반적인 JavaScript 코드 대신 한글 키워드를 사용하여 더욱 직관적인 프로그래밍 환경 제공
- **가독성 향상**: 한글 함수명을 사용하여 코드의 의미를 더 명확하게 표현
- **JavaScript와의 완전한 호환**: 기존 JavaScript 기능을 그대로 활용하면서 한글 기반 함수들을 추가
- **HTML 통합 지원**: 한스크립트를 통해 HTML 요소를 직접 다룰 수 있어, 동적 웹 페이지 구현이 용이
- **CSS 지원 추가**: 스타일링을 위한 CSS 명령어도 한글화하여 제공

## ✅ 장점
1. **한국어 기반 문법으로 직관적**
   - 프로그래밍 초보자도 쉽게 접근 가능
   - 영어가 익숙하지 않은 사용자도 부담 없이 코드 작성 가능

2. **가독성 향상**
   - 한글 함수명으로 코드의 의미를 명확하게 표현
   - 기존 JavaScript 코드보다 직관적인 코드 작성 가능

3. **학습 도구로 적합**
   - 초보자나 학생들이 코딩 개념을 쉽게 익힐 수 있음
   - 한국어로 프로그래밍 개념을 설명하기 용이

4. **기존 JavaScript와 연동 가능**
   - JavaScript의 표준 기능을 그대로 활용하면서 한글 함수 추가 가능
   - 기존 프로젝트에 점진적으로 적용 가능

5. **HTML 및 CSS 지원 추가**
   - HTML 요소와의 직접적인 연동을 통해 동적 웹 페이지 구현 가능
   - CSS 명령어를 통해 스타일링을 한글 기반으로 작성 가능

## ❌ 단점
1. **기존 개발자들에게 익숙하지 않음**
   - 대부분의 개발자는 영어 기반 JavaScript에 익숙하여 새로운 문법에 적응하는 데 시간이 필요함

2. **개발 문서 및 커뮤니티 부족**
   - 기존 JavaScript에 비해 자료가 부족하여 학습에 어려움이 있을 수 있음
   - 관련 오픈소스 프로젝트나 커뮤니티가 아직 많지 않음

3. **실무 적용의 어려움**
   - 대부분의 기업 및 개발 환경에서 영어 기반 JavaScript를 사용하므로 한스크립트를 바로 적용하기 어려울 수 있음
   - 팀 내 협업 시 영어 기반 코드와 혼용하면 오히려 코드 해석이 어려워질 가능성 있음

4. **번역 및 유지보수 문제**
   - JavaScript의 새로운 기능 추가 시 한글화된 문법도 지속적으로 업데이트해야 하는 부담
   - 한글 함수명과 기존 JavaScript 함수명이 혼용될 경우 혼란이 발생할 수 있음

## 설치 및 사용법

### 브라우저 환경
```html
<!-- 한스크립트 라이브러리 로드 -->
<script src="hanscript.js"></script>
<script>
  // 값 설정 및 출력 예시
  값바꿈("메시지", "안녕하세요, 한스크립트!");
  보여주기(값바꿈들["메시지"]);

  // HTML 요소 조작 예시 (HTML 지원 기능)
  한스크립트.요소("제목").innerHTML = "한스크립트와 HTML 지원!";
  
  // CSS 스타일 변경 예시 (CSS 지원 기능)
  한스크립트.스타일_설정("제목", "색", "파랑");
</script>
```

### Node.js 환경
```sh
npm install hanscript
```

```javascript
const 한스크립트 = require("hanscript");

한스크립트.값바꿈("메시지", "안녕하세요!");
한스크립트.보여주기(한스크립트.값바꿈들["메시지"]);
```

## 한스크립트 확장자 (`.hans`)
한스크립트 전용 파일 확장자는 `.hans`입니다. `.hans` 확장자를 사용하면 한스크립트 코드를 독립적인 파일로 관리할 수 있으며, JavaScript와 유사한 방식으로 실행할 수 있습니다.

### `.hans` 파일 예제
```hans
값바꿈("안내", "이것은 한스크립트 파일입니다.");
보여주기(값바꿈들["안내"]);
```

## 기여 방법
이 프로젝트는 오픈 소스로 제공됩니다. 누구나 기여할 수 있으며, 새로운 기능 추가 및 개선 사항을 제안할 수 있습니다.

1. 이 저장소를 포크합니다.
2. 새로운 기능을 개발하거나 버그를 수정합니다.
3. 변경 사항을 커밋한 후 풀 리퀘스트(PR)를 보냅니다.

## 라이선스
한스크립트는 오픈 소스로 제공되며, 자유롭게 사용하고 수정할 수 있습니다. 다만, 이를 사용할 경우 반드시 크레딧을 표기하고, 다음 깃허브 링크를 명시해야 합니다:

[깃허브 링크](https://github.com/lukaaaaaaaaaaaaaaaasssssssssss/hanscript/tree/main)

모든 기여는 오픈 소스 정신을 따릅니다.

**참고:** 현재 HTML, CSS, jsva 지원 기능이 포함되어 있습니다.

2025-02-17 업데이트
수정문의: **looukast** 디스코드
