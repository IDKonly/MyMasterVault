---
title: 옵시디언 템플레이터(Templater) - Callout 넣기
creation_date: 2
note_type: Webclips
aliases: 
tags:
  - 옵시디언_업그레이드하기
---

[[ReadItLater]] [[Article]]

# [옵시디언 템플레이터(Templater) - Callout 넣기](https://eoureo.tistory.com/19)

Callout(말풍선, 설명글?)의 모양과 색을 보면서 골라 노트에 삽입할 수 있습니다.

얼마 전에 다음 글을 보게 되었습니다.

  
템플레이터를 이용하여 Callout을 넣는 템플릿을 소개하는 글이었습니다. 글 올리신 분이 한글화까지 해서 좋았습니다. 조금 아쉬운 점이 있었지만 간단하게 만들어 쓰는 템플릿의 개념에 맞다고 느꼈습니다. 

이왕이면 Callout의 모양과 색을 바로 볼 수 있으면 좋겠다는 생각이 들었습니다. 그러다가 "교보문고 도서 검색" 템플릿([https://eoureo.tistory.com/16](https://eoureo.tistory.com/16))의 책 목록을 보여주는 대화상자를 만들면서 조금만 소스 코드를 바꾸면 될 것 같아 만들기 시작하였습니다.

간단하게 만들려고 했는데 만들다 보니 욕심이 많아져 이렇게 소스 코드가 길어졌네요.

다음 슬라이드에서 템플릿 설정과 사용방법을 볼 수 있습니다.(전체화면으로 보세요.)

[https://docs.google.com/presentation/d/1CYcctNATvw-xMKbWtZiSw7hj5oT0jvXU4Cu8\_doQ5qw/edit?usp=sharing](https://docs.google.com/presentation/d/1CYcctNATvw-xMKbWtZiSw7hj5oT0jvXU4Cu8_doQ5qw/edit?usp=sharing) 

템플릿 파일 첫머리에 어떤 방식으로 쓸 것인지를 설정할 수 있습니다.

  
run\_type = 0; // callout 형식만 대화상자에서 고른 다음 바로 노트에서 글 작성  
run\_type = 1; // 폴딩과 제목, 내용을 따로따로 입력 (키보드만으로 내용을 입력할 수 있음.)  
run\_type = 2; // 폴딩과 제목, 내용을 하나의 대화 상자에서 입력 (callout 모양 그대로 보며 내용을 입력할 수 있음)

각 방법이 나름의 장점이 있겠지요.

저는 0번 방법이 옵시디언에 더 맞다고 생각합니다. 모양과 색으로 Callout을 고르고 바로 글을 입력하면 되니까요.

1과 2번 방법도 여러 줄을 붙여 넣기 할 때 쓸모가 있겠네요.

## 소스 코드

제 Gist 코드입니다.

## 만들면서

다음은 이 템플릿을 만들면서 살펴본 내용들입니다.

관심이 있으면 한번 보기 바랍니다.

도움이 되었으면 합니다.

-   되도록 obsidian 자체의 스타일로 callout을 보여주도록 했습니다(기본 테마 클래스로 스타일 지정).
-   callout 안의 callout을 사용할 수 있습니다 (callout 중첩).
-   이전 소스 코드를 되도록 바꾸지 않으려고 했습니다.

템플레이터 함수 tp.system.suggest로는 간단한 리스트만 만들 수 있어 Callout 배경색을 넣을 수 없었습니다. 그래서 옵시디안의 SuggestModal을 확장하여 만들었습니다.

Modals | Obsidian Plugin Developer Docs    
[https://marcus.se.net/obsidian-plugin-docs/user-interface/modals](https://marcus.se.net/obsidian-plugin-docs/user-interface/modals) 

템플릿을 넣은 다음 노트 파일에 커서가 나오지 않아 바로 글을 쓸 수가 없었습니다. 해결방법은 구글링 하여 찾을 수 있었습니다. 다음 글에 올려 봤습니다.

[https://eoureo.tistory.com/17](https://eoureo.tistory.com/17)

[

옵시디언 템플레이터 - 실행한 다음 에디터가 활성화(focus) 안됨. - 임시 해결

"Templater" 실행이 끝난 다음 "Editor"가 활성화(fucus) 되지 않습니다. 노트 파일에서 커서(caret)가 보이지 않습니다. 그래서 이어서 바로 글을 작성할 수 없습니다. 그렇지만 "Template"에서는 바로 이어

eoureo.tistory.com



](https://eoureo.tistory.com/17)![](Room_0_metadata/Shelf_0_Resource/img-3.png)

Callout을 중첩하려고 할 때 노트의 커서가 있는 행과 열을 알아야 했습니다. 그 내용도 따로 페이지를 만들어 올렸습니다.

[https://eoureo.tistory.com/18](https://eoureo.tistory.com/18)

[

옵시디언 템플레이터 - 실행 노트에서 커서 위치를 얻는 방법

템플레이터에서 템플릿이 삽입될 곳의 위치를 알면 쓸모가 많습니다. Callout을 넣으려고 할 때 커서가 위치한 곳에 넣을 수 있는지 확인할 수 있습니다. 또 Callout 안에 Callout을 넣으려 할 때 커서

eoureo.tistory.com



](https://eoureo.tistory.com/18)![](Room_0_metadata/Shelf_0_Resource/img-4.png)

많은 댓글 바랍니다. 사소한 댓글도 환영합니다.

이 글이 도움이 되었다면 밑의 공감 버튼을 눌러주세요.

글쓴이에게 힘이 됩니다.