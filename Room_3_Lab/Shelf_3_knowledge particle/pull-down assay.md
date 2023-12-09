---
title : pull-down assay
creation_date : 23.02.08
last_modified :
note_type : basic
category : 
memo_level :
aliases : 
tags : [webclip]
---

Parent : [[_KnowledgeParticle]]
Drived from : [[]]

[GST-pull down assay 원리 / pull down assay 원리 - Bio-Chae](https://bio-chae.com/pull-down-assay/)


> GST-Pull down assay의 목적은 단백질간의 상호작용 (interaction)을 확인하는 것이다.

Pull down assay는 실험의 이름 그대로 “Pull down” “끌어당겨서” **단백질의 interaction을 확인**하는 것이다. IP와 굉장히 유사한 부분이 있다. 하지만 기본 원리에 있어서 큰 차이가 있다.

## 1. GST-Pull down 원리 및 workflow

Pull down assay는 tag이 달려있는 정제 단백질을 이용하여 단백질을 pull down 즉, 끌어 당기는데 이용한다. 즉, Glutathione S-Transferase (GST), His-tag, Biotin 등이 tagging 되어있는 단백질을 정제한 후에 다른 단백질 혹은 cell lystae등과 반응 시킨다. 그 후에 pull down을 하기 위해서 bead를 이용하는데 IP에서 A/G agarose bead를 이용했다면 pull down에서는 각 tagging protein에 맞는 bead를 사용한다.

-   [[Glutathione S-Transferase(GST)]] – Glutathione Agarose Bead
-   [[His-tag]] – Nikel bead
-   [[Biotin]] – Streptavidin bead

최근에는 [[Magnetic bead]] 라고 해서 centrifugation 하는 것이 아니라 **자석의 힘으로 bead를 pull down 할 수 있는 bead들도 많이 사용된다**.

![[Pasted image 20230208102410.png]]

## 2. GST-pull down을 수행하기 위한 선결 조건

Pull down assay를 수행하기 위해서는 반드시 하나 이상의 단백질을 tagging protein 형태로 정제해야 한다는 것이다. Tagging protein에 결합할 수 있는 bead를 이용하여 pull down할 것이기 때문이다. **반드시 하나 이상의 단백질은 tagging 단백질 있도록 정제되어야 한다.**

## 3. GST-pull down protocol (요약)

1.  Tagging 단백질이 fusion 되어 있는 형태로 정제한다.
2.  정제된 단백질과 interaction을 확인 할 단백질 혹은 cell lysate를 buffer와 함께 섞어준 후 단백질이 결합할 수 있도록 충분히 반응시킨다.
3.  반응이 끝난 단백질 복합체가 들어있는 튜브에 Bead를 넣고 반응시킨다.
4.  반응이 끝난 tube를 원심 분리하여 bead+단백질복합체를 pull-down시킨다.
5.  비특이적인 반응을 제거하기 위해서 washing buffer로 washing한다.
6.  Western blot을 수행하여 단백질의 결합을 확인한다.

## 4. Pull down assay vs [[Immunopreicipitation]]

**기본적으로 Bait(미끼) 단백질을 침강시켜서 interaction하고 있는 단백질들을 동정한다는 실험 목적은 같다.** 또한, 마지막에 interaction을 확인하는 방법까지도 western blot과 동일하다. 하지만 단백질을 인지하는 방법과 bead의 종류가 다르며, **pull-down assay의 경우에는 반드시 하나 이상의 단백질에 tagging 단백질이 fusion되어 있어야 한다.**

|                      | GST-Pull down                                                     | [[Immunoprecipitation]]                          |
| -------------------- | ----------------------------------------------------------------- | -------------------------------------------- |
| Bait 단백질 인지방법 | Tagging protein과 bead의 결합 <br>(Tag protein - bead 결합)           | 해당 단백질과 항체간의 결합<br> (항원-항체 반응) |
| 침전방법 (Bead)      | GST - Glutathione agarose<br> His-tag - Nikel<br> Biotin - Streptavidin | immunoglobulin - A/G agarose bead            |
| 단백질 확인 방법     | [[Western blot]]                                                      | [[Western blot]]                                 |


## 5\. Pull-down assay 연관 포스팅

> [**Pull-down assay buffer**](https://bio-chae.com/gst-pull-down-buffer/)
> **[Pull down asssay protocol](https://bio-chae.com/pull-down-assay-protocol/)**