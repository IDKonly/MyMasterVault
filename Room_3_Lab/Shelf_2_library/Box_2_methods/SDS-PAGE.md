---
title : SDS-PAGE
creation_date : 23.02.06
last_modified :
note_type : method
category : []
aliases : 
tags : [protein]
---

Parent : [[_Methods]]

# method

## Sample
[[Rapid Perparation of nuclear extract from Yeast cells for western blot]]에서 얻은 단백질샘플을 이용한다.

## SDS gel
2가지 종류의 gel을 이용한다.

### Running gel
| Agent                | 5%   | 6%   | 7%   | 8%   | 9%   | 10%  | 12%  | 15%  |
|----------------------|------|------|------|------|------|------|------|------|
| 40% Acrylamide       | 625  | 750  | 875  | 1000 | 1125 | 1250 | 1500 | 1875 |
| ddH2O                | 3020 | 2895 | 2770 | 2645 | 2520 | 2395 | 2145 | 1770 |
| 1.5M Tris-HCl pH 8.8 | 1250 | 1250 | 1250 | 1250 | 1250 | 1250 | 1250 | 1250 |
| 10% SDS              | 50   | 50   | 50   | 50   | 50   | 50   | 50   | 50   |
| 10% APS              | 50   | 50   | 50   | 50   | 50   | 50   | 50   | 50   |
| TEMED                | 5    | 5    | 5    | 5    | 5    | 5    | 5    | 5    |
APS; Ammonium persurfate

1. APS와 TEMED 첨가 직후에 살짝 흔들어 섞어 준뒤, 바로 gel 틀에 붓는다.
2. 젤의 상단부분을 평평하게 만들어주기 위해서, 70% 에탄올을 위에다가 붓는다. (약 2~3ml정도. 가득 찰때까지.)
3. 15분 정도면 굳고, 최대 30분이면 다 굳는다.

### Stacking gel
| Agent              | 1    | 2    | 3    | 4    |
|--------------------|------|------|------|------|
| 40% Acrylamide     | 228  | 456  | 684  | 912  |
| ddH2O              | 1849 | 3698 | 5547 | 7396 |
| 1M Tris-HCl pH 6.8 | 370  | 740  | 1110 | 1480 |
| 10% SDS            | 25   | 50   | 75   | 100  |
| 10% APS            | 25   | 50   | 75   | 100  |
| TEMED              | 3    | 6    | 9    | 12   |
Running gel 위에 Stacking gel을 굳혀서 만든다.

1. 알코올을 덜어내고, stacking gel을 붓는다.
2. 그 후, comb를 꽂고 15분 이상 굳힌다.

## PAGE

1. 젤과 고정대(?)를 조립하고, 통 안에 체결한다.
	1. 젤이 홀수개라면, 남는 위치에는 버퍼 댐(buffer dam)을 체결해준다.
	2. 안쪽에는 새 버퍼를 사용해야 하기 때문에 이렇게 한다.
2. 안쪽에 새 EB buffer를 붓고, 바깥에는 쓰던 EB buffer를 붓는다.
	1. 바깥쪽에 버퍼를 부으면 대개 안쪽에 있던 buffer가 새어나와 상대적으로 부족해지는데, 이 버퍼를 다시 채워넣어준다.
3. 디자인한대로 sample을 로딩한다.
	1. 두꺼운 유리판 방향 기준으로 왼쪽부터 1번.
	2. 기본적으로 marker - positive control - negative control 다음에 gel을 로딩한다.
4. 젤 하나당 20mA를 걸고, stacking gel에서 벗어나 마커가 분리되기 시작하면 젤 하나당 30mA를 건다.
	1. 이때 전류를 높이지 않거나 늦게 올리는 것은 실험결과에 큰 영향을 주지 않지만, 전류를 낮추는 것은 영향을 줄 수 있다.
5. 이후 [[Western blot#Running the gel and transfer]]를 시행한다.

## Double-point

실험의 정합성을 위해 하나의 샘플을 여러 볼륨으로 로딩하는 것.
굳이 Double point 뿐만 아니라, Triple point 등의 여러 볼륨으로 로딩할 수 있으며
이것은 컨트롤인 H3의 양을 정량해서 어떤 조작에 의한 변화가 일관됨을 확인할때, 굳이 여러 단계의 작업간에 [[SDS-PAGE]]를 여러번 내리지 않아도 되도록 한다.

# Explain 

1. 목적은 결국 단백질을 무게 순서대로 정렬하여 보는 것이다.
2. 길이가 DNA보다 훨씬 짧기 때문에 acrylamind gel을 사용한다.
3. 하지만 이 방법을 DNA와 같은 방법으로 보는 것에는 크게 2가지 정도의 문제가 있다.
4. 첫번째는 단백질들이 각자 고유한 전하를 가지기 때문에, 별다른 처리 없이 전기영동을 할 경우 무게 뿐만 아니라 고유한 전하량에 따라서 분리될 수 있다. 이 문제를 해결하기 위해서 SDS를 처리하게 되는데, 단백질에 처리된 SDS는 2개의 아미노산 당 하나의 SDS가 결합한다. 그럼으로 인해서 단백질 내부의 전하를 SDS가 덮어 씌우는데, 이로인해 단백질은 고유한 전하량을 잃음으로써 해당 문제가 해결된다.
5. 두번째는 단백질들이 2차구조와 같은 형태로 존재하기 때문에, DNA와 같이 분자의 크기와 길이가 비슷하다는 것을 이용한 방법이 어려워지는데, 이는 단백질에 열을 가하면 denaturation 되는 것을 이용해 해결한다. disulfate bonding의 경우, 강력한 공유결합에 해당하기 때문에 베타-멀캅토에탄올과 같은 reducing agent를 투입하여 결합을 끊어준다. 이 처리를 통해 단백질을 linear한 상태의 polypeptide로 만들기 때문에 electrophoresis를 적용할 수 있게 된다.
6. 핵심적인 내용으로 glycine은 pH가 산성조건일때 강한 negative charge를 가지고, 염기조건에서 약한 negative charge를 가지는 특징이 있다. 이것을 이용해서 gel 내부에서 이동속도 차이를 만들어 단백질을 무게별로 분리해낼수 있다.
7. stacking gel에 loading된 샘플은 glycine과 Cl- 이온과 함께 움직이는데, 이때 stacking gel은 pH가 상대적으로 낮기 때문에 glycine이 강한 - charge를 갖게 된다. 그래서, 매우 빠른 속도의 Cl-과 glycine 사이에 있는 단백질이 stacking gel을 벗어나기 전에 정렬된다. 이과정은 모든 단백질이 거의 동일한 위치에서 running되도록 만들어 해상도를 높인다.
8. sample이 stacking gel을 벗어나 runnig gel로 이동하면, 전압을 높여 더 빠른 속도로 이들을 분리해낼수 있도록 하는데, pH가 높아진 상황에서의 glycine은 매우 느린 속도를 가지므로 글라이신과 염소이온 사이에 단백질이 분리된다.

# 참고
[[blog_SDS-PAGE]]
[[Book_SDS-PAGE of proteins]]
[Introduction to SDS-page - MBL](https://www.mblintl.com/resources/scientific-resources/fundamentals-for-planning-research/the-principle-and-method-of-sds-polyacrylamide-gel-electrophoresis-sds-page/)