---
title : Bradford assay
creation_date : 23.05.17
last_modified :
note_type : method
category : []
aliases : 
tags : []
---

Parent : [[_Methods]]

Bradford solution을 쓴다.
→ 제품임 ; # Bio-Rad Protein Assay Dye Reagent Concentrate, 450 ml **#5000006** 5배 희석하여 사용.
참고사항 : [브래드퍼드 단백질 정량법 - 위키백과, 우리 모두의 백과사전](https://ko.wikipedia.org/wiki/%EB%B8%8C%EB%9E%98%EB%93%9C%ED%8D%BC%EB%93%9C_%EB%8B%A8%EB%B0%B1%EC%A7%88_%EC%A0%95%EB%9F%89%EB%B2%95)

1. Standart curve를 그려야 한다.
	1. BSA 1.6mg/ml를 serial dilution한다.
	2. 모든 튜브에 20ul DW를 투입하고, 연속적으로 희석한다.
	3. 원하는 샘플은 0.8, 0.4, 0.2, 0.1, 0 각 20ul의 5개의 샘플을 만든다.
	4. 3개의 신뢰 가능한 값을 얻는다면 신뢰도(R<sup>2</sup>)를 포함한 표준곡선을 그릴수 있고, 이를 기준으로 샘플의 값을 비교하면 샘플의 단백질 농도를 알 수 있다.
2. 샘플을 적정치만큼 희석한다. 되도록이면 BSA가 포함되어 있는 샘플의 중간정도의 농도를 띠면 된다.
3. 만들어진 BSA와 타겟샘플을 800ul 만큼의 bradford solution에 희석하고 voltexing한다.
4. 5분정도 반응하도록 둔 뒤 OD<sub>600</sub>을 잰다.
	1. 원래 흡광도를 잴 때 반응하는 coomassie blue 염색약은 595nm 파장대에서 최대 흡광도를 가지지만, 600과 크게 차이나는 구간이 아니고 충분히 연관관계가 있을 것이기 때문에 그냥 이것을 지표로 삼는다.
5. 얻어낸 BSA의 흡광도 값으로 엑셀을 통해 표준곡선을 그리고, 이 공식에 샘플의 OD값을 대입해 농도값을 얻는다.