e commerce - 전자상거래

stakeholder - 이해관계자

e-commerce business type 1: nike

type 2: coupang, naver

type 3: 소비자

---
---

e-commerce data (platform biz)
1. 갯수
2. cataloging, categorazing
3. 일관된, generation
4. 지표, 즉각적,
5. 이력 데이터
6. 롱테일 - 사용자 이력 알고리즘, 학습
7. 용도에 따라 저장소 저장방식 다르게
8. 데이터 이동
9. 수익 개선

---
---

e-commerce traffic
1. traffic에 peak
2. 새벽시간 traffic 줄어든다
3. 외부, 내부 traffic handling 제어방향 수준 다름

특징
bigdata, log, catalog governance, longtail, , , , scalability, , control,

- 상품데이터 log
- 데이터 이용 kafka / immediacy duplication
- request defined redis / variation
- redis cache용도 / immediacy duplication
- service최적화 / optimization
- 품질수준 / policy

---
---

key value business

1. 이익 = (매출 * margin) + 광고수익
2. 매출 = 상품판매
결론 검색

---
---

e commerce biz는 microservice를 사용하는게 장점

대충 기본 틀
로그인 - 검색 - 비교 - 결제 - 배송

- 회원정보 서비스
- 가입 탈퇴 서비스
- 로그인 서비스

- 반품 교환 서비스
- 이력 서비스 -  저장 조회 관리
- 분석 서비스 - 구매 판매 프로모션 매출
- 학습서비스 - 전처리 데이터이동 보관

- 검색서비스 - 외부가격비교 내부가격비교

- 결제서비스
- 배송서비스

---
---

### redis usecase / 기간 한정, 빠른 전환
- 장바구니 - 로그아웃 시 소멸
- temporary user정보 - 로그아웃 소멸
- 할인정보 - 할인기간 종료 소멸
- 쿠폰정보 - 로그아웃, 쿠폰행사 종료 소멸
- 배송정보 - 배송완료후 n일후 소멸
- 토큰, 세션 로그인상태유지위해 - 로그인후 소멸, 로그아웃후 소멸
- 광고 - 광고계약시점이후 소멸
- 채팅정보 - 채팅 종료시 소멸
- etc cache - 소멸기한이 있을 경우 소멸

### kafka usecase / 이동, trigger
- page tracking - 페이지 분석
- 광고클릭정보 - 광고 카운팅
- 에러정보 - 이상탐지
- 구매정보 - 매출집계
- 내 외부 api keyword정보 - 키워드 집계
- 서버 로그 정보 = 서버 이상 확인, 이상탐지
- 장바구니 정보 - 구매 절차 간소화
- 결제정보 - 실제 결제 프로세스


---
---





