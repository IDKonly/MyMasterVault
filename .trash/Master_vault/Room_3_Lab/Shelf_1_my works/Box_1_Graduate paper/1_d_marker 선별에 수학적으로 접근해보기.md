---
title : 1_d_marker 선별에 수학적으로 접근해보기
creation_date : 22.10.20
last_modified :
note_type : basic
category : thinking
memo_level :
aliases : 
tags : []
---

Parent : [[1_Saccharomyces cerevisiae의 telomeric silencing 연구를 위한 새로운 마커 유전자의 탐색_intro]]

![[Pasted image 20221020214413.png]]
준수형이 고른 타겟 유전자들을 봤을때, 이런 분포도가 나왔다.
이런식으로 보면 거리변화는 발현변화에 그다지 유의미해 보이지 않는다.

데이터가 너무 적기 때문에 편향적으로 보이는 것일지도 모른다는 생각에
모든 유전자를 대상으로 동일한 그림을 그려보기로 했다.
그래서 전체를 대상으로 유전자 발현변화를 살펴보면

![[Pasted image 20221020214637.png]]
이렇게 염색체 말단으로 갈수록 더 퍼지는 그림이 나온다.
그니까... 거리변화는 사실 유의미하다.

염색체의 각 팔의 길이는 일정하지 않기 때문에, 가장 작은 팔의 길이(~105kbp)를 기준으로 자르고, 표현된 유전자의 갯수가 너무 많기 때문에 P-value가 너무 높은 유전자(>0.5)들은 목록에서 제외했다.

![[Pasted image 20221020214838.png]]

그러면 명확하게 말단부위에 발현이 감소되는 구간이 있음을 확인할 수 있는데,
Sir2에 의해서 발현이 줄어들었음을 확인하고 싶다.
sir2는 [[sir2 spreading]]에 의해서 확률적으로 연장되므로, 이론적으로 지수함수 그래프를 따를것이다.

![[Pasted image 20221020215044.png]]

정확하다고 하기는 힘들지만, 가장 근사한 지수함수를 그래프에 적용해서 그려보았다.
$$y= 6.5*0.85^{x/1000}+2$$
그러면 Sir2에 의해서 지배적으로 조절되는 유전자들은 이 주변에 있을것이라고 가정하고, 유전자들을 선별해보았다.
![[Pasted image 20221020215417.png]]

근사한 지수함수의 기울기가 어느정도 있는 상태(y>2.1)에서, 함수 주변(y+-0.5)에 존재하는 유전자들의 log2 fold change를 그려보았을때, 21개의 유전자가 이런 경향을 띄고 있었고, 이중 p value가 0.05 미만인 유전자가 15개, 0.005미만으로 특별히 유의미하게 변했다고 판단할 수 있는 유전자가 11개였다.

![[Pasted image 20221020215838.png]]

이중에 기존에 선별한 유전자랑 겹치는게 5개, 근접한 유전자가 2개.
이전에 했던 실험결과랑 비교해보면 

![[Pasted image 20221020220023.png]]

이렇게 된다

기본적인 발현량이 크지 않으면 감지가 잘 안되는듯
내 생각엔 AAD15의 경우도 비슷한 이유일거라고 생각함.
최소한 발현량이 200언저리는 되어야 PCR로 감지가 가능할 것 같음.

>조졌다!

# 의문
[[1_d_Q_ERR 단백질들은 뭐하는 놈들인데 자꾸 끼는거야?]]
[[1_d_Q_silencing facter가 없어졌는데 발현량이 떨어지는 놈들은 뭐하는 놈들이지?]]
[[1_d_Q_추세선에서 크게 벗어나는 애들은 뭐하는 애들이지?]]