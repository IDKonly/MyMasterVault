---
title: The Tandem Affinity Purificaion(TAP) Method
creation_date: 23.04.10
last_modified: 
note_type: method
category: []
aliases:
  - TAP purification
tags:
  - protein
  - purification
  - TAP-taged
---

Parent : [[_Methods]]
Drived from : [[Immunoprecipitation]]

# One step Method
→ Calmodulin binding만 이용

## Cell Growth
1. Overnight culture in YPD 5ml
2. Subculture with 0.1~0.2 initiate OD<sub>600</sub> to 2.0 (mid-log phase ~ late-log phase, this value can be change)
	1. subculture 용량은 요구하는 타겟 단백질의 양이나 성장조건등에 따라 바뀔 수 있음.

## Harvest and Lysis
1. Harvest cell (3000 rpm 5 min) and wash with dH2O 1mL.
	1. 50ml Used conical tube에 세포를 배양한 배지를 모두 나눠담고, harvest한다.
2. transfer to 2ml tube; harvest cell in 2ml tube(12000 rpm 30 sec). *→ can store at -80℃ (escape)*.
	1. 1ml정도의 물로 50ml conical tube에서 harvest 한 cell들을 녹이고, 이것을 다시 다른 튜브로 옮겨 resuspend 한다. 
	2. 2ml tube에 최대 300ml 배양한 cell을 담을 수 있음.
3. This cells can then be lysis by variable methods

### Cell Lysis Methods
#### Bead Beating
1. Resuspend in mixture (2X binding buffer and [[protease inhibitor]]) 1 volume of pellet.
	1. 혼합물이 cell을 포함해서 1x binding buffer, 1x Protase inhibitor 만큼 되도록 넣는다.
2. Add 1ml (or 1 volume of resuspend mixture) glass bead 
3. Beadbeating for 10min in 4℃ and voltexing well.
	1. 3번 반복 (Beadbeating 30분)
4. Poke hole in bottom of tube with a needle and allow liquid to flow into 15ml tube by centrifugation at 3000rpm for 5min.
5. Resuspend pellet (**NO ADD WATER**) and transfer to new 1.5ml tube, and centrifuge 12000rpm 20min 4℃.
6. Transfer **Supernatant** to new 1.5ml tube and keep in ice.
	1. 이 시점에서 잠시간 휴식 가능.

#### [[Coffee grinder]]

## Calmodulin Binding
1. **Remove cap from new chromatography culumns.**
2. Transfer **100ul resin bead** (or what you need) to chromatography column, and wash it with **1x binding buffer 2ml**
	1. 이 작업은 레진을 보관하고 있는 20% 에탄올 용액이 레진과 단백질의 반응성을 약화시키지 않게 하기 위해서이다. (equalization)
	2. 바닥에 용액받이를 깔고 거치대에 세워서 한다.
	3. 레진을 용액에 잘 풀어서 쓰고, 실험 도중 레진이 마르지 않도록 주의한다.
3. Capping bottom of chromatography column with **yellow cap**, and **add sample** which keep in ice. then **capping the top** and sealing both **use parafilm**.
4. Rock at 4℃ for 2-3 hours or O/N.
	1. tag와 단백질의 특징들을 고려해서 1시간에서 overnight까지 다양하게 설정할 수 있다.

## Collection and Elution
1. Collect flow-though (*store at -80℃*)
	1. 실험결과에 필요한 것은 아니지만 추후에 트러블슈팅의 가능성을 위해서 모아둔다.
2. Wash 3 times with 2ml 1X binding buffer
3. Elute 5 times with 300µl elution buffer to each of the tubes.

### Out Put
→ 샘플당 5개의 300ul elution sampe과 하나의 Flow-through가 발생한다. (*store at -80℃*)
→ 이중 첫번째부터 세번째 까지의 샘플은 적정한 양(50ul정도) 분주하여 4X loading dye를 처리하고 95도에서 5분간 끓인다. [[Western blot]] 샘플을 만들기 위한 것이다.


| 2x binding buffer | per 100ml |     | Elution buffer  | per 30ml |
| ----------------- | --------- | --- | --------------- | -------- |
| 1M HEPES pH 7.5   | 10ml      |     | 1M HEPES pH 7.5 | 1.5ml    |
| 5M NaCl           | 6ml       |     | 5M NaCl         | 900ul    |
| 14M BME           | 150ul     |     | 14M BME         | 20ul     |
| 1M MgAc           | 200ul     |     | 1M MgAc         | 30ul     |
| 1M CaCl2          | 600ul     |     | 0.5M EDTA       | 240ul    |
| NP-40             | 200ul     |     | NP-40           | 30ul     |
| 1M Imidazole      | 200ul     |     |                 |          |

[[TAP method refference]]

> [[Immunoprecipitation]]과 거의 동일하다.
> 다른 Binding tag와 결합할 거라면 resin과 buffer 조성만 조정하면 된다.
> Elution buffer의 경우, elution 조건이 특이한 경우에는 다른 방법들을 추가해야 할 수도 있다.