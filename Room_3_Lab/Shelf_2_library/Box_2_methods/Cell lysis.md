---
title : Cell lysis
creation_date : 23.01.02
last_modified :
note_type : method
category : []
aliases : 
tags : [method]
---

Parent : [[_Methods]]

# RNA isolation의 경우
1. [[Cell harvest]]한 pellet을 얻었으면, 세포를 깨기 위한 처리를한다.
2. Master mix를 만들어도 좋고, 따로 넣어도 좋다.
	1. 권장하는 것은 실험오차를 줄이기 위해 master mix를 만드는 것이다.
	2. Recipe (per single tube)
| Chemical                          | Volume |  
| :--------------------------------- | ------: | 
| 1M Sorbitol-50mM Tris-Cl (pH 7.4) | 1ml    |  
| β-mercaptoethanol                 | 1ul    |
| zymolase (100mg/ml stock)                          | 5ul    | 
1. Shaking incubate / 30min at 30 °C.


# gDNA isolation의 경우
1. [[Yeast Cell culture#Overnight cell culture|Overnight cell cuture]]를 한 후에 [[Cell harvest]]를 한다.
	1. 이 경우 배양액의 OD를 고려하지 않아도 된다. 충분한 양의 DNA가 필요한거지 어떤 상태의 세포들이 필요한 것이 아니기 때문이다.
	2. early stationary phase : > 2 * 10<sup>8</sup> Cells/ml
2. Suspend with Protoplasting buffer 200ul
	1. incubating in 37C, 12min, inverse occasionally 
3. Add 200ul of lysis solution.
4. Incubate at 65C for 20min.
5. Rapidly cool on ice
6. Add 0.2ml 5M pottasium acetate (pH 5.4)
	1. inverse **(뒤집어 섞는다)**
7. Centrifuge at 12000rpm at 4C during 15min
	1. transfer sup. to fresh tube.
8. Add 360ul volume of isopropanol.
	1. inverse
	2. incubate at RT during 5min.
9. Centrifuge at 12000rpm during 15min. → remove sup
10. Add 200ul of 70% ethanol.
	1. incubate at RT during 5min
11. centrifuge at 12000rpm during 30sec.
12. Dry pellet add 100ul of diH<sub>2</sub>O

## Buffers
Protoplasting buffer
| Chemical          | volume |
| ----------------- | ------ |
| 2-mercaptoehtanol | 10ul   |
| zymolase          | 0.2mg  |
| Tris-Cl (pH 7.5)  | 100mM  |
| EDTA         | 10mM       |
Lysis solution
| Chemical | Volume |
| -------- | ------ |
| NaOH     | 0.2M   |
| SDS          | 1%       |

