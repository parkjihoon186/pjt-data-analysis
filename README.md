# pjt-data-analysis
Sesac LLM DA 1차 프로젝트 1st 

1. 프로젝트 개요 (Project Overview)

프로젝트의 목적을 한두 문장으로 요약한다.

olist가 제공하는 브라질 전자상거래 공개 데이터 를 활용하여 주(State)별 시장 침투율을 분석하고, 고객 행동 패턴을 파악하여 비즈니스 성장 전략을 제안하는 프로젝트이다. 

2. 데이터 출처 (Data Source)

Olist Public Dataset (customers, orders,products,review)

IBGE (브라질 인구 통계)

3. 분석 목표 (Analysis Goal)

우리는 이분석으로 고객이 1회만 구매하는 이유는 무엇일까를 중점으로 살펴보았다.

주요 주(State)별 고객 침투율은 어떠한가?

침투율로는 상파울로우가 가장 높게 나왔다는것을 알수있었습니다. 

고객들의 구매 행동 패턴은 어떠한가? (RFM 분석)

이 RFM 분석결과를 통해 1회성 고객인걸 파악할수있다  이는 itaquera 지역에만 국한된것이아니라 전체지역에서 성향이 나타나고있다

Olist의 비즈니스 성장을 위한 핵심 문제점과 해결책은 무엇인가?

4. 분석 과정 (Analysis Process)

간단한 목차 형식으로 진행 과정을 요약합니다.

데이터 불러오기 및 전처리 (인구 데이터 정제, Null 값 처리 등)

고객 침투율 계산 및 시각화

RFM(Recency, Frequency, Monetary) 분석을 통한 고객 행동 패턴 파악

인기 상품 및 매출 분석

문제점(낮은 재구매율, 배송 지연 등)에 대한 원인 분석

5. 주요 결과 및 결론 (Key Findings & Conclusion)

분석을 통해 얻은 가장 중요한 인사이트를 정리합니다.

상파울루는 고객 수와 침투율 모두 높다.

대부분의 고객은 1회성 구매자이며, 재구매율이 낮다.

인기 상품과 매출 기여도가 높은 상품이 다르다.

핵심 문제점은 배송 지연과 같은 운영 이슈와 관련이 있다.

6. 기술 스택 (Tech Stack)

프로젝트에 사용된 주요 도구를 나열합니다.

Python

Pandas

Matplotlib

Seaborn