---
creation_date: 23.05.01
last_modified:
note_type: basic
category:
memo_level:
aliases:
tags: []
---

Parent : [[]]

예전에 쓴 인트로를 가공하자
[[1_Saccharomyces cerevisiae의 telomeric silencing 연구를 위한 새로운 마커 유전자의 탐색_intro]]

        

## 텔로미어

텔로미어(Telomere)는

이 전체적인 구성은 효모에서 포유류에 이르기까지, 진핵세포 전체에 걸쳐서 고도로 보존되어 있다. 
이렇게 만들어진 구조체는 외부의 공격으로부터 DNA를 방어하므로, 결과적으로 genome stability를 증가시킨다.

—

텔로미어는 진핵생물의 염색체 각 말단에 존재하는 DNA-단백질 복합체이다. 이 구조는 효모에서부터 포유류에 이르기까지 고도로 보존되어 있다. 이 구조는 빽빽한 heterochromation 구조를 이루고 있다.


## Telomeric positioning effect

Position effect는 centromere, telomere와 같이 염색체에 전반적으로 분포한 heterochromatin block에 있거나 근접한 유전자가 heterochromatin에 의해서 silencing이 되는 현상이다. (Krassimir. 2012) Telomere 또한 heterochromatin block이기 때문에 position effect가 나타나는데, 이 telomere에 의한 position effect를 Telomere position effect(또는 telomeric silencing)라고 한다. TPE는 특정 유전자나 텔로미어에 대해서 특이적이지 않은 현상이다. (Raymund et al., 2012) _S. cerevisiae_ 에서, 텔로미어는 Rap1p의 binding site를 제공하고 이 Rap1은 Sir protein을 모집한다고 알려져 있다. 이 Sir protein들은 최초로 모집된 말단영역으로부터 스스로를 계속해서 소집하며, 긴 heterochromatin fiber를 생성하는 것으로 학계에 보고되었다. (Sarah et al., 2018, Bo et al., 2006) 그 결과, Sir complex에 의해서 만들어진 긴 heterochromatin fiber가 telomere의 position effect를 강화 시켜 넓은 범위에 영향을 미친다. position effect는 heterochromatin의 범위에 의존하기 때문에, silencing의 경계에 위치하는 유전자는 확률적으로 transcriptional silencing이 일어난다. 이 때문에 생겨나는 유전자 발현패턴에 차등이 있다는 것을 Position-effect variegation(PEV)이라고 하고(Sarah et al., 2013), telomere 부근에서 일어나는 것을 특이적으로 Telomere position effect variegation(TPEV)이라고 한다.

—

heterochromatin구조 안에 있거나 인접한 유전자는 그 영향을 받아 silencing되고, 이것을 position effect라고 한다. Telomere 또한 heterochromatin block이기 때문에 position effect가 나타나는데, 이 telomere에 의한 position effect를 Telomere position effect(또는 telomeric silencing **Abstract와 표현 통일하기** )라고 한다.

[[Saccharomyces cerevisiae]]는 heterochromatin 연구에 아주 유용한 모델 생물체이며 잘 알려진 teloemre 구조를 가지고 있다. [[Saccharomyces cerevisiae|S. cerevisiae]]의 TPE는 telomere에 결합한 Rap1이 [[SIR complex]](Sir2, Sir3, Sir4)를 모집하면서 이것에 의해 생성된 heterochromatin이 일으킨다. [[SIR complex]]는 결합원점으로부터 인접한 Histone을 acetylation 시키며 퍼져(spreading)나간다.



## URA3 assay

TPE 연구에서 핵심적인 역할을 하는 두가지 연구 방법 중 하나인 URA3 assay는 URA3 유전자를 genome에 삽입하는 방법을 이용한다. Yeast에서 널리 쓰이는 방법은, 7번째 염색체의 왼쪽 팔 (TEL07L)에 있는 ADH4 유전자 부근에 URA3 유전자를 삽입하는 것이다. (Gottschling et al., 1990) URA3는 5-Fluoroorotic Acid(5-FOA)가 함유된 배지 위에서 발현되었을 때 치명적인 독성 대사산물을 만들어 세포 스스로를 죽이기 때문에, 5-FOA resistance를 비교해 telomeric silencing의 존재여부 또는 정도(level)를 알 수 있다. (Gottschling et al., 1990) Telomere position effect에 대한 연구에서 가장 핵심적인 역할을 하는 두 실험의 특징 중 하나는 아주 높은 민감도이다. 많은 연구에서 FOA-sensitivity assay는 광범위하고 유용하게 사용되었다. (Krassimir. 2012)

## 문제점

