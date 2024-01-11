---
title: Myc or HA purification
creation_date: 23.11.29
last_modified: 
note_type: method
category: purification
aliases:
  - Myc purification
  - HA purification
tags:
  - 준수_protocol
---
## Cell Growth
1. Broth 5ml, O/N
2. Subculture from initial OD 0.1 to OD 2.0 at 100ml broth 
	1. Transfer 50ml conical tube and centrifuge 3000rpm, 5min (Harvest)
3. Discard supernatant and washing with 1ml of DW
4. Transfer to 1.5ml tube and centrifuge 3000, 5min
5. Discard supernatant, Store at -80℃ 

## Lysis (bead beating)
1. Measure cell volume
2. Add cell lysis buffer and bead
3. Voltex in 4℃,30min and inverting every 10min
4. Poke hole in bottom of tube with a needle and allow liquid to flow into 15ml tube by centrifugation at 3000rpm for 5min.
5. Resuspend pellet (**NO ADD WATER**) and transfer to new 1.5ml tube, and centrifuge 12000rpm 20min 4℃.
6. Transfer **Supernatant** to new 1.5ml tube and keep in ice.
	1. Keeping **input WB sample**

## [[Bradford Assay]]
1. 정량한 뒤 coumn의 capacity에 따라 희석배수를 정할 것.
2. purification 과정을 전혀 거치지 않았기 때문에 농도가 높을 것이다.
	1. 1/20 희석 후 측정 권장
3. [[Bradford assay]]

## Resin Binding
1. Column에 1ml volume에 맞추어서 lysis buffer를 채워준다.
2. Myc, HA antibody 각각 2.5㎕ 씩 넣고 2hr, 4℃ rotation
3. Tip 끝을 자른 pipette tip으로 Protein A/G agarose 100ul를 column에 넣고 1hr, 4℃ rotation

## Collection and Elution
1. Flow-through를 받아줌.
2. FLAGbinding buffer 0.5ml로 washing 6번 (2ml tube 3개에 washing fraction을 받음)
3. Elution buffer 200ul로 5번 elution -> 1bead volume/elution buffer (1.5ml tube 5개에 한 번씩 elution)

(Sample 당 EB는 1ml)

## Blotting
-rabbit α-IgG를 이용해서, western blot / silver staining 수행
-coomassie brilliant blue staining시, band가 안 보일 수 있음, 그래서 silver staining 수행


## Buffer

| Stock buffer | Dilution folds | 150mM NaCl Binding buffer    | 150mM NaCl Lysis buffer  |
|--------------|----------------|----------------|--------------|
| 1M Tris-Hcl (pH7.5)  | 1/20        | 25ml           |        25ml       |
| 5M NaCl      | 3/100          | 15ml           |          15ml    |
| 0.5M EDTA    | 1/500          | 1ml            |         1ml     |
| D.W.         |                | 459ml          | 454ml        |
| Triton X-100 |                | X              | 5ml          |
| Total        |                | 500ml          | 500ml        |

Binding(Wash) buffer : 50mM Tris-Hcl, pH7.5,150mM NaCl, 1mM EDTA
Lysis buffer : 50mM Tris-Hcl, pH7.5,150mM NaCl, 1mM EDTA, 1% Triton X-100