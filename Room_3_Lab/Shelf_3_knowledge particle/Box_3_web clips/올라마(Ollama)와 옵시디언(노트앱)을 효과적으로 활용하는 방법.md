---
title: 올라마(Ollama)와 옵시디언(노트앱)을 효과적으로 활용하는 방법
creation_date: 2
note_type: Webclips
category: 
memo_level: 
aliases: 
tags:
  - AI
  - 옵시디언_업그레이드하기
---

Parent : [[_Webclips]]

[[ReadItLater]] [[Article]]

# [올라마(Ollama)와 옵시디언(노트앱)을 효과적으로 활용하는 방법](https://anpigon.tistory.com/441)

이전 글에서는 올라마(Ollama)에 대한 기본적인 소개를 하였습니다(참고: [로컬에서 무료로 사용할 수 있는 LLM 도구, Ollama 활용 가이드](https://anpigon.tistory.com/434)). 이번 글에서는 올라마(Ollama)를 옵시디언 노트앱에서 어떻게 활용할 수 있는지 상세히 안내하고자 합니다.

## 올라마와 윈도우OS: 호환성 문제 해결

올라마는 현재 윈도우OS를 아직 지원하지 않습니다. 하지만 WSL2 또는 Docker를 통해 올라마를 실행할 수 있습니다. 또는 윈도우를 지원하는 대안 프로그램인 [LM Studio](https://lmstudio.ai/)를 고려할 수도 있습니다.

## 올라마 AI모델 설치 및 실행

올라마의 설치 및 모델 다운로드는 매우 간단합니다. 먼저 [ollama.ai](https://ollama.ai/)에서 올라마를 다운로드하여 설치합니다. 그리고 아래의 명령어를 통해 `mistral` 모델을 다운로드합니다.

```
ollama pull mistral 
```

시작하기 위해서는 다음 명령을 사용합니다:

```
OLLAMA_ORIGINS=* ollama serve 
```

> **중요**: OLLAMA\_ORIGINS=\* 옵션은 옵시디언에서 CORS 오류를 방지하기 위해 필수입니다.

![터미널에서 ollama 서버를 실행한 결과 화면](Room_0_metadata/Shelf_0_Resource/터미널에서%20ollama%20서버를%20실행한%20결과%20화면.png)

만약 아래와 같은 메시지가 표시된다면, 이미 실행 중인 올라마 서버를 종료해야 합니다.

![](Room_0_metadata/Shelf_0_Resource/img-2.png)

환경변수 설정은 터미널에서만 가능합니다. 만약 메뉴 표시줄에 올라마 아이콘이 보인다면, 올라마 아이콘을 클릭하고 "Quit Ollama"를 선택하여 서버를 종료할 수 있습니다.

![](Room_0_metadata/Shelf_0_Resource/img-2.png)

올라마 서버가 성공적으로 실행되었다면, 다음과 같이 API 호출을 할 수 있습니다.

```
curl http://localhost:11434/api/chat -d '{
  "model": "mistral",
  "messages": [
    { "role": "user", "content": "why is the sky blue?" }
  ]
}'
```

**성공적인 API 호출 결과:**

![](Room_0_metadata/Shelf_0_Resource/qoTFPIa.png)

환경변수와 올라마 서버 설정에 대한 추가 정보는 [올라마 FAQ](https://github.com/jmorganca/ollama/blob/main/docs/faq.md#how-do-i-use-ollama-server-environment-variables-on-mac) 페이지에서 찾을 수 있습니다.

> **참고**:  
> OLLAMA\_HOST 환경변수를 사용하면 올라마 서버 IP와 PORT 번호를 변경할 수 있습니다. (기본값은 127.0.0.1:11434 입니다.)

## 옵시디언에서 올라마를 활용하는 방법: Text Generator 플러그인

올라마 공식 홈페이지에서는 [obsidian-ollama 플러그인](https://obsidian.md/plugins?id=ollama)을 소개하고 있습니다. 하지만 여기서는 제가 익숙한 [Text Generator 플러그인](https://obsidian.md/plugins?id=obsidian-textgenerator-plugin)을 사용해서 올라마를 활용하는 방법을 설명하겠습니다. 추후에 기회가 되면 obsidian-ollama 플러그인 사용법도 소개해드리겠습니다.

### 옵시디언 Text Generator 플러그인 설치 및 설정

옵시디언에서 [Text Generator 플러그인](https://obsidian.md/plugins?id=obsidian-textgenerator-plugin)을 설치합니다. 그 후, Text Generator 플러그인 설정화면에서 아래와 같이 설정을 완료합니다.

-   LLM Provider: **Ollama**
-   Model: **mistral**
-   Base Path: `http://localhost:11434`

![](Room_0_metadata/Shelf_0_Resource/img-2.png)

### 올라마를 사용한 문장 생성

옵시디언에서 노트를 작성하다가 ollama를 호출할 때는 `/`를 입력해 명령어 창을 불러옵니다. 그리고, "Text Generator: Generate Text!"를 선택하면 됩니다. 또는 단축키 `Cmd` + `J`를 사용할 수도 있습니다

![명령어 입력 화면 1](Room_0_metadata/Shelf_0_Resource/명령어%20입력%20화면%201.png)

조금 기다리면 자동으로 텍스트가 생성됩니다.

![](Room_0_metadata/Shelf_0_Resource/mvSlgef.png)

### 프롬프트 템플릿을 활용한 고급 사용

옵시디언에서 노트를 작성하다가 `/`를 입력해 명령어 창을 불러오고, "Text Generator: Templates: Generate & Insert"를 선택한 후, 미리 정의한 프롬프트 템플릿을 사용합니다.

![명령어 입력 화면 2](Room_0_metadata/Shelf_0_Resource/명령어%20입력%20화면%202.png)

그리고 미리 정의한 프롬프트 템플릿을 선택합니다. 아래 화면에 보이는 "설명해주세요"는 제가 미리 정의한 프롬프트 템플릿입니다.

![템플릿 선택 화면](Room_0_metadata/Shelf_0_Resource/템플릿%20선택%20화면.png)

그리고 잠시 기다리면 정의된 템플릿에 따라 텍스트가 생성됩니다.

![](Room_0_metadata/Shelf_0_Resource/CQT1GMA.png)

### 프롬프트 템플릿 예시:

````
---
promptId: explain
name: 👼설명해주세요
tags:
  - thinking
  - writing
version: 0.0.1
---
다음 내용에 대해 전문적으로 설명해주세요. 

```
{{tg_selection}}
```
````

> 템플릿 문법에 대한 자세한 설명은 [Text Generator 플러그인 문서](https://docs.text-gen.com/_notes/3-+Templates/01+Understanding+Context)에서 확인하실 수 있습니다.

### 올라마 한국어 답변 가능성

프롬프트 템플릿에서 한국어로 대답을 요청하면 한국어로 대답이 제공됩니다. 그러나, 한국어 답변의 퀄리티는 많이 부족합니다.

![한국어 답변 화면](Room_0_metadata/Shelf_0_Resource/한국어%20답변%20화면.png)

일단은 영어로 답변을 받고 구글 번역기나 DeepL과 같은 번역 서비스를 이용하는 것이 더 나을 수 있습니다.

## 마치며

이 글은 옵시디언 사용자들이 효과적으로 Text Generator 플러그인을 활용하는 방법을 소개하기 위해 작성되었습니다. 옵시디언과 관련된 다른 유용한 플러그인이나 기능들에 대해서도 알아보시는 것을 추천드립니다.

---

[![](https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20coffee&emoji=&slug=anpigon&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff)](https://www.buymeacoffee.com/anpigon)

*or*

[\[카카오페이로 후원하기\]](https://anpigon.github.io/buymeacoffee/) [\[토스페이로 후원하기\]](https://toss.me/anpigon/)