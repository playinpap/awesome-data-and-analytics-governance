# Contents : `Awesome Reference`

`Awesome Data & Analytics Governance`는 **데이터 & 분석 거버넌스** 개선에 기여하는 것을 목적으로 합니다.   
이 때 데이터 & 분석 거버넌스란, 데이터를 활용하는 **문화**와 이를 뒷받침할 수 있는 **인프라**, 크게 이 두 축으로 의미를 한정합니다.

1. 데이터 & 분석 거버넌스에 대한 소개 및 진단지 샘플 제공 : [**Awesome Diagnosis**](./README.md/#awesome-diagnosis)
2. 데이터 & 분석 거버넌스 개선에 참고할 수 있는 양질의 자료 수집 : [**Awesome Reference**](./CONTENTS.md)
3. 데이터 & 분석 거버넌스에 대해 묻고 답하거나 토론할 수 있는 공간 제공 : [**Awesome Discussion**](https://github.com/playinpap/awesome-data-governance/discussions)

`Awesome Reference` 는 실제로 task 를 진행하면서 읽어보았던, 혹은 참고했었던 레퍼런스들을 모은 공간입니다.   
찾아와주신 여러분들에게도 도움이 되는 자료가 되길 바랍니다.

<br/>

---
## Table of Contents

* [KPI / Metric](#kpi---metric)
  * 좋은 정량적인 목표, 지표를 개발하기 위해선 어떻게 해야할까요?
* [Communication](#communication)
  * 올바른 데이터 활용을 위해 여러 직군끼리 어떻게 협업해야 할까요?
* [Data Logging](#data-logging)
  * 어떻게 하면 품질 좋은 데이터 수집을 위한 문화와 프로세스를 만들어나갈 수 있을까요?
* [Data Warehouse / Mart](#data-warehouse---mart)
  * 안정적이고 신뢰할 수 있는 데이터 파이프라인을 설계하기 위해선 어떻게 해야할까요?
  * 데이터 분석에 용이한 형태로 데이터 구조를 설계할 순 없을까요?
* [Data Discovery](#data-discovery)
  * 수많은 데이터 중, 사용자들이 원하는 데이터를 빠르고 정확하게 찾기 위해선 어떻게 해야할까요?
* [Team Building](#team-building)
  * 회사의 분석 문화 수준을 제고시키기 위해서 데이터 전담 조직을 어떻게 세팅해야할까요?

<br/>

## KPI / Metric

* [[Book] Product Analytics: Applied Data Science Techniques for Actionable Consumer Insights](https://www.amazon.com/Applied-Data-Science-Transforming-Actionable/dp/0135258529)
* [[Book] A Practical Guide to A/B Testing: Trustworthy online controlled experiments](https://www.amazon.com/Trustworthy-Online-Controlled-Experiments-Practical/dp/1108724264)
* [[Web Site] DMR - Your Home for Statistics and Gadgets](https://expandedramblings.com/)
* [[Video] Connecting Inputs to Outputs at Udemy](https://amplitude.com/amplify-sessions?wchannelid=emyjmwjf79&wmediaid=rg1ahklebd)
* [[Slide] Amplitude - North Start Guide Book](https://amplitude.com/north-star)
* [[Article] 한글 번역 - Udemy에서 Input Metric을 Output Metric에 연결하는 방법](https://medium.com/bondata/amplify-2022-udemy-f34c398f4c74)
* [[Article] This is How Amazon Measures Itself](https://www.holistics.io/blog/how-amazon-measures/)
* [[Article] The Guide to Product Metrics](https://mixpanel.com/de/content/guide-to-product-metrics/full-report/)

<br/>

## Communication

* [[Article] 지표선정 자리에서 해야하는 5가지 질문들 — Data Analyst의 컨설팅](https://medium.com/alexandersyoon/%EC%A7%80%ED%91%9C%EC%84%A0%EC%A0%95-%EC%9E%90%EB%A6%AC%EC%97%90%EC%84%9C-%ED%95%B4%EC%95%BC%ED%95%98%EB%8A%94-5%EA%B0%80%EC%A7%80-%EC%A7%88%EB%AC%B8%EB%93%A4-data-analyst-%EC%9D%98-%EC%BB%A8%EC%84%A4%ED%8C%85-f7012d61a572)
* [[Article] 프로덕트 매니저를 위한 데이터 분석가 협업 가이드 — Product Sprint 편](https://medium.com/alexandersyoon/%ED%94%84%EB%A1%9C%EB%8D%95%ED%8A%B8-%EB%A7%A4%EB%8B%88%EC%A0%80%EB%A5%BC-%EC%9C%84%ED%95%9C-%EB%8D%B0%EC%9D%B4%ED%84%B0-%EB%B6%84%EC%84%9D%EA%B0%80-%ED%98%91%EC%97%85-%EA%B0%80%EC%9D%B4%EB%93%9C-become-best-workplace-buddies-af821839ac7b)

<br/>

## Data Logging
  
* [[Article] 데이터 로그 설계, 데이터 로깅, 이벤트 로그 설계, 데이터 QA의 모든 것](https://zzsza.github.io/data/2021/06/13/data-event-log-definition/)
* [[Article] 모바일 앱 로그분석, 어떻게 시작해야 할까?](https://brunch.co.kr/@leoyang99/15)

<br/>

## Data Warehouse / Mart

* [[Tool] dbt: data build tool](https://www.getdbt.com/)
* [[Tool] greatexpectation: data profiling & quality check tool](https://greatexpectations.io)
* [[Tool] deequ: data unit testing tool for spark](https://github.com/awslabs/deequ)
* [[Tool] python-deequ: data unit testing tool for spark](https://github.com/awslabs/python-deequ)
* [[Book] Data Warehouse Toolkit: The Definitive Guide to Dimensional Modeling, 3rd Edition](https://www.amazon.com/Data-Warehouse-Toolkit-Definitive-Dimensional/dp/1118530802)
* [[Book] 데이터 파이프라인 핵심 가이드, 성공적인 데이터 분석을 위한 인프라 설계와 구축](http://www.kyobobook.co.kr/product/detailViewKor.laf?mallGb=KOR&ejkGb=KOR&barcode=9791158393045)
* [[Book] 데이터 중심 애플리케이션 설계](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791158390983&orderClick=LEa&Kc=)
* [[Article] The Analytics Engineering Guide](https://www.getdbt.com/analytics-engineering/)
* [[Article] GitLab - SQL Style Guide](https://about.gitlab.com/handbook/business-technology/data-team/platform/sql-style-guide/)
* [[Article] 데이터에 신뢰성과 재사용성까지, Analytics Engineering with dbt](https://tech.socarcorp.kr/data/2022/07/25/analytics-engineering-with-dbt.html)
* [[Article] How Airbnb Achieved Metric Consistency at Scale](https://medium.com/airbnb-engineering/how-airbnb-achieved-metric-consistency-at-scale-f23cc53dea70)[^metric_standard]
* [[Article] The Journey Towards Metric Standardization](https://www.uber.com/en-US/blog/umetric/)[^metric_standard]

<br/>

## Data Discovery

* [[Tool] Datahub](https://datahubproject.io/)
* [[Tool] Amundsen](https://www.amundsen.io)
* [[Tool] Open Data Discovery](https://github.com/opendatadiscovery/odd-platform)
* [[Article] 데이터 디스커버리 플랫폼 도입기 - 1편. 데이터 디스커버리란?(feat. Datahub VS Amundsen 비교 분석)](https://tech.socarcorp.kr/data/2022/02/25/data-discovery-platform-01.html)

<br/>

## Team Building

* 

<br/>

### Footnote

[^metric_standard]: '전사적으로 지표를 어떻게 일관되게 관리할 수 있을지' 고민에 대한 레퍼런스
