---
_filters:
  - type: any
    trueFalse: true
    filters:
      - type: filemeta
        field: tags
        fType: tags-multi
        fn: isAnyInList
        value: "#excalidraw"
---
