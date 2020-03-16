# SPC 시스템
- SPC는 Statistical Process Control의 약자로서 통계적 공정관리를 의미한다. 
- 공정에 얻어진 DATA(검사 DATA)를 통계적으로 해석하여 샘플 DATA에 의한 평가의 오류를 최소화하여 품질문제 예방
- 검사 DATA의 통계해석, 관리도, 공정능력 도구 제공
- 끊임없는 공정의 개선 추구와 만족스러운 품질의 제품을 높은 생산성으로 생산할 수 있도록 하는 현장 관리기법.
  (즉 "Never Ending Improvement Program"으로서 개선을 위하여 연속적으로 적용해 가야 할 관리기법)
- SPC를 통하여 우리가 목표로 하는 가장 중요한 것은 품질 산포가 작은 균일한 품질의 제품을 생산. 
  즉 SPC적 관리를 통하여 공정변동을 줄여 가고자 함.
  
  ![산포의 의미](http://www.spclink.co.kr/images/sub0101a.jpg)

# SPC 시스템 요구사항
- 정확한 검사 DATA를 실시간 저장,분석
- 특별 특성제품의 핵심공정을 대상
- 관리도에 의한 공정관리
- 공정별 공정능력의 통계적 계산과 평가

# SPC 시스템 통계분석 제공 내용
- 공정 모니터
- 관리도(계량치, 계수치)와 공정능력 분석
- 입력변수(X인자)와 결과변수(Y인자)의 통합관리
- 측정 데이터 변수들의 상관분석 및 다변량 분석
- 비교대상 통계량의 추정과 검정에 따른 해석 지원

# QC7 도구

1.특성요인도(cause-effect diagram)

2.층별(stratification)

3.체크시트(check sheet)

4.히스토그램(histogram)

5.산점도(scatter diagram)

6.파레토그래프(Pareto's graph)

7.관리도(control chart)와 그래프(graph)

# SPC 시스템 DB Spec
- SQL Server 2017 성능(InMemory, CCI)

  > 검사 항목이 많은 통계적 공정 관리 시스템의 경우 트랜잭션이 상당하다. SQL Server 2014의 OLTP 인메모리 기능을 평가해 보면서 데이터 입출력이 급증해도 데이터베이스 잠김(Lock & Latch) 현상이 없다는 것과 잠김 없이 데이터 일관성 보장이 가능하다는 것이 매우 인상적이었다. OLTP 처리 속도는 인메모리 컴파일러를 통해 네이티브 코드를 만들었을 때 24배 가까이 빨라졌다. 그리고 평소 느리다는 소리를 듣던 조회 시스템도 CCI(Clustered Columnstore Indexes)를 적용해보니 처리 속도가 22배나 증가했다 (삼성전기 생산기술연구소 MES그룹김명수 수석)
  
  
