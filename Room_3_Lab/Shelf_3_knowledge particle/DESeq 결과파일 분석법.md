---
title : 무제 파일
creation_date : 23.01.03
last_modified :
note_type : basic
category :
memo_level :
aliases : 
tags : []
---

Parent : [[_KnowledgeParticle]]
Drived from : [[]]

[[DESeq]]은 read 수 결과값에 0이나 NA를 포함하고 있는 경우가 있는데,
이 경우 [[p-value]]와 [[Padj]] 값이 좋지 않다.
Padj값이 0.5 이상인 경우 아예 유효하지 않다고 취급해서 지우면,
대부분 이런 경우가 사라진다.
