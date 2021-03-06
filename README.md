# SPC 시스템
- SPC는 Statistical Process Control의 약자로서 통계적 공정관리를 의미한다. 

- 공정에 얻어진 DATA(검사 DATA)를 통계적으로 해석하여 샘플 DATA에 의한 평가의 오류를 최소화하여 품질문제 예방

- 검사 DATA의 통계해석, 관리도, 공정능력 도구 제공

- 끊임없는 공정의 개선 추구와 만족스러운 품질의 제품을 높은 생산성으로 생산할 수 있도록 하는 현장 관리기법.
  (즉 "Never Ending Improvement Program"으로서 개선을 위하여 연속적으로 적용해 가야 할 관리기법)
  
- SPC를 통하여 우리가 목표로 하는 가장 중요한 것은 품질 산포가 작은 균일한 품질의 제품을 생산. 
  즉 SPC적 관리를 통하여 공정변동을 줄여 가고자 함.
  
  ![산포의 의미](http://www.spclink.co.kr/images/sub0101a.jpg)
  
  6시그마 : 관리의 상/하한을 6 * 표준편차 범위안에 넣는다, 100만번 중 3,4번 오류(99.96) vs 3시그마 : 99.7% 범위

- TPS(Toyota Production System)의 3대 기둥 : JIT(필요한 제품을 필요한 때에 필요한 만큼 생산) + IAS(문제 발생시 자동으로 공정멈춤) + 1인공 추구(최소한의 인원으로 생산) , 품질관리(4M변경시 초물검사, 자주검사:불량 안보냄, 순차검사:불량안받음) 

# SPC 시스템 요구사항

- 정확한 검사 DATA를 실시간 저장,분석

- 특별 특성제품의 핵심공정을 대상

- 관리도에 의한 공정관리

- 공정별 공정능력의 통계적 계산과 평가

# SPC 시스템 통계분석 제공 내용

- 공정 모니터

- 관리도(계량치, 계수치)와 공정능력 분석

  [공정능력분석(Cp,Cpk,Pp,Ppk)](http://blog.naver.com/PostView.nhn?blogId=jiwoo6941&logNo=220248030868&categoryNo=25&parentCategoryNo=0&viewDate=&currentPage=1&postListTopCurrentPage=1&from=search&userTopListOpen=true&userTopListCount=10&userTopListManageOpen=false&userTopListCurrentPage=1)  
  
  [공정능력 CP, CPK, 시그마수준](https://walkingfox.tistory.com/11)
  
  [평균 그리고 표준편차의 개념](https://walkingfox.tistory.com/10)
  
  [3시그마 규칙 ( 68-95-99.7 규칙 )](https://walkingfox.tistory.com/118?category=628022)
  
- 입력변수(X인자)와 결과변수(Y인자)의 통합관리

- 측정 데이터 변수들의 상관분석 및 다변량 분석

- 비교대상 통계량의 추정과 검정에 따른 해석 지원

# QC7 도구

1. 체크시트(check sheet)

  - 목적: 데이터의 수집과 분석

  - 용도: 데이터의 도식화, 예방점검
  
2. 파레토그래프(Pareto's graph)

  - 목적: 개선활동의 우선순위를 결정

  - 용도: 현상태의 문제점 파악, 개선효과의 확인 
  
  - [Pareto Chart(파레토 차트)](https://m.blog.naver.com/PostView.nhn?blogId=kdoil4532&logNo=221259838864&proxyReferer=https:%2F%2Fwww.google.com%2F) 
  
  - [Pareto Analysis and Check Sheets](http://owic.oregonstate.edu/sites/default/files/pubs/EM8771.pdf) 

3. 히스트그램(histogram)

  - 목적: 품질데이터의 산포를 파악

  - 용도: 분포의 모양파악 및 규격대비, 공정능력 파악
  
  - [확률분포 적합성](http://www.databaser.net/moniwiki/wiki.php/%ED%99%95%EB%A5%A0%EB%B6%84%ED%8F%AC%EC%A0%81%ED%95%A9%EC%84%B1)

4. 관리도(control chart) 및 그래프(graph)

  - 목적: 데이터의 시각화와 공정의 이상여부 파악

  - 용도: 데이터의 시각화, 공정의 관리 및 해석
  
  - [엑셀을 활용하여 XBar-R관리도 그리기](http://blog.naver.com/PostView.nhn?blogId=jiwoo6941&logNo=220248024509&parentCategoryNo=&categoryNo=25&viewDate=&isShowPopularPosts=true&from=search) 
  
  - [관리도핵심요약](https://slidesplayer.org/slide/14294125/) 
  
  - [품질 실무 관리도](http://www.hansung.ac.kr/web/quality-mgmt/4?p_p_id=EXT_BBS&p_p_lifecycle=1&p_p_state=exclusive&p_p_mode=view&p_p_col_id=column-1&p_p_col_count=1&_EXT_BBS_struts_action=%2Fext%2Fbbs%2Fget_file&_EXT_BBS_extFileId=659777) 
  
  - [불량율에 대한 시그마 수준과 불량율에 대한 Cpk](http://blog.naver.com/PostView.nhn?blogId=kohseiuk&logNo=130128534883) 
  
  - [공정능력 계산 - CP, CPK](https://m.blog.naver.com/PostView.nhn?blogId=easternsun&logNo=220063795394&proxyReferer=https:%2F%2Fwww.google.com%2F) 

5. 특성요인도(cause-effect diagram)

  - 목적: 원인과 결과의 관계를 파악

  - 용도: 원인을 모두 도면에 나열, 층별

6. 산점도(scatter diagram)

  - 목적: 대응하는 두 종류 데이터의 관계 파악

  - 용도: 원인과 결과의 상관관계 파악, 층별

7. 층별(stratification)

  - 목적: 불량원인의 추적

  - 용도: 무제의 핵심 파악, 5M1E(작업자(Man), 기계(Machine), 자재(Material), 작업방법(Method), 측정(Measurement), 환경(Environment))에 의한 요인 추구

### [SPC for Excel Statistical Tools](https://www.spcforexcel.com/spc-software/statistical-tools-spc-for-excel)
### [통계적 공정관리[SPC]](http://hrd.pps.go.kr:8820/home/DownloadBoardAction.do?BO_IDX=3895&FILE_NO=10638&BO_CODE=REFERENCE_ROOM)

# SPC 시스템 DB Spec

- SQL Server 2017 성능(InMemory, CCI)

  > 검사 항목이 많은 통계적 공정 관리 시스템의 경우 트랜잭션이 상당하다. SQL Server 2014의 OLTP 인메모리 기능을 평가해 보면서 데이터 입출력이 급증해도 데이터베이스 잠김(Lock & Latch) 현상이 없다는 것과 잠김 없이 데이터 일관성 보장이 가능하다는 것이 매우 인상적이었다. OLTP 처리 속도는 인메모리 컴파일러를 통해 네이티브 코드를 만들었을 때 24배 가까이 빨라졌다. 그리고 평소 느리다는 소리를 듣던 조회 시스템도 CCI(Clustered Columnstore Indexes)를 적용해보니 처리 속도가 22배나 증가했다 (삼성전기 생산기술연구소 MES그룹김명수 수석)
  
  
