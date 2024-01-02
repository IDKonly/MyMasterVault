---
title : Yeast transformation
creation_date : 23.01.16
last_modified :
note_type : method
category : []
aliases : 
tags : [method]
---

Parent : [[_Methods]]

## Seeding
1. Inoculate cells into 5ml YPD and [[Yeast Cell culture#Overnight cell culture|grow O/N]].
	
## Subculture
1. Take OD<sub>600</sub> of cells. add enough cells (about 200ul) to a new 10ml YPD culture.
2. Grow the cells on the shaker for 3 hours. OD<sub>600</sub> should be about 0.5~1.0. (or **0.4~0.6**, 0.5가 이상적인 OD값이다.)
	1. mid-log phase에 진입한 세포들을 원하기 때문.

## Harvest
1. Spin down cells(3000rpm, 5min) remove the media, and add 1ml water.
2. Transfer cells plus water to new 1.5ml tube and spin down(3000rpm, 5min).

## Competent Cell
1. Remove the water and add 100ul 100mM LiAc to cells and mix well.
	1. (**1M [[1M Lithium Acetate|LiAc]] 10ul, dH2O 90ul**)
2. Let the cells plus 100mM [[1M Lithium Acetate|LiAc]] sit at 30C for 30 minutes **(in shacking incubater)**
3. Centrifuge 3000rpm 5min
4. Remove sup.
	1.  Plasmid 같이 적은 양으로도 충분하거나 product의 농도가 충분히 높아서 적은 양으로 충분히 transformation이 가능한 경우, supernatant를 어느정도 남겨서 적은 양의 product를 넣어도 resuspend 할수 있도록 한다.
	2. 만약에 충분히 많은 양(resuspension 하기에 충분한)의 PCR product를 사용한다면, sup을 남길 필요 없이 최대한 다 따면 된다.

## Transformation
1. Make **[[50% PEG]] cocktail** 
	1. **240ul [[50% PEG]]3350(50%)**
	2. **36ul 1M [[1M Lithium Acetate|LiAc]]**
	3. **50ul boiled/chilled 1mg/ml [[ssDNA]]**
2. Resuspend with **PCR product or Plasmid** 10ul~15ul
3. **Add 326ul PEG cocktail** to tube and mix well
4. Let tubes sit at room temperature for 2 hours. 
	1. Voltex every 30min 
5. 42C heat shock 10min
	1. E.coli의 경우에는 얼음에 박지만, 이 경우에는 얼음을 사용하지 않아도 된다.
6. Centrifugation 12000rpm, 30sec. remove PEG.
7. Gently resuspend cell pellet in 100ul sterile water.
8. **Plate on appropriate selective media.**
9. Let plate grow for 3 days.