하지만 URA3 assay는 assay에 적합한 야생형(WT) 균주를 찾는 데에 2주 이상의 시간이 필요하고, 해당하는 위치에 URA3 유전자를 삽입하기 위해 Plasmid를 처리해야 하는 등 많은 시간이 필요하다. (Gottschling et al., 1990) 뿐만 아니라, URA3 reporter를 삽입하는 과정과 우리가 원하는 query gene이 동시에 조작된 균주를 얻는 것은 별개의 일이기 때문에, SGA method와 같은 double mutant 균주를 얻기 위한 실험이 추가로 진행되어야 한다. 이런 식의 연구는 빠르게 원하는 연구 결과를 얻는 데에 아주 오랜 시간을 소모하는 동시에 5-FOA와 같은 높은 비용의 재료들 때문에 연구의 효율성에 문제를 일으킨다. 또한 2011년에 학계에 보고된 바에 따르면, FOA-sensitivity assay중 하나인 URA3 assay를 할 때에 세포의 사멸이 Telomeric silencing effect의 결손으로 인한 URA3의 발현을 나타내는 것이 아니라, 5-FOA에 의해서 유도된 대사의 결과를 나타낼 뿐이라는 의혹을 제기했다. (Rossman et al., 2011) 더불어, URA3가 삽입된 telomere가 아닌 다른 부위에서 silencing defect가 발생했다면 감지할 수 없다 라는 주장 또한 제기 되었다. (Takahashi et al., 2011) 이러한 문제는 불가피하게 우리에게 telomeric silencing에 대한 아이디어 중 일부가 잘못된 실험 방법에 기반을 두고 있는지 의문을 제기하게 만든다. (Krassimir. 2012) 즉, 직전에 telomere position effect의 연구에서 쓰였던 분석법들은 높은 비용과 학계에서 제기된 치명적인 의혹들 때문에 이를 대체하거나 보완할 telomeric silencing의 감지방법이 필요하다.


## 연구 결과로 나아질 수 있는 점

이렇게 외래 유전자가 아니라 WT이 원래 가지고 있는 유전자를 이용해서 silencing의 존재 여부를 판단한다면, 외래 유전자로 인해 생기는 대사변화를 감수하지 않아도 될 뿐 아니라 같은 샘플 내에서 동시에 여러 부위의 발현변화를 감지할 수 있을 것이기 때문에 여러 측면에서 telomere position effect의 변화를 연구할 수 있을 것이다. 또한 이 방법은 여러 실험 방법에서 이용하고 있는 신뢰성 있고 보편적인 방법을 기반에 두고 있으므로 기존 방법보다 상당히 빠른 속도로 실험을 진행하고 결과를 얻을 수 있다.

이런 빠르고 신뢰성 있는 검증 방법은 시간소모를 최소화함으로써 telomeric silencing에 대한 이해를 빠르게 증진시킬 수 있을 것이다.



**텔로미어**

Telomeres in most eukaryotes are composed of heterochromatin structure.

**TPE**

텔로미어 근처에 있는 유전자는 필연적으로 heterochromatin의 영향을 받아서 silencing 된다. 이 현상을 telomere position effect (TPE, or telomeric silencing)라고 부른다. TPE is not specific effect to gene or telomere.

**Sir complex**

Sir complex는 텔로미어 근처에서 heterochromatin을 형성하는 주요 단백질 중 하나이다. Sir complex의 구성요소 중 하나인 Sir2가 결실되면 telomeric silencing이 일어나지 않는다.

**Spreading**

_S. cerevisiae_ 에서, 텔로미어는 Rap1p의 binding site를 제공하고 이 Rap1은 Sir protein을 모집한다고 알려져 있다. 이 Sir protein들은 최초로 모집된 말단영역으로부터 스스로를 계속해서 소집하며, 긴 heterochromatin fiber를 생성하는 것으로 학계에 보고되었다(Sarah et al., 2018, Bo et al., 2006). 
이렇게 만들어진 SIR complex는 텔로미어와 인접한 영역에서 발생하는 TPE를 더 넓은 범위로 확장한다.

**Growth assay**

URA3 assay로 대표되는 Growth assay는 아주 높은 민감도를 가진 동시에 잘 알려진 TPE를 대상으로 하는 실험이다. URA3 assay는 URA3가 발현되는 균주가 5-FOA 배지에서 성장할때 독성 대사산물을 만들어 스스로를 사멸시키는 것을 이용하는 실험이다. 주로 TEL07L에 URA3 유전자를 삽입하여 5-FOA resistance를 비교하여 TPE의 강도를 비교 할 수 있다.

**Major conflict**

However,

1. Cost
	1. URA3 reporter를 삽입하는 과정과 우리가 원하는 query gene이 동시에 조작된 균주를 얻는 것은 시간이 오래걸린다.
	2. 5-FOA와 같은 높은 비용의 재료들 때문에 연구의 효율성에 문제를 일으킨다.
2. critical quastion
	1. 또한 2011년에 학계에 보고된 바에 따르면, FOA-sensitivity assay중 하나인 URA3 assay를 할 때에 세포의 사멸이 Telomeric silencing effect의 결손으로 인한 URA3의 발현을 나타내는 것이 아니라, 5-FOA에 의해서 유도된 대사의 결과를 나타낼 뿐이라는 의혹을 제기했다(Rossman et al., 2011). 
	2. 더불어, URA3가 삽입된 telomere가 아닌 다른 부위에서 silencing defect가 발생했다면 감지할 수 없다 라는 주장 또한 제기 되었다(Takahashi et al., 2011). 

