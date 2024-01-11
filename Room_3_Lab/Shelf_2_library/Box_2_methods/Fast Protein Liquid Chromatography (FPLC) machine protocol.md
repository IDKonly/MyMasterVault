---
title : FPLC machine protocol
creation_date : 23.05.16
last_modified :
note_type : method
category : []
aliases : FPLC
tags : [SEC, FPLC]
---

Parent : [[_Methods]]

- in This lab, use AKTA go
- [[FPLC 추가정보]]

## Maintenance Routine

1. 튜브 제자리 (inlet tube 4개 → 20% EtOH, outlet tube 3개 → Waste)
2. Replace new Rinse solution
	1. 50ml of 20% EtOH
3. Inlet/Purge pump priming
	1. inlet valve A를 open flowpath로 지정한다.
	2. 펌프 상단에 있는 valve를 반시계방향으로 한바퀴 반 돌려서 열고, 30ml 주사기를 포트에 꽂은 뒤 안에 있는 buffer를 빼낸다. (Purge)
		1. 이 과정은 두개의 펌프 모두에서 이루어져야 한다.
		2. 이 과정은 inlet부터 flowpath에 이르는 관에 있을 수 있는 공기를 빼내고, 액체로 가득 채우기 위해서 시행한다.
	3. Injection valve를 Waste로 지정하고, pump와 inlet의 flow를 5ml/min으로 지정한 후, pump에서 다시 purging한다.
4. Performance test 
	1. System - performance test - system test - run
	2. 보통 Pass한다.
5. [[CIP (Cleaning-in-place)]]  of flow path and injection valve
	1. B, Sample inlet을 DW에, Inlet C를 1M NaOH, 그리고 inlet A를 buffer에 넣고 CIP method를 실행하면 된다. 
	2. 이 동안에 (혹은 이후에) Injection valve를 load로 두고, 10ml의 cleaning solution(1M NaOH)를 injection valve port에 주입한다.
	3. 그 다음 주사기를 DW로 채우고 동일한 절차대로 주입한다.

## Preperation

### Setting up of Chromatography Coumn

>[!note] Warning
>Column이 20% EtOH로 채워져 있는 경우, Salt를 포함하고 있는 buffer를 투입하지 마시오, 반대의 경우도 금지됩니다.
>EtOH와 Salt가 직접 접촉할 경우 침강반응이 일어날 수 있고, 이렇게 만들어진 염은 column과 장비를 손상시킬 수 있습니다.

