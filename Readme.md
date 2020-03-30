### 서울시의 전기차 충전소의 효율적인 위치 선정을 분석하기 위해 시작한 개인 프로젝트 입니다.
### 주 타겟은 '동작구' 입니다.
<hr/>

* 3월 20일(total car num in Seoul.jpynb):
  * 서울시 전체 자동차 등록 대수를 구별로 나누어 순위를 매겼습니다.
  
* 3월 21일(total car num in Seoul.jpynb):
  * 서울시 전체 전기 자동차 등록 대수를 구별로 나누어 순위를 매겼습니다.
  
* 3월 26일(Electirc vehicle charging station.jpynb):
  * 서울시 전체 전기차충전소 위치 좌표를 추출하였습니다.
  * (error) 133행 부터 FAILE
  
* 3월 27일(Electirc vehicle charging station.jpynb):
  * 539개 중 90%이상 좌표 추출 성공
  * 충전소 좌표.csv 파일에 저장
  
* 3월 28일(fillNull_chargingStation.jpynb, infinite charging_folium.jpynb):
  * 일부 추출하지 못한 좌표 수작업으로 가져옴
  * folium을 이용하여 전기차충전소 현 위치 시각화 완료
