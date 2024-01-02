---
title: Gibson Assembly cloning (깁슨 어셈블리 클로닝)
creation_date: 23.09.25
note_type: Webclips
category: 
memo_level: 
aliases:
  - 깁슨 어셈블리 클로닝
tags:
  - 실전_실험_프로토콜_101
  - BRIC
  - cloning
---

Parent : [[_Webclips]]

[[ReadItLater]] [[Article]]

https://www.ibric.org/bric/trend/bio-series.do?mode=series_view&newsArticleNo=8882240&articleNo=8882807&beforeMode=latest_list#!/list

다양한 스토리를 담고 있는 연재를 만나보세요.

\[실전 실험 프로토콜 101\] #19. Gibson Assembly cloning (깁슨 어셈블리 클로닝)

Bio통신원(세오)

-   등록일 2023.08.18
-   조회 1335

지난 연재에서 “유전자 무작위 돌연변이 (Site saturation mutant library)”를 만드는 방법을 소개하였습니다 (출처 1). 엔자임을 처리한 플라스미드와 인서트를 사용해서 라이게이션을 할 경우, 플라스미드 사이즈가 큰 경우에는 transformation이 잘 안 되는 경우도 있습니다. 이러한 문제점을 해결하기 위해서 이번 연재에서는 엔자임을 처리한 것보다 더 좋은 라이게이션 성공률로 원하는 플라스미드를 만드는 것을 소개하겠습니다.      

깁슨 어셈블리는 DNA 단편의 길이와 말단의 호환과 상관없이 여러 개의 DNA 단편을 제한 효소를 처리하지 않고 연결할 수 있습니다 (그림 1). 따라서 큰 DNA  구조를 만드는 데 사용하기 쉽습니다. 또한 깁슨 어셈블리는 단 하나의 튜브에서 여러 겹의 DNA 단편들을 같이 넣어서 효율적으로 처리할 수 있습니다 (노트 1, 그림 1, 2).

  
**제한효소를 사용한 벡터와 PCR로 만든 인서트를 어셈블리를 위한 프라이머**

NEBuilder Assembly Tool를 이용해서 겹치는 PCR 프라이머를 디자인하거나, 혹은, 직접 프라이머를 디자인합니다 (노트 2). Tm은 48°C보다 높게 15-20nt 겹치게 디자인합니다 (노트 3). 제한효소로 선형화한 벡터 (linearized vector)에서 전체 겹치는 시퀀스는 벡터 시퀀스로 해야 하고, 인서트를 증폭할 때 사용하는 프라이머를 추가해야 합니다 (그림 2). 벡터에서 사용된 제한효소 사이트는 어셈블리되면 사라질 수 있지만, 기존의 제한효소 부위를 복원하거나 새로운 제한효소 부위를 도입하기 위해 뉴클레오타이드를 추가할 수 있습니다. 제한효소를 사용해서 선형화된 벡터를 만들 때, 일반적으로 두 개의 제한 효소를 사용하여 엔자임을 처리하면 절단되지 않은 벡터를 줄일 수 있습니다.

![upload_image](Room_0_metadata/Shelf_0_Resource/upload_image.jpeg)

**그림1. 깁슨 어셈블리 클로닝 방법 (출처: 2)**

**깁슨 어셈블리 클로닝 프로토콜 (그림 2)**

1.  DNA 단편들이 적당히 겹칠 수 있게 프라이머를 디자인합니다 (노트 2).  
     
2.  Q5 High-Fidelity DNA polymerase를 이용하여 타깃 단편을 증폭합니다.  
     
3.  PCR로 증폭하고, 젤 러닝을 통해서 타깃 단편들을 확인하고, 타깃 부분만 뽑아서 농도를 측정합니다.  
     
4.  제한 효소를 통해 선형화된 벡터를 준비합니다.  
     
5.  위에서 준비한 단편들과 선형화한 벡터를 깁슨 어셈블리 master 믹스에 넣고 50°C에서 15분 동안 처리합니다 (처리 시간을 60분으로 하면 어떤 경우에는 결합 효율이 더 높아집니다).  
     
6.  1:3 dilution으로 라이게이션을 합니다 (nebiocalculator.neb.com).  
     
