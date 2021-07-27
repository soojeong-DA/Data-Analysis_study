문서앱 로그 데이터 분석을 통해
- Funnel 방식으로 유저의 행동 패턴을 파악하여, 해당 시나리오의 Bottleneck 구간을 탐색
- 유저를 세분화하여 Bottleneck 개선 방안에 유용한 insight를 도출

[참고]
- [Python 데이터 분석 실무](https://wikidocs.net/book/1867) 의 예제 실습
- [실습 데이터 및 코드](https://github.com/songhunhwa/songhunhwa.github.com/tree/master/tutorial/tutorial_02) songhunhwa(저자)님의 github

---
구간별 전환율       
- 제품내 웹 -> 앱으로 전환하는 구간은 전환율이 양호함(74%)

- 모든 funnel 단계에서 전환율 전반적으로 낮음 (약 20%대)
- 전체적으로 구매정보 -> 구매결제로 이어지는 전환율이 낮아(3.7%) 개선이 시급함
- 바로 전단계인 제품내 -> 구매정보로의 전환율 역시 낮은 편임(23%)


전환율 개선 Target 그룹          
- 클러스터링 결과 PDF 사용 그룹의 전환율 상대적으로 낮아 원인 파악 필요(24%, 타그룹 평균 약35%)
	- 개선 우선순위가 가장 높은(핵심)그룹으로 고려 가능
- PDF 관련 기능 검토 필요 (안정성 등)