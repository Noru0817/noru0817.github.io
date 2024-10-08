---
title: 소프트웨어공학 1주차 - (1)
date: 2024-09-13 18:52:45 +09:00
categories: [3학년 2학기, 소프트웨어공학]
tags: [단기 계획, 3학년 2학기, 소프트웨어공학]
mermaid: true
---

이번 글에선 소프트웨어공학 1주차 내용에 대해 설명해드리려고 합니다.

내용이 다소 많아서 이번엔 (1) ~ (3)에 걸쳐 설명 드릴 예정입니다 😄

## **소프트웨어공학이란?**

소프트웨어공학은 다음의 일련의 과정입니다.

1. **소비자의 문제 해결을**
2. **비용, 시간, 그리고 다른 제약들을 고려한**
3. **시스템적인 개발 및 크고, 높은 질의 소프트웨어 시스템의 진화(발전)를 통하여 진행**

이때 앞서 언급한 '높은 질'에 집중할 필요가 있는데요, 소프트웨어공학에서 말하는 **'질(Quality)'**에는 다음 5가지가 고려됩니다.

1. **효율성 (Efficiency → 수행능력(Performance))**
   → 응답 시간, 처리율, 메모리 사용량
2. **의존성 (Dependability)**
   - 강건성(Robustness) : 어떤 환경 하에서도 제품이 기대되는 성능을 유지하는 것
   - 신뢰성 (Reliability)
   - 가용성 (Availability)
   - 결함 허용 (Fault Tolerance) : 시스템을 구성하는 부품의 일부에서 결함 또는 고장이 발생해도 정상적 또는 부분적으로 기능 수행을 가능하게 하는 것
   - 보안 (Security)
   - 안전 (Safety)
3. **유지보수성 (Maintainability)**
   - 확장성 (Extensibility)
   - 수정 가능성 (Modifiability)
   - 적응성 (Adaptability)
   - 이식성 (Portability, Reusability)
   - 가독성 (Readability)
   - 추적성 (Traceability)
4. **유용성 (Usability)**
   → 사용자가 어떠한 설명이 있지 않더라도 해당 소프트웨어의 사용을 쉽게 익힐 수 있도록 하는 것
5. **유틸리티 (Utility)**

소프트웨어는 누군가 필요로 하기 때문에 만들어집니다. 이때, 이 소프트웨어와 관련된 사람들을 **'이해 관계자(Stakeholders)'**라고 부릅니다. 여기서 이해 관계자는 다음과 같습니다.

1. **사용자**(Users): 소프트웨어를 사용하는 사람
2. **소비자**(Customers) : 소프트웨어를 구매하는 사람
3. **소프트웨어 개발자**(Software developers)
4. **개발 관리자**(Development managers)

물론, 한 사람이 위의 4개의 역할을 모두 가지고 있을 수 있습니다! 😆

### **소프트웨어 질 & 이해 관계자**

![Desktop View](/assets/img/software-engineering/software-quality-stakeholder.jpg){: width="500" height="500" }

#### **소프트웨어 질 : 충돌 및 목적**

서로 다른 질적 요소들은 상호 충돌할 수 있습니다.

#### **충돌 예시**

1. **효율성의 증가는 유지보수성 또는 이식성을 떨어뜨릴 수 있습니다.**
   → 예를 들면 C에서의 인라인 어셈블리 코드 사용이 있습니다. 특정 연산에 있어 어셈블리 코드를 직접 삽입하면 실행 속도는
   빨라지지만, 어셈블리 코드를 모르는 개발자가 해당 코드 분석 시 어려움이 있고, 만약 다른 ISA(Instruction Set Architecture)
   를 사용하는 환경에서는 이식하기 어려워지는 문제가 발생합니다.
2. **유용성의 증가는 효율성을 떨어뜨릴 수 있습니다.**
   → 엔드 유저의 UX만 고려하여 코드를 작성할 경우, 겉으로 보기에는 사용하기 편리하나, 해당 편의성을 제공하기 위해 불필요한
   코드가 많이 작성되어있을 경우, 리소스 사용량이 늘어나는 등 해당 서비스를 제공하는 서버 PC의 처리 속도, 응답 속도 등이 떨어지는
   문제를 야기할 수 있습니다.
3. **최적화 또한 종종 필수적입니다.**
   → E.g.는 가장 높은 가능성을 가진 신뢰성을 고정된 예산 사용 또한 포함합니다.

오늘은 여기까지입니다. 읽어주셔서 감사합니다 😖