7.  DNA 단편이 1 혹은 2개인 경우는 0.02-0.5pmols 사용하고, 단편이 4-6개인 경우에는 0.2-1.0pmoles 사용합니다 (노트 4).   
     
8.  농도를 측정하고 결합을 설정합니다.
    
    |                                 | 2-3 Fragment Assembly |
    | ------------------------------- | --------------------- |
    | Total Amount Fragments          | 0.02-0.5pmols, Xµl    |
    | Gibson Assembly Master Mix (2X) | 10µl                  |
    | Deionized H2O                   | 10-Xµl                |
    | Total Volume                    | 20µl                  |
    
9.  NEB 5-apha competent 셀을 이용해서 트랜스포메이션 합니다. 항생제 (예, Ampicillin)와 IPTG/Xgal를 이용해서 콜로니를 스크린 합니다.  
     
10.  다음날 콜로니를 계수하고, 콜로니 효율을 계산합니다 (CFU/ml \[no. of colonies x dilution factor / volume of culture plate\]).  
     
11.  자란 콜로니 일부를 콜로니 PCR을 통해서 라이게이션 성공 여부를 결정하고, positive 한 샘플만 시퀀싱을 보내어 라이게이션 여부를 확인합니다 (노트 5).  
     

![upload_image](Room_0_metadata/Shelf_0_Resource/upload_image-1.jpeg)

**그림 2. 제한효소로 선형화된 벡터와 PCR로 만든 인서트와의 어셈블리 (출처: 3)**

  
**노트**

