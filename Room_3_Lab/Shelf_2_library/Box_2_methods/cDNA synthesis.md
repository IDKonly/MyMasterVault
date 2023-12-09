---
title : cDNA synthesis
creation_date : 22.10.19
last_modified : 23.04.13
note_type : method
category : [qPCR]
aliases : 
tags : [method,cDNA]
---

Parent : [[_Methods]]

# Method

## Prepare RNA Template
1. [[RNA isolation(MN kit, NucleoSpin)]]
2. [[Nano drop]]
3. Dilution with RNase-free water or UPW to 1000ng/ul.

## PCR mixure recipe (each sample)
| Material                                     | volume (ul)       |
| -------------------------------------------- | ----------------- |
| 10X TOPscript RT buffer                      | 2                 |
| TOPscript recerse transcriptase(200units/ul) | 1                 |
| 2mM each dNTP mixture                        | 2                 |
| Template RNA*                                | x                 |
| 10mM primer                                  | 1                 |
| RNase Inhibitor(40units/ul)                  | 0.5               |
| sterile water(RNase free)                    | up to 20 (12.5-x) |
→ Store at -20°C

### PCR condition
42/5:00 - 50/1h - 95/5:00 - 4/inf

### Template RNA 
Total RNA : 1ng ~ 5ug
mRNA : 1ng ~ 250ng
Specific RNA : 0.01pg ~ 0.5ug

In general, the recommended amount of RNA is the same as above, but in this lab we usually use 500 ng of RNA.

### Primer
Oligo (dt)<sub>18</sub> : 50 ~ 100uM
→ If using oligo(dT)<sub>18</sub>, incubate at 40C for 5min before PCR.
Random hexamer : 50 ~ 100 uM
→ IF using ramdom hexamer, incubate at 25℃ for 10min before PCR.
Specific Primer : 15 ~ 20pmol

## Warning 

>Reaction conditions is only a general recommendation. The experimental conditions should be adjusted according to the purpose and sample

>typiclally 50C is good starting point. For RNAs containing secondart structure and other challenging target, a synthesis temperature of 60C may be used without loss of performance.

# Reference
[TOPscript™ cDNA Synthesis Kit | Global Supplier of enzymes, experiment kits & cloning kits for enzymes | Enzynomics](https://www.enzynomics.com/shop/product_item.php?it_id=402004)


# Legacy 

> P.S.
> 이 실험은 옵시디언을 사용하기 전에 진행되어 노션에 기록이 남아있음
> 필요하면 노션에서 찾아볼 것.

1. RNA를 [[nano drop]]에서 정량한다. (막 3200ng/ul로 나오고 그럼)
2. 정량한 RNA를 UPW 또는 RNase free water로 1000ng/ul로 희석한다.

PCR mix recipe (each sample)
| Material                                     | volume (ul)       | agent location |
| -------------------------------------------- | ----------------- | -------------- |
| 10X TOPscript RT buffer                      | 2                 | -20            |
| TOPscript recerse transcriptase(200units/ul) | 1                 | -20            |
| 2mM each dNTP mixture                        | 2                 |                |
| Template RNA                                 | 500ng (x ul)      |                |
| 10mM primer                                  | 1                 |                |
| RNase Inhibitor(40units/ul)                  | 0.5               | -20            |
| sterile water(RNase free)                    | up to 20 (12.5-x) |                | 

**PCR condition -> 42/5:00 - 50/1h - 95/5:00 - 4/inf**

_prepare_

one of following RNA tmeplate
- Total RNA 1ng~5ng

one of the following primers
- oligo (dT)<sub>18</sub> - 50uM~100uM
- if using oligo(dT)<sub>18</sub>, incubate at 40C for 5min
- if using random hexamer, incubate at 25C for 10min
-> incubate 42~60C for 60min
-> incubate at 95C for 5 min to incubate the reaction

**typiclally 50C is good starting point. For RNAs containing secondart structure and other challenging target, a synthesis temperature of 60C may be used without loss of performance.**


> Template RNA와 Sterile water를 제외한 agent를 모두 섞어 master mix로 만들어 준비하면 편리하다.
> sample 갯수대로 만들면 모자랄 위험이 있으니 0.5개분량정도 더 만들면 좋다. 딱 떨어지지 않거나 한다면 1개 분량을 더 만들어도 좋다.
> template RNA 용액의 양이 매우 적을때, 조심해야 한다. RNA가 벽면에 묻은채로 섞이지 않으면 cDNA 합성에 실패할 수 있다. 