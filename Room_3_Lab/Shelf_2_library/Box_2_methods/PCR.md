---
title : 4_PCR
creation_date : 22.10.20
last_modified :
note_type : method
category : []
aliases : 
tags : [method]
---

Parent : [[_Methods]]

# Prepare

[[Gel electrophoresis]]
[[Primer dilution]] : 만약 프라이머 stock을 쓴다면, 10ul(primer) : 90ul(UPW)로 희석한다.

![[KakaoTalk_20230202_154817814 2.jpg]]
> 1. Template / primer 희석하기
> 	1. gDNA : 20-30ng
> 	2. Plasmid : around 1ng
> 2. Mixture : volume이 가장 큰 DW(UPW)부터!
> 	1. 1.5ml tube에 mastermix를 만들것
> 	2. polymerase 마지막에 넣고, voltexing 
> 3. Template → PCR tube 에 loading 
> 4. Mixture → PCR tube 

# Recipe

## Dream Taq
| Agent          | Volume (ul/per 10ul rxn) | 비고 |
| -------------- | --------------------: |-----|
| 10X buffer     | 1                    | Mater mix |
| dNTP mix       | 0.8                  | Mater mix |
| Forward primer | 0.5                  | Mater mix |
| Reverse primer | 0.5                  |Mater mix |
| Template DNA   | 10~500ng (x ul)      |
| Polymerase     | 0.1                  | !주의 temp sensitive.|
| UPW            | up to 10 (7.1 - x)            |Mater mix |

reference : [[DreamTaq_user guide_221020_101620.pdf]]

순서

1. template DNA와 polymerase를  제외한 mastermix를 만들어놓는다.
2. PCR tube에 원하는 template DNA를 넣는다.
3. 중요) Master mix에 polymerase를 넣고, **즉시** PCR tube에 Master mix를 나눠 넣는다.
4. 그 다음 드림택 PCR로 돌려준다.

일지
[[22.11.04 PCR and Gel electrophoresis]]
[[22.11.11 PCR and Gel electrophoresis]]

→ Dreamtaq은 proof-reading 기능이 없어서 무언가를 측정하고 나서 product를 버릴때만 사용한다. mutation이 자주 일어나서 높은 정확도가 필요한 작업에는 좋지 않음.
→ 이런 경우에는 Phusion polymerase를 쓰는 것이 맞다.

## Phusion Polymerase


Ref : [PCR Protocol Phusion® DNA Polymerase | NEB](https://international.neb.com/protocols/0001/01/01/pcr-protocol-m0530)

Mix 
| Agent                               | 50ul rxn | Volume (ul per unit(10ul) | Final concentration |
| ----------------------------------- | -------- | ------------------------- | ------------------- |
| 5X Phusion HF or GC Buffer          | 10         | 2                         | 1X                  |
| 2mM dNTPs                           |   1       | 0.2                       | 200uM               |
| 10uM Forword primer                 |    2.5      | 0.5                       | 0.5uM               |
| 10uM Reverse primer                 |       2.5   | 0.5                       | 0.5uM               |
| Template DNA                        |  variable         | variable                       | < 5ng/ul            |
| DMSO(optional, GC-ratio denpendent) |  (1.5)        | (0.3)                       | 3%                  |
| Phusion polymerase                  |    0.5      | 0.1                       | 1.0units/50ul PCR   |
| UPW                                 |    to 50      | to 10ul                   |                     |

PCR Cycle 

| Step            | Temp  | Time          |
| --------------- | ----- | ------------- |
| Initial         | 98    | 30s           |
| 25~35 cycle     | 98    | 5~10s         |
|                 | 45~72 | 10~30s        |
|                 | 72    | 15~30s per kb |
| Final Extension | 72    | 5~10min       |
| Hold            | 4~10  | inf           |

주의) gDNA 농도가 너무 높으면 PCR이 안되더라

### PCR Troubleshooting Guide

[PCR Troubleshooting | Bio-Rad](https://www.bio-rad.com/ko-kr/applications-technologies/pcr-troubleshooting?ID=LUSO3HC4S)
[PCR Troubleshooting Guide | NEB](https://international.neb.com/tools-and-resources/troubleshooting-guides/pcr-troubleshooting-guide)

[Will excessive template affect the specificity of PCR products? | ResearchGate](https://www.researchgate.net/post/Will_excessive_template_affect_the_specificity_of_PCR_products)

>Too much template can lead to no amplification if the template dna has pcr inhibitors.

너무 많은 템플레이트는 아예 증폭 산물을 없애버릴 수도 있다.

## Hot Start

polymeras를 cpr cycle 중 preheating이 끝나고 집어넣는다.


### 궁금증 해소

![[Pasted image 20230110182416.png]]