1.  깁슨 어셈블리 master mix는 세 가지 다른 효소 활동이 포함되어 있습니다: 1) 엑소뉴클레아제는 한쪽 끝에서 상보적으로 공유하는 단편 (15-80bp)의 어닐링을 쉽게 하는 단일 가닥의 3’ 오버행을 생성합니다. 2) Proprietary DNA 중합효소는 각각의 어닐링 된 단편 내의 틈을 채웁니다. 3) DNA ligase는 조립된 DNA의 깨진 곳을 연결합니다.
2.  NEBuilder Assembly Tool은 빠르고 쉽게 겹치는 프라이머 (두 단편 사이의 겹치는 지역의 15-25nt)를 디자인할 수 있습니다.
3.  Tm은 Tm 계산기를 통해 할 수 있습니다 ([www.neb.com/TmCalculator](http://www.neb.com/TmCalculator)).
4.  결합의 효율은 단편의 길이가 증가할수록 성공률은 줄어듭니다. pmols 계산은 NEBioaclculator를 이용합니다.
5.  실제 실험을 통해 17kb의 벡터와 1kb 인서트의 깁슨 어셈블리 성공률은 67.5% 나왔습니다. 제한효소를 처리한 벡터와 제한효소를 처리한 인서트를 이용한 라이게이션 실험에서의 성공률은 67.5%에 훨씬 미치지 못했습니다.   

**출처**

1.  [https://www.ibric.org/myboard/read.php?Board=news&id=352366&fbclid=IwAR0562siLTfcujeYeLs8kRjiFAM3QsbMpDHUVq43RsUdu7DNWhdPQp7AFW0](https://www.ibric.org/myboard/read.php?Board=news&id=352366&fbclid=IwAR0562siLTfcujeYeLs8kRjiFAM3QsbMpDHUVq43RsUdu7DNWhdPQp7AFW0)  
     
2.  [https://www.neb.com/protocols/2012/09/25/gibson-assembly-master-mix-assembly](https://www.neb.com/protocols/2012/09/25/gibson-assembly-master-mix-assembly)  
     
3.  [https://www.neb.com/applications/cloning-and-synthetic-biology/dna-assembly-and-cloning/gibson-assembly](https://www.neb.com/applications/cloning-and-synthetic-biology/dna-assembly-and-cloning/gibson-assembly)

본 기사는 네티즌에 의해 작성되었거나 기관에서 작성된 보도자료로, BRIC의 입장이 아님을 밝힙니다. 또한 내용 중 개인에게 중요하다고 생각되는 부분은 사실확인을 꼭 하시기 바랍니다.  
[\[기사 오류 신고하기\]](mailto:news@ibric.org "이메일 보내기")

[![[실전 실험 프로토콜 101] #19. Gibson Assembly cloning (깁슨 어셈블리 클로닝)](Room_0_metadata/Shelf_0_Resource/[실전%20실험%20프로토콜%20101]%2019.%20Gibson%20Assembly%20cloning%20(깁슨%20어셈블리%20클로닝).do)](https://www.ibric.org/bric/trend/bio-series.do?mode=series_view&newsArticleNo=8882240&articleNo=8882807&beforeMode=latest_list#a "실전 실험 프로토콜 101 자세히 보기")

진행 [실전 실험 프로토콜 101](https://www.ibric.org/bric/trend/bio-series.do?mode=series_view&newsArticleNo=8882240&articleNo=8882807&beforeMode=latest_list#a "실전 실험 프로토콜 101 자세히 보기")

논문에 나온 실험을 따라서 하고 싶어도 논문에 실험 절차가 너무 간략하게 소개되어 있거나, 자세한 설명이 없어서 실험을 따라 하기가 어려운 경우가 종종 있습니다. 이럴 경우 '같은 실험실 혹은 주위 실험실에서 실제로 유사한 실험을 한 사람의 실험 노트가 있다면 얼마나 좋을까?' 라고 자주 생각했습니다. 이번 연재를 통해 제가 실험실에서 배운 내용을 같거나 비슷한 분야에서 연구하는 분들과 나누고자 합니다. 물론 제가 소개하는 내용이 최고라고 생각하지 않고, 소개하는 내용보다 더 좋은 실험 방법이 있다고 생각합니다. 이러한 자신만이 알고 있는 실험 방법을 공유하여 주시면, 같은 길을 걷고 있는 분들에게 도움이 되리라 생각합니다.

-   세오 (필명)

-   [![[실전 실험 프로토콜 101] #20. MBP 퓨전 단백질 시스템을 이용한 결합 단백질 찾기](Room_0_metadata/Shelf_0_Resource/[실전%20실험%20프로토콜%20101]%2020.%20MBP%20퓨전%20단백질%20시스템을%20이용한%20결합%20단백질%20찾기.do)](https://www.ibric.org/bric/trend/bio-series.do?mode=series_view&newsArticleNo=9864709&articleNo=8882807&beforeMode=latest_list&article.offset=0&articleLimit=10 "[실전 실험 프로토콜 101] #20. MBP 퓨전 단백질 시스템을 이용한 결합 단백질 찾기 자세히보기")
    
    -   2023.09.22
    -   조회수388
    -   답변0
    -   추천추2
    
-   [![[실전 실험 프로토콜 101] #18. 유전자 무작위 돌연변이(Site saturation mutant library)](Room_0_metadata/Shelf_0_Resource/[실전%20실험%20프로토콜%20101]%2018.%20유전자%20무작위%20돌연변이(Site%20saturation%20mutant%20library).do)](https://www.ibric.org/bric/trend/bio-series.do?mode=series_view&newsArticleNo=8881046&articleNo=8882807&beforeMode=latest_list&article.offset=0&articleLimit=10 "[실전 실험 프로토콜 101] #18. 유전자 무작위 돌연변이(Site saturation mutant library) 자세히보기")
    
    -   2023.06.28
    -   조회수2002
    -   답변0
    -   추천추0
    
-   [![[실전 실험 프로토콜 101] #17. Colony formation assay (콜로니 생성 분석)](Room_0_metadata/Shelf_0_Resource/[실전%20실험%20프로토콜%20101]%2017.%20Colony%20formation%20assay%20(콜로니%20생성%20분석).do)](https://www.ibric.org/bric/trend/bio-series.do?mode=series_view&newsArticleNo=8878591&articleNo=8882807&beforeMode=latest_list&article.offset=0&articleLimit=10 "[실전 실험 프로토콜 101] #17. Colony formation assay (콜로니 생성 분석) 자세히보기")
    
    -   2023.03.20
    -   조회수2740
    -   답변0
    -   추천추5
    

[![메쎄이상](Room_0_metadata/Shelf_0_Resource/메쎄이상.png)](https://www.ibric.org/app/advertise/banner.do?id=27736 "새창열림")