1. Column([Superose® 6 Increase 10/300 GL Cytiva 29-0915-96, 10/300 GL | Sigma-Aldrich](https://www.sigmaaldrich.com/KR/ko/product/sigma/ge29091596))을 장비에 결착
	1. 컬럼과 장비를 연결
		1. 연결 전에 flow를 0.2mL/min로 켜둔다
		2. column 상단을 열어두고, 튜브에서 액체가 흘러 나오기 시작하면 연결한다 (drop to drap)
			1. 이후 column 하단을 열고, 액체가 새어나오기 시작하면 하단도 동일하게 연결한다.
2. Equalibration
	1. 위의 이유로 DW→ buffer 순서로 진행하고, 각 2CV만큼 column을 통과시킨다.
		1. DW equilibration을 할때는 Wash tube( **inlet C는 1M NaOH에 있어야 한다.**)를 뺀 모든 inlet tube가 DW에 담겨 있어야 하고, 반대로 buffer equilibration을 할 때는 buffer에 담겨 있어야 한다.
	2. DW 2시간 30분, buffer 1시간 30분여 소요된다.

## Main

### Standard Loading
> [[Size exclusion chromatography(SEC)]] 결과물의 사이즈 레퍼런스가 되어줄 비교물질을 장비에 걸고, 그 데이터를 얻는 작업. 이 데이터를 얻는 작업이 선행되어야 이후에 얻는 데이터를 분석할 수 있다.

1. inlet 3개(**A, B, Sample**)을 Buffer를 받아들일 수  있도록 담근다. 
	1. Equilibration 단계를 거쳤다면 이미 담겨져 있을 것이다.
2. Method를 실행하면, buffer가 흐르기 시작하는데, 이때 loop tube는 격리된 상태로 있는다. 약 5ml가 흐를 동안, 이 격리된 상태는 유지된다.
	1. 이 사이에, Chromatography buffer 1ml를 injection valve port를 통해서 주입한다.
	2. 그 다음 희석된 Standard(buffer 400ul + standard 20ul (분주된 한개의 standard))를 injection valve에 있는 포트를 통해 주입한다.
	3. 이때, 공기가 들어가지 않도록 주의하고, 주사기는 뽑지 않는다.
	4. 주사기를 뽑으면, 외부로 용액이 누출되거나, 주입한 샘플이 제대로 로딩되지 않을 수 있음. (Siphoning)
	5. 주입이 완료되었으면, process가 완료될때까지 기다린다. 이 시간에 Sample을 준비해두면 된다. (약 1시간 30분 소요)

### Sample Preperation

#### Sample Concentration

Go to : [[Sample concentration]]

#### Bradford Assay

Go to : [[Bradford assay]]

### Main Practice

1. 기본적으로 Standard loading과 동일한 방법으로 수행합니다.
2. Buffer로 injection loop를 세척한 뒤, [[Bradford assay]] 등을 통해 정량한 단백질을 정해진 양 혹은 농도대로 주입합니다.
3. Standard loading과는 달리 fraction을 받게 되므로, fraction collector에 tube를 거치해두고, 암(arm)을 정위치에 둔다.
4. Method를 선택하고 실행한다.

## Post-maintenance

### Column Storage

1. Equlibrate with DW (2CV, 0.75ml/min) inlet은 모두 DW에.
2. Equlibrate with 20% EtOH (2CV, 1/2 recommend flow rate)
	1. 위 두개는 그냥 equilibration method를 역순으로 돌리면 된다 (equl with buffer - equl with DW)
3. 종료되면 column 내부는 20% EtOH로 가득 찬 상태이므로 그대로 column의 연결부를 분리하고 봉인후 냉장보관한다.
4. 분리된 커넥터는 다시 연결해 놓는다.

### System Storage

1. [[CIP (Cleaning-in-place)]] 한다.
	1. Flow path → B, Sample inlet을 DW에, Inlet C를 1M NaOH, 그리고 inlet A를 buffer에 넣고 CIP method를 실행하면 된다. 
		1. 단, 시스템 내부에 EtOH를 채워야 한다는 점을 고려해서 마지막에 한번 DW로 CIP한다.
	2. Injection valve → DW - NaOH - DW - EtOH 순서로 10ml injection.
2. 모든 inlet을 20% EtOH에 담그고, 모든 inlet을 대상으로 Pump.
3. Fraction collector를 세팅하고, fractionation을 켠다.
	1. Flow rate : 10ml/min , Timer 25ml volume, run

## FPLC Solutions

*All solutions need 0.22um filteration*

### Chromatography Buffer 1L

| Agent               | Volume |
| ------------------- | ------ |
| 1M Tris-HCl (pH7.5) | 20ml   |
| 5M NaCl             | 20ml   |
| DW                  | 960    |

### 20% EtOH 2L

| Agent    | Volume |
| -------- | ------ |
| 94% EtOH | 428ml  |
| DW       | 1572ml |

### 1M NaOH 200ml

| Agent | Volume      |
| ----- | ----------- |
| NaOH  | 8g          |
| DW    | up to 200ml |

### Altered Chromtography Buffer A

| Agent           | Volume |
| --------------- | ------ |
| 100% Glycerol   | 100ml  |
| 1M Tris (pH8.0) | 50ml   |
| 3M KCl          | 113ml  |
| 0.5M [[EDTA]]   | 2ml    |
| DW              | 715ml  |



[[수정요